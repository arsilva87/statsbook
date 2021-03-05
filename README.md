<img align="right" src = "https://raw.githubusercontent.com/arsilva87/statsbook/main/figs/figura_thumbnail.png" width="25%" height="25%">

# Estatística Decodificada

Aqui você encontrará materiais suplementares como scripts do R e conjuntos de dados utilizados no livro, todos disponíveis para consulta e download.

## Conjuntos de dados experimentais
Para ler no R os arquivos a seguir, use as funções read.table(), read.csv() ou read.csv2(). O arquivo batata.xlsx contém os mesmos dados do batata.txt; 
o objetivo é exemplificar a leitura de arquivos .xlsx com o a função read_excel() do pacote readxl. Os nomes dos arquivos a seguir contém os links para leitura 
direta pelo R usando as funções mencionadas [com excessão da read_excel()].

- [batata.txt](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/batata.txt)
- [batata.xlsx](https://github.com/arsilva87/statsbook/raw/main/datasets/batata.xlsx)
- [pareada.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/pareada.csv)
- [camadassolo.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/camadassolo.csv)
- [milho.txt](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/milho.txt)
- [dadosboot.txt](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/dadosboot.txt)
- [pimenta.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/pimenta.csv)
- [ancova.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/ancova.csv)
- [vinhaca.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/vinhaca.csv)
- [gergelim2ad.txt](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/gergelim2ad.txt)
- [splitplot.txt](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/splitplot.txt)
- [azuki.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/azuki.csv)
- [gergelim1ad.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/gergelim1ad.csv)
- [conjunta.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/conjunta.csv)
- [TA.csv](https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/TA.csv)

Por exemplo:
```r
> batata <- read.table("https://raw.githubusercontent.com/arsilva87/statsbook/main/datasets/batata.txt", 
     header = TRUE, colClasses = c("factor", "factor", "numeric"))
> str(batata)
'data.frame':   12 obs. of  3 variables:
 $ cultivar: Factor w/ 4 levels "1","2","3","4": 1 1 1 2 2 2 3 3 3 4 ...
 $ bloco   : Factor w/ 3 levels "1","2","3": 1 2 3 1 2 3 1 2 3 1 ...
 $ prod    : num  50.9 50.6 51.2 49.1 49.3 49.9 49.9 49.8 49.5 49.2 ...
```

## Jupyter notebooks [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/arsilva87/statsbook/main?filepath=Jupyter_notebooks%2FScript_Cap03.ipynb) 

Execute em nuvem todos os comandos apresentados nos capítulos com um Jupyter notebook com kernel R pronto para uso. 

## Contato
anderson.silva@ifgoiano.edu.br
