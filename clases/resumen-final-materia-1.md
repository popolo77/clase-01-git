# Resumen final - Materia 1: Git, GitHub, Terminal e IA Profesional

## Introducción

En la Materia 1 del Programa Complementario de Formación Frontend se trabajaron las bases profesionales de Git, GitHub, terminal, documentación, trazabilidad académica y uso responsable de inteligencia artificial.

El objetivo de la materia no fue memorizar comandos, sino comprender cómo se organiza un proyecto real, cómo se registran los avances y cómo se construye evidencia profesional en GitHub.

---

## ¿Qué problema resuelve Git?

Git permite controlar versiones de un proyecto.

Cuando se trabaja sin Git, es común guardar archivos con nombres como:

* proyecto-final;
* proyecto-final-2;
* proyecto-ahora-si;
* proyecto-no-tocar.

Ese método es desordenado y poco profesional.

Con Git, cada avance importante puede guardarse mediante commits. De esa manera, el proyecto tiene una historia clara y se puede revisar qué cambió, cuándo cambió y por qué cambió.

---

## ¿Qué es GitHub?

GitHub es una plataforma online donde se alojan repositorios Git.

Git trabaja principalmente en la computadora local. GitHub permite llevar ese repositorio a la nube, compartirlo, colaborar, crear Issues, trabajar con Pull Requests y mostrar evidencia profesional del aprendizaje.

En esta materia, GitHub se usó como repositorio académico y como herramienta de organización del trabajo.

---

## Flujo básico de Git

El flujo inicial aprendido fue:

```text
Working Directory → Staging Area → Repository
```

Esto significa:

1. Primero se modifican archivos en la carpeta del proyecto.
2. Luego se preparan los cambios con `git add`.
3. Finalmente se guardan en el historial con `git commit`.

Los comandos principales fueron:

```bash
git status
git add
git commit
git log --oneline
```

---

## Revisión de cambios

Antes de guardar cambios, se aprendió a revisarlos con:

```bash
git diff
```

Este comando muestra cambios que todavía no fueron preparados.

También se utilizó:

```bash
git diff --staged
```

Este comando muestra los cambios que ya están preparados para el próximo commit.

Esto ayuda a evitar commits desordenados o con archivos equivocados.

---

## Trabajo con ramas

Una rama es una línea de trabajo independiente dentro del repositorio.

La rama principal es `main` y representa la versión estable del proyecto.

Cuando se necesita hacer una mejora, conviene crear una rama aparte para trabajar sin afectar directamente a `main`.

Ejemplo:

```bash
git checkout -b mejora/estructura-repo
```

En esta materia se usaron ramas para reorganizar el repositorio y para trabajar tareas específicas vinculadas a Issues.

---

## GitHub Issues

Un Issue es una tarea, mejora o problema registrado dentro de GitHub.

En esta materia, los Issues se usaron para planificar el Trabajo Integrador.

Ejemplos:

* Completar glosario de comandos Git.
* Crear resumen final de la Materia 1.
* Preparar defensa oral del integrador.
* Revisar README final del repositorio.

El Issue permite saber qué hay que hacer, por qué se hace y cuándo se considera terminado.

---

## Pull Requests y Merge

Un Pull Request es una solicitud para integrar cambios desde una rama hacia otra, normalmente hacia `main`.

Permite revisar qué archivos cambiaron antes de incorporar esos cambios a la rama principal.

El merge es la acción final de integrar esos cambios.

El flujo profesional trabajado fue:

```text
Issue → rama → cambios → commit → push → Pull Request → merge
```

Este flujo permite trabajar con orden, trazabilidad y criterio profesional.

---

## Uso profesional y ético de IA

También se creó una política personal de uso de IA.

La regla principal de la materia es:

> Todo código, comando, explicación o decisión técnica incorporada al proyecto debe poder ser comprendida, modificada y defendida oralmente.

La IA puede usarse como apoyo para estudiar, documentar, revisar errores o mejorar explicaciones, pero no debe reemplazar la comprensión personal.

---

## Evidencias generadas

Durante la materia se generaron evidencias concretas:

* repositorio en GitHub;
* README profesional;
* carpeta de clases;
* glosario de comandos;
* reflexiones personales;
* política de uso de IA;
* bitácora técnica;
* Issues;
* ramas;
* Pull Requests;
* merges;
* commits claros.

---

## Conclusión

La Materia 1 permitió construir una base profesional para trabajar con proyectos de desarrollo.

El aprendizaje principal fue entender que programar no es solamente escribir código. También implica organizar el trabajo, documentar avances, controlar versiones, comunicar decisiones y dejar evidencia clara del proceso.

Este repositorio demuestra el inicio de una metodología que se aplicará en todas las materias del programa: cada materia tendrá su propio repositorio actualizado en GitHub, con documentación, práctica, trazabilidad e integrador final.
