## Usage of Webview:
To visualise the graphs in vscode we are going to use the webview-api from the vscode-extension api. This is the most suitable and costumisable tool for our project. 
The other api's do not provide the needed functionality.

## Tools for graph visualisation:
We have been looking at a few libraries or tools for our graphs. There are a few options each with their pros and cons:
- D3.js
  - Very complex api, but allows for a lot of costumisation
- Cytoscape
  - Not as complex D3.js, and seems to have simple interaction tools for our edges. Seems to be the best option

## Tentative Tech-stack
- TypeScript (TypeDaddy)
  - VsCode Api
- Python for ArchLens
  - unittest (library for testing)
  - Astroid (parsing Python-projects)
- Cytoscape.js (Graphs)
- Docker (maybe)    

## Current expansion ideas:
 - Dynamically create diagrams
 - Interactive edges (Click edge for info and a ‘jump-to-line’ button)
 - More diagrams (Add UML)
 - Integrate version-control (Select commit to compare with current)
   - Diff-view
 - Export picture of graph
 - 
