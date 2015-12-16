
# educloudalliance.org

Sivuston educloudalliance.org lähdetiedostot.

## TODO

* footer: OKM:n hanke
* page: youtube-videot suoraan playlististä?
* page: dokut google driveltä?
* page: github-issuet ja PR:t?
* Travis rakentamaan sivu joka yö


## Työkalut

Sivusto rakentuu https://jekyllrb.com/ työkalulla.

Omalla koneellaan työkalua voi käyttää Dockeria apuna käyttäen komennolla:

    docker run --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll:pages jekyll s --baseurl=

Sivuston pohjateemana on käytetty https://github.com/jeromelachaud/grayscale-theme


## Kontribuutiot

Nosta Githubissa Issue jos mielestäsi sisältöä pitäisi muuttaa.
Myös valmista sisältöä otetaan vastaan.

