# My Notebook

A collection of personal notebooks

## Start container

```
docker run --restart unless-stopped --name jupyter -p 8888:8888 -v "$PWD":/home/jovyan/work -d jupyter/all-spark-notebook start-notebook.sh --NotebookApp.password='sha1:PASSWORD'
```
