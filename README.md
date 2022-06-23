# Hello MermaidJS


## Integrations
Use markdown language to create different kind of charts in
- README.mds (by default: GitHub, GitLab)
  - IDE: VsCode via plugin: 
- ReactJS via npm package (react-mermaid)
- HTML-files (using Javascript)



## Supported chart-types
- Flowchart
- Sequence diagram
- Gantt diagram
- Class diagram
- Git Graph
- ER diagram (experimental)
- User Journey
- Pie Charts
- Requirement diagram
- Context diagram

## Personal opinion
Advantage instead of create diagrams with e.g. draw.io
- Diagrams as markdown text in repo
- Embed diagrams directly instead of images of the diagram itself
- Creates vector graphics for best scalablity (export as PNG available too)
-

```mermaid
graph TD;
  A[Coding] -->|Code done| B(Run tests)
  B --> C{Tests passing}
  C -->|Yes| E[Laptop]
  C -->|No| B[iPhone]
```

```mermaid
gantt
    title Onboarding
    dateFormat  DD.MM.YYYY
    section Ablauf
    Welcome                  :a1, 30min
    Get familiar with MacOS  :after a1, 1h
    section Installing programs
    communication software     :after a1, 30min
    Dev Tools (GIT)       : 30min
    VSCode + Plugins      : 30min
    another task      : 30min
    another task      : 30min
```

```mermaid 
  journey
    title My random journey
    section Do what I like
      Coding: 7: Me, @PC
      Lorem ipsum: 5: Me
      Dolor set amit: 4: Me, @PC
    section Do what has to be done
      Laboratim: 1: Me
      Finished: 5: Me
```
      


# References:
[GitHub - Mermaid-js](https://mermaid-js.github.io/mermaid/#/)
[NPM react-mermaid](https://www.npmjs.com/package/react-mermaid)