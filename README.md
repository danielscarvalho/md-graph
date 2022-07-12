# md-graph
Markdown Graph

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
      D-->D;
      F-->F;
      G-->F;
      H-->I;
      J-->I;
      K-->I;
```

```mermaid
flowchart LR

A[Hard] -->|Text| B(Round)
B --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

```mermaid
flowchart LR
    V((WEB<br>View))
    C[[Java WEB API<br>Controller]]
    M[(Database<br>MySQL<br>Model)]
    V<--- JSON --->C
    C<--- SQL --->M
```

Referência:<br>
https://github.com/mermaid-js/mermaid
https://mermaid-js.github.io/mermaid
