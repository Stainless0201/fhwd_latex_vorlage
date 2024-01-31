# Vorlage einer Wissenschaftlichen Arbeit für die FHDW Paderborn in LaTeX

Dieses Repository wird genutzt um eine Wissenschaftliche Arbeit für die Universität
FHDW in Paderborn zu schreiben. Dies ist ein persönliches Repo, erklärt wird hier wie
ich es nutze. Verteile aber gerne mein Template.

## Requirements
- Unix based system (i prefer debian)
- LaTex installed (`sudo apt install texlive-full`)
- Bibliothek editor (`https://www.jabref.org`)


## First Steps
- `Thesis.tex` Zeile 7-14 anpassen 
- Add `Signature.jpg` in root directory

## Build
- Just use `bash buildToPDF.sh` to generate `Thesis.pdf` in current dir
    - Notes
        - it also creates `Quellen.zip` / compressed folder `quellen`
        - removes generated files
        - creates `commit` with current date