# Operational Governance

_OS2.eus governance model (https://www.os2.eu/governancemodellen) er oprindeligt skrevet til et ikke kode-nært publikum. For at uddybe og gøre de opridsede mål mere operationelle er denne guide en række implementeringsmetoder til hurtigt og nemt at komme i gang med at være compliant_

## Getting Started

- Det primære kode-repo ligger under en os2 styret GitHub organisation og der følges et GitHub flow - Officielle docs: https://docs.github.com/en/get-started/using-github/github-flow

- Hvert repo har et team af maintainers, teamet kan besættes af leverandører eller tilstrækkeligt trænede udviklere/anvendere. Hver projekt har en projekt-koordinator der holder styr på og delgerer issues og opdeler dem i milestones på GitHub. Det tilgængeligt projekt-budget dikterer hvordan disse roller besættes.

- Dokumentation, der både beskriver anvendelse, men også hvordan man hurtigt kommer i gang med at udvikle og bidrage, placeres i et doc-repo under samme organisation, og bygger automatisk (via github-actions) et søgbart dokumentations site på GitHub pages. En simpel template er udarbejdet til dette: https://github.com/OS2offdig/OS2-docs-template

- Projekterne opbygges som genbrugelige, veldokumenterede services der kommunikerer ind og ud via åbne standardprotokoller. f.eks REST og der bygges automatiskt container-images af dem (med github_actions, det har vi en template under udvikling til), hver gang der er godkendt en pull-request og ny, testet kode merges in i hoved branchen. På den måde eleveres udbredelses potentialet for modulerne, istedet for at begrænse anvendelse til publikum der kender til en specifikt udviklings-syntax eller metodik. En PoC på en sådan template ligger OS2Lab organisationen, der er til hurtige prototyper, tutorials, spirende samarbejds projekter m.m. https://github.com/OS2lab/dev-polyglot-microservices
