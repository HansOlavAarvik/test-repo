# Notater til git

## kort om git og github
Git er ei samling av koden og kodehistoria di, den blit samla i noko kalla ein "repository" eller "repo". Repoen hugsar alle endringar og versjonar du lagrar til han og lar deg lage greiner av koden din samt mogeleheit til å gå tilbake til tidlegare versjonar. 
Github er ein nettstad ein burker til å dele kode med andre. Dei som har tilgang til å endre ein repo i github kan legge til, hente eller fjerne kode frå github repoen. Github oppererer sømlaust med git arkitekturen.
## Installasjon
Installere git
Definere git e-post og brukarnavn
Lage github brukar

## gode tips
`git help everyday` er ei enkel handbok til som fint forklarar dei mest brukte kommandoane


## Kommandolinje:
- `git --version`
- git status     				    Show the working tree status
- git add .         				make files ready for staging
- git reset					        Remove from stage
- git commit -m “message” 		    Commits to branch
- git log 					        Gir log over siste commit
- git commit -a -m “message”	    Git commit og add I samme linje
- git remote
- 	origin “url”
- 	show origin
- git push “repo” “branch” -u		oppdaterere “repo” “branch” online
- git fetch 				        henter siste commit av repo
- git merge «repo»/»branch» 		Merger saman greiner
- `git pull` 				            henter siste instans av branch, om du b
- git clone «url»				    kloner repo til din maskin



.gitignore 
	Gjer at finavn du legger inn her ikkje blir oppdatert I git

```python
def kul_kode():
    print("lmao")
```    