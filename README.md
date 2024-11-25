## Desafio Titanic

### Criando ambiente virtual (com CMD)

```cmd
> conda create -n <env_name> python=3.9
```

* Feche e reabra o CMD para inicializar o ambiente: `conda activate <env_name>`

### Instalando libs

```cmd
> conda install numpy pandas matplotlib seaborn jupyter jupyterlab
```

### Entrando no Jupyter pelo CMD

```cmd
> jupyter lab
```

### Instalando dependências

```cmd
> conda env update --file <file_dependencies>.yml
```
