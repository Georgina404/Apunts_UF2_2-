# Apunts_UF2_2
# Documentació i optimització
### Optimització
#### Hediondez del codi (code smell)
Si es produeix una hediondez, és símptoma de que el codi font possiblement contingui un problema més profund. No es consideren bugs, ja que no són tècnicament incorrectes i tampoc impedeixen que el codi s'executi correctament.

Indica que pot contindre deficiencies en el disseny que pot ralentitzar el desencolupament o augmenten el risc d'errors en el futur.

#### Anàlisi del codi
Hi ha dos tipus possibles:
- Anàlisi dinàmic (unit test)
- Anàlisi estàtic (lint): es realitza mitjançant analitzadors estàtics (linters) o mitjançant llocs webs d'inspecció de codi (Continuous Inspection). Analitzadors linters: lint (C), sonar (Java), JSLint/ESLint (Javascript).
Analitzadors Continuous Inspection: scrutinizer (PHP, Python y Ruby), SonarQube (més de 20 llenguatges).

#### Refactorització
És el procés de reestructurar el codi font, alterant la seva estructura interna sense canviar el seu comportament extern.
- Tècniques:
-- Renombrament de variables
-- Passar codi duplicat a funcions
-- Eliminació de codi inabastable
-- Eliminació de codi redundant
-- Eliminació de codi mort

### Documentació
#### Tipus de documentació
- Documentació de codi
- Documentació tècnica
- Documentació d'usuari

#### Formats de documentació
- HTML (Javadoc)
- Markdown (Gitbook)
- reStructuredText (Readhedocs)
- asciiDoc

### Control de versions
#### Sistemes coneguts
- CVS
- Subversion
- Mercurial
- Git: modern, distribuït, eficient. Llocs que suporten Git: GitHub, Bitbucked, GitLab, Coding
