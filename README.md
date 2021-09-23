# DevOps Project: Operations - slides

In deze repository vind je de slides die gebruikt wordt in de lessen van de cursus DevOps Project: Operations (3e jaar bachelor toegepaste informatica aan Hogeschool Gent).

De slides zijn te bekijken via <https://hogenttin.github.io/devops-prj-slides/01-kick-off.html>.

## Slides genereren

Om zelf de slides te genereren heb je een Linux (of UN*X) omgeving nodig, met (GNU) make en [Pandoc](https://pandoc.org/).

Haal eerst de branch `gh-pages` (wordt gebruikt om de slides te publiceren via Github Pages) binnen en maak die beschikbaar in de directory `gh-pages`.

```console
git worktree add gh-pages gh-pages
```

Genereer vervolgens de slides a.h.v. de Makefile:

```console
make all
```

Je kan nu de slides bekijken door de .html-bestanden in de `gh-pages` directory te openen in een webbrowser.

## Bijdragen

Bijdragen aan het hier gepubliceerde lesmateriaal zijn van harte welkom! verbeteren van tikfouten, toevoegingen, onduidelijkheden melden, enz. Je kan een Issue of een Pull Request openen.

## Licentie-informatie

Deze syllabus is samengesteld door [Bert Van Vreckem](https://github.com/bertvv/) en valt onder de [Creative Commons Naamsvermelding-GelijkDelen 4.0 Internationale Publieke Licentie](http://creativecommons.org/licenses/by-sa/4.0/).
