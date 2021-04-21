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

Komennolla

	git blame harjoitus.md

sain näkyviin harjoitus.md tiedoston muokkaushistorian. Historiassa näkyy gittiin lisätyn commitin hash, milloin se on lisätty gittiin ja kuka sen on lisännyt. Markdown tiedostossa näkyy rivikohtaisesti, kuka on lisännyt/muokannut ja milloin.

e) Tein "tyhmän" muutoksen lisäämällä turhaa tekstiä tähän markdowniin. Ajoin komennon

	git reset --hard

Tuloksena git palautti repositoryn edelliseen githubiin lisättyyn versioon. Tulosteessa luki version hash ja commit message.

f) Uutena ohjelmana päätin asentaa VLC työpöytäsovelluksen. Asensin ensin sudo apt install vlc ja kokeilin, että ohjelma toimii. Toimi hyvin.

Tein uuden sls tiedoston joka asentaa vlc:n. VLC:n konfiguraatio löytyy /home/miro/.config/vlc kansiosta, mutta en keksinyt sieltä oikein mitään eritysitä konfiguroitavaa.

![Kuva VLC:n asennus statesta] (https://gyazo.com/9f102f5cdae86ef7a32bc87c8c7ff144)

Kuva VLC:n pkg.installedista.
