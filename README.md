# PythonAnaconda_Devcontainer
This will create a remote container using docker for python development using Anaconda3 as base image.

Create docker container with:

  `docker run -i -t -p 8888:8888 -v "%CD%":/home --name anaconda3_temp continuumio/anaconda3:2020.11`
  
  (%CD% same as current directory)

## An example on how to set up this environment
there are several pages/videos that gives examples on this. As an example:
See [Gina Sprints YouTube video](https://www.youtube.com/watch?v=cK7vgjOntqM) on **How to Run Python 3 and Jupyter Lab using an Anaconda Docker Container and VS Code**

# Attach VSCode remote container
Use in vscode by attaching to running remote container by `F1`and select **Attach to running container......**

