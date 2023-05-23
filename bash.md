```bash
v=$(< mon fichier)
> monfichier
v='toto:tata'
seg1=${v%%:*} # toto
seg2=${v##*:} # tata
```
Source: https://twitter.com/Florent_ATo/status/1642845017294135297