# Experimentos com python

Este git é para armazenamento de aqruivos com dicas de python para manter exemplos para uso futuro.

## Link sites
- [Editor de Markdown online](https://stackedit.io/app#)<br>
- [Conda cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

## Comandos python mais usados nos meus projetos

|Function                                                             |Command                                  |
|---------------------------------------------------------------------|----------------------------------------|
|Make exact copy of an environment                                    |conda create --clone py35 --name py35-2 |
|Get a list of all my environments, active environment is shown with* |conda env list                          |
|List all packages and versions installed in active environment       |conda list                              | 
|Change Jupyter Notebook working directory                             |jupyter notebook --generate-config     | 
|Delete an environment and everything in it          |conda env remove --name bio-env     | 

# GIT

## Comandos GIT mais usados
|Function           | Command |
|-------------------|---------|
| Clonar um projeto | git clone <endereço do projeto> |
| Acionar uma branch | git branch |
| Trazer atualizações | git pull |
| Adicionar novos elementos ao projeto | git add . |
| Commitar modificações | git commit -m "comments" |
| Subir modificações para o git | git push |

## How can you undo the last git add?
|Function                            | Command |
|------------------------------------|---------|
| How can you undo the last git add? | git add -- |

## Undo a commit & redo

| Ação                            | Command | Step |
|------------------------------------|---------|------|
| Commit com problema                | git commit -m "Something terribly misguided" |  # (0: Your Accident) |
| Desfaz o Commit                    | git reset HEAD~             |  # (1) |
| Edita o que precisar              |[ edit files as necessary ]  | # (2)  |
| Adiciona alterações                | git add .                   | # (3)  |
| Comita sobre o anterior com problema | git commit -c ORIG_HEAD     | # (4)  |




