
# Santander-Java-DIO
 📌 Projeto Final do Bootcamp Santander Java+Angular 2023
<br>

## Diagrama de Classes

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
<br>

# Linguagens
| Java <br>
| Javascript <br>
| Typescript <br>
| Angular <br>

# Frameworks 
| Intelligj <br>
| Elipse <br>
| Sprong Boot <br>


# 📝Entregas 
🔸Protoripo Entrega Final | [Figma] (https://www.figma.com/file/qSqLVuNnroa3ntDRBDAk7H/School-Music?type=design&mode=design&t=6ycBDCzkV9S7aoEy-0)<br>
🔸Caderno de Estudos | [Notion] (https://www.notion.so/debora-dev/Caderno-de-Estudos-52af39a2f5984bf980f1252135c8650f)<br>
🔸Pokedex | (https://github.com/Lolisdu/js-developer-pokedex)



