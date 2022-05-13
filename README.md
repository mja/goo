# Gene Ontology relationship networks

Transform [Gene Ontology](http://geneontology.org/docs/download-ontology/) terms and relationships into a network graph for inspection, visualisation, and hypothesis generation.

![](GOO.png)

_GO terms rendered with [Gephi](https://gephi.org)_

Making the above figure:

1. Run code in [geneongology.ipynb](geneontology.ipynb)
2. Notebook produces `go.terms.csv` node file and `go.relationships.csv` edges file.
3. Open Gephi and "Import spreadsheet...", select `go.relationships.csv` and import and "Edges table"
4. Import `go.terms.csv` as a "Nodes table" and after finishing the import, select "Append to workspace"
5. For coloring, select Nodes > Partition > namespace and Edges > Partition > relationship
6. Select Layout: "Force Atlas 2"
7. In Preview, set the background color to `#1F1F1F`.