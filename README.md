<div align="center">
  <img src="https://user-images.githubusercontent.com/6454510/178803369-dc28461d-dccf-4b72-9b56-95d301dad1a6.png" width="400" alt="Euridice Logo" />
</div>

Euridice is a framework designed to provide the tools for intuitive data
quality improvement through the process of data cleansing. Built for a
thesis project at Leiden University, the software was developed to clean
data used in data science pipelines through interactive and intuitive
workflows. It should be used in the context of a consultant assisting a
user of the to-be-cleaned data with building workflows to clean data.

The framework consists of multiple core applications / services:

* Lens: React-based Workflow Editor
* Lake: Dask-wrapping DataFrame storage
* Flow: Workflow Templating & Rendering `(DAG -> BFS -> IPython)`
* Engine: GraphQL API mapping for JupyterLab Server

Euridice features a complete REST API as well as a GraphQL API 
for easily developing and integrating with other tools and systems.

Euridice runs as multiple APIs in the [Django](https://www.djangoproject.com/)
Python framework with a [PostgreSQL](https://www.postgresql.org/) database.
