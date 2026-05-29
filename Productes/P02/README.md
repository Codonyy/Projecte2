
# P02: Afegint la documentació de seguretat al repositori

## Breu descripció

L’objectiu d’aquesta activitat és organitzar i centralitzar tota la documentació tècnica del projecte dins d’un repositori GitHub utilitzant format Markdown.

Aquesta metodologia evita problemes de:

```text
Data Silos
```

i permet mantenir tota la informació:

* Accessible
* Versionada
* Organitzada
* Compartida entre membres de l’equip

---

# Objectius de l’activitat

* Crear un repositori GitHub anomenat:

```text
Projecte2
```

* Documentar correctament les activitats.
* Utilitzar Markdown de forma professional.
* Organitzar captures i recursos multimèdia.
* Facilitar la navegació entre fitxers del projecte.

---

# Estructura del repositori

L’estructura mínima del projecte és la següent:

```text
Projecte2/
│
├── README.md
│
├── T02/
│   ├── README.md
│   ├── solucio.md
│   └── img/
│
└── T03/
    ├── README.md
    ├── solucio.md
    └── img/
```

---

# README principal

El fitxer:

```text
README.md
```

ha de presentar el projecte de manera visual i clara.

Pot incloure:

* Descripció del projecte
* Índex de tasques
* Tecnologies utilitzades
* Enllaços interns
* Captures de pantalla
* Badges o icones Markdown

---

# Carpetes de tasques

## Carpeta T02

Conté la documentació relacionada amb:

```text
Creació i desplegament de la web corporativa
```

Fitxers necessaris:

```text
T02/
├── README.md
├── solucio.md
└── img/
```

El fitxer:

```text
README.md
```

ha d’explicar:

* Objectiu de l’activitat
* Contingut de la carpeta
* Enllaç directe a:

```text
solucio.md
```

Exemple d’hipervincle:

```markdown
[Veure la solució](./solucio.md)
```

---

## Carpeta T03

Conté la documentació relacionada amb:

```text
Servidor de fitxers
```

Fitxers necessaris:

```text
T03/
├── README.md
├── solucio.md
└── img/
```

El README també ha d’incloure:

* Explicació de la tasca
* Contingut de la carpeta
* Enllaç directe al document tècnic

---

# Carpeta img

Cada tasca disposa d’una carpeta:

```text
img
```

on s’emmagatzemen:

* Captures de pantalla
* Evidències
* Diagrames
* Configuracions

Requisits:

* Format:

```text
PNG
```

* Mida optimitzada
* Nom descriptiu dels fitxers

Exemple:

```text
gpo-configuracio.png
```

---

# Documentació de la solució

Cada tasca inclou un fitxer:

```text
solucio.md
```

Aquest document conté:

* Explicació tècnica
* Passos realitzats
* Configuracions
* Comandes
* Resultats
* Captures de pantalla

---

# Inserció d’imatges en Markdown

Exemple correcte:

```markdown
![Configuració de permisos NTFS](./img/permisos-ntfs.png)
```

La descripció alternativa és obligatòria per:

* Accessibilitat
* Bones pràctiques
* Compatibilitat

---

# Tecnologies utilitzades

## Eines

* Git
* GitHub
* Markdown

## Sistemes

* Windows Server
* Ubuntu Server

## Altres

* Visual Studio Code
* GitHub Pages

---

# Resultat final

El projecte permet:

* Centralitzar documentació tècnica
* Facilitar el treball col·laboratiu
* Aplicar control de versions
* Mantenir una estructura professional
* Crear un repositori escalable i ordenat

---

# Conclusions

La utilització de GitHub i Markdown com a plataforma de documentació tècnica aporta:

* Organització
* Traçabilitat
* Professionalitat
* Facilitat de manteniment

Aquest sistema és habitual dins entorns professionals IT i DevOps.
