# Mermaid

Mermaid is a JavaScript based **diagramming and charting tool** that uses **Markdown-inspired text definitions** and a renderer **to create** and modify complex **diagrams**:

- Flowchart
- Sequence diagram
- Class diagram
- State diagram
- Entity relationship diagram
- User journey
- Gantt diagram
- Pie chart
- Quadrant chart
- Requirement diagram
- Gitgraph diagram
- C4 diagram
- Mindmap
- Timeline
- ZenUML
- etc.

## Examples

### Sequence diagram

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
 ```
 
 ### Class diagram
 
 ```mermaid
classDiagram
  Class01 <|-- AveryLongClass : Cool
  <<interface>> Class01
  Class03 *-- Class04
  Class05 o-- Class06
  Class07 .. Class08
  Class09 --> C2 : Where am i?
  Class09 --* C3
  Class09 --|> Class07
  Class07 : equals()
  Class07 : Object[] elementData
  Class01 : size()
  Class01 : int chimp
  Class01 : int gorilla
  Class08 <--> C2: Cool label
  class Class10 {
    <<service>>
    int id
    size()
  }
 ```
 
 ### Mindmap
 
 ```mermaid
 mindmap
    Mermaid.js Mind Map Article
        Basic Mind Map
            Indentation
        Shapes
            Default
            id[Square]
            id(Rounded)
            id((Circle))
            id))Bang((
            id)Cloud(
            id{{Hexagon}}
        Icons
            Font Awesome
            Other Icons
```
