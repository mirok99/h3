# Harjoitus H3

Aloitin tehtävän luomalla uuden repositoryn githubiin. Määritin lisenssin ja kuvauksen. Sitten yhdistin gitin xubuntuun komennolla 

	git clone https://github.com/mirok99/h3.git

Lisäsin README tiedoston.

d) Komennolla

	git log

sain tulostettua kaikki gittiin git push komennolla tekemäni muutokset ja niiden hashit. Tulosteessa näkyy myös muokkauksen kellonaika ja tieto muokkaajasta.

Komennolla

	git diff

sain tulostettua gitissä olevan version ja xubuntussa olevan version eron. Esimerkiksi markdown tiedostossa näkyy mitkä rivit on lisätty verrattuna gitissä olevaan versioon. Gitissä viimeisin versio on HEAD. Pystyin vertailemaan esimerkiksi viimeisintä versiota (HEAD) ja toiseksi viimeisintä komennolla

	git diff HEAD^..HEAD

Tämä komento näyttää viimeistä edellisen version ja viimeisimmän version eron. Lähde: https://www.techiedelight.com/find-differences-between-two-commits-git/
