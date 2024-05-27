
Ploomber is the fastest way to build data pipelines ⚡️


 Use your favorite editor (Jupyter, VSCode, PyCharm) to develop interactively and deploy ☁️ without code changes (Kubernetes, Airflow, AWS Batch, and SLURM).


Do you have legacy notebooks? Refactor them into modular pipelines with a single command.


Overall comparison
![Screenshot from 2024-05-23 19-56-47](https://github.com/surenoobster/docs_of_ploomber/assets/154669584/e7ee668f-252b-4280-9339-56b659600779)



install: Install dependencies

nb (short for notebook): Manage notebooks and scripts

report: Generate a pipeline report

scaffold: Create a new project

status: Pipeline status summary

task: Execute a single task

if you want to create a project from starting pipeline 
ploomber 

```sh
ploomber scaffold --empty
```

enter project name 

then edit pipeline.yaml as per your requirement

then do 

```sh
ploomber build
```

# This pipeline was automatically generated

## Setup

```sh
pip install -r requirements.txt
```

## Usage

List tasks:

```sh
ploomber status
```

Execute:

```sh
ploomber build
```

Plot:

```sh
ploomber plot
```


for SQL 

https://docs.ploomber.io/en/latest/use-cases/sql.html

for debugging

https://docs.ploomber.io/en/latest/user-guide/debugging.html

for jupyter integration

https://docs.ploomber.io/en/latest/user-guide/jupyter.html

for other concepts refer 

https://docs.ploomber.io/en/latest/





Soorgeon is a command-line tool designed to refactor Jupyter Notebooks into modular Ploomber pipelines.

It automates the process of converting notebook cells into task-based pipelines, which are more maintainable and scalable.




# install packages
```sh
pip install soorgeon ploomber
```

# get the example's code

```sh
git clone https://github.com/ploomber/soorgeon
```

# refactor the sample ML notebook

``` sh
cd examples/machine-learning
soorgeon refactor nb.ipynb
```
# run the auto-generated Ploomber pipeline
```sh
ploomber build
```

#overall 
```sh
soorgeon refactor path/to/nb.ipynb
```


ref link
https://github.com/ploomber/soorgeon/blob/main/doc/guide.md




ref link for implemented soorgeon
https://github.com/surenoobster/soorgeon_demo/tree/master








## Resources

* [Ploomber documentation](https://docs.ploomber.io)
