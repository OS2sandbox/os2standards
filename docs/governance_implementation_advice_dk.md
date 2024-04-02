# Implementering af styringskriterier

##### 🇬🇧 [Read in english](../docs/governance_implementation_advice_en.md)

_[OS2's governance model](https://www.os2.eu/governancemodellen) er oprindeligt skrevet til et ikke kode-nært publikum. For at uddybe og gøre de opridsede mål mere operationelle er denne guide en række implementeringsmetoder til hurtigt og nemt at komme i gang med at være compliant_

## Kom godt i gang
_Sådan kommer du i gang med at sikre at dit projekt er kompatibelt med [OS2's governance model](https://www.os2.eu/governancemodellen)_

- Alt kildekode og dokumentation til projektet placeres i repositorier under en GitHub organisation der er ejet af OS2.

- Udvikling af ny kildekode og dokumentation følger et [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)

- Dokumentation, der både beskriver anvendelse, men også hvordan man hurtigt kommer i gang med at udvikle og bidrage, placeres i et dokumentations repositorie under samme organisation, og bygger automatisk et søgbart dokumentations site. En simpel template til dette findes her: https://github.com/OS2offdig/OS2-docs-template

- Hvert repo har et team af maintainers, teamet kan besættes af leverandører eller tilstrækkeligt trænede udviklere/anvendere. 

- Hver projekt har en projekt-koordinator der holder styr på og delgerer issues og opdeler dem i milestones på GitHub. Det tilgængelige projekt-budget dikterer hvordan disse roller besættes.

- Projekterne opbygges som genbrugelige, veldokumenterede services der kommunikerer ind og ud via åbne standardprotokoller. Forretningslogik, standardkommuniakationskode og service orkestrering placeres i selvstændige overskuelige moduler sammen med dokumentation og udrulningsmetoder i kode. På den måde sænkes barren for at udvikle en exit strategi og åbne op for leverandørsamarbejder. Et PoC på en skabelon til dette er tilgængelig her-> https://github.com/OS2sandkasse/dev-polyglot-microservices


- Der bygges automatiskt container-images af dem, hver gang der er godkendt en pull-request og ny, testet kode merges in i hoved branchen.
En færdig skabelon til dette er ikke tilgængelig, men der kan hentes inspiration i denne PoC -> https://github.com/OS2sandkasse/dev-polyglot-microservices/blob/main/.github/workflows/build.yml

