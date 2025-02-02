---
title: Programação com Objetos
path: /po
type: topLevelPage
---

# Programação com Objetos

> Esta cadeira tem como objetivo dar a conhecer o paradigma de programação com objectos, as suas vantagens,
> inconvenientes e limitações; assim como o paradigma dos padrões de desenho, tanto no desenvolvimento, como na refactorização de aplicações.

## Recursos Adicionais

- [Wiki do Prof. David Matos](https://web.tecnico.ulisboa.pt/~david.matos/w/pt/index.php/Programa%C3%A7%C3%A3o_com_Objectos)
- [MermaidJS Live Editor](https://mermaid.live/) - Editor de gráficos UML
- [Umbrello UML Modeller](https://umbrello.kde.org/) - Editor de gráficos UML
- [Página da Cadeira - Fénix](https://fenix.tecnico.ulisboa.pt/disciplinas/Fis4/2021-2022/1-semestre)

```mermaid
classDiagram
class Student {
    +age: int
    +jumpOffTower(northTower: Tower): void
}

class Course {
    +name: String
    +students: List~Students~
    +giveMaxGradeToAllStudents(): void
}

Course --> Student

```
