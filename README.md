## Mi rekomendas, ke vi uzu *[PumpedSardines/Tajpi](https://github.com/PumpedSardines/Tajpi)*, se vi volas pli da agordoj.

# klavareto
- eta klavaro por Apple-komputiluzantaj esperantistoj
- uzu la akuton (') por aktivigi la cirkumfleksojn
- ```' + c = ĉ```, ```' + H = Ĥ```

# kiel instali
```
curl -sL \
  https://github.com/draumaz/klavareto/archive/refs/heads/main.tar.gz | \
    bsdtar -xpzf - \
      --strip-components=1 \
      -C "${HOME}/Library/Keyboard Layouts/" \
      klavareto-main/klavareto.bundle
```
- restartigu


# kialo
- mi ŝatas tajpi aksentojn kun la akuto, tamen macOS normale ne subtenas ĉi tion.
