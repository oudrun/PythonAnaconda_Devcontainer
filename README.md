# PythonAnaconda_Devcontainer
This will create a remote container using docker for python development using Anaconda3 as base image.

Create docker container with:

  `docker run -i -t -p 8888:8888 -v "%CD%":/home --name anaconda3_temp continuumio/anaconda3:2020.11`
  
  (%CD% same as current directory)
  
# Attach VSCode remote container
Use in vscode by attaching to running remote container by `F!`and select **Attach to running container......**

