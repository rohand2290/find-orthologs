# find-orthologs
This is a Jupyter Notebook that maps mouse proteins to their human orthologs.

# Objectives
We have accession numbers of mouse proteins. 
Accession numbers need to be found for the human orthologs (equivalents.)
This is in order to import it into STRING using Cytoscape to generate a network based on what pathway or disease the proteins are involved in.


# Usage
You'll need Postgres running locally on your system, as well as Nix. Clone the repo and run `nix develop`. 
You'll also need to create a `.env` file which follows this format:

```
USER=
PASSWORD=
HOST=
PORT=
```

Once that's done, you can run `jupyter lab` or use VS Code with the Jupyter extension to run the notebook.
