# Santander-Java-DIO
Projeto Final do Bootcamp Santander Java+Angular 2023
<br>

Diagrama de Classes

```mermaid

  classDiagram
  class Aluno {
    - Nome: string
    - Matricula: string
    - Features: Feature[]
    - News: News[]
  }

  class Feature {
    - icons: string
    - descriptions: string
  }

  class News {
    - icons: string
    - descriptions: string
  }

  Aluno "1" *--  "1"Feature
  Aluno "1" *-- "n" News

```
