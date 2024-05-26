
Ploomber is the fastest way to build data pipelines ⚡️


 Use your favorite editor (Jupyter, VSCode, PyCharm) to develop interactively and deploy ☁️ without code changes (Kubernetes, Airflow, AWS Batch, and SLURM).


Do you have legacy notebooks? Refactor them into modular pipelines with a single command.


Overall comparison
![Screenshot from 2024-05-23 19-56-47](https://github.com/surenoobster/docs_of_ploomber/assets/154669584/e7ee668f-252b-4280-9339-56b659600779)




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













## Resources

* [Ploomber documentation](https://docs.ploomber.io)
