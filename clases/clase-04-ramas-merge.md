
En `clases/clase-04-ramas-merge.md` poné:

```markdown
# Clase 4 - Ramas, git mv, merge y reorganización del repositorio

## Objetivo de la clase

Aprender a trabajar en una rama independiente para realizar una mejora sin afectar directamente la rama principal `main`.

## Conceptos trabajados

- Rama principal `main`.
- Rama de mejora.
- Trabajo por funcionalidad.
- Reorganización de archivos.
- Uso de `git mv`.
- Merge.
- Fast-forward.
- Sincronización con GitHub.
- `git pull --rebase`.

## Comandos utilizados

```bash
git checkout -b mejora/estructura-repo
mkdir clases recursos reflexiones
git mv resumen.txt clases/clase-01-git-local.md
git mv glosario-git.txt recursos/glosario-git.md
git mv objetivos.txt reflexiones/objetivos-formacion.md
git mv reflexion-clase-01-git reflexiones/reflexion-clase-01.md
git commit -m "Reorganizar estructura academica del repositorio"
git checkout main
git merge mejora/estructura-repo
git pull --rebase origin main
git push