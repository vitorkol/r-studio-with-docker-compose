# R Studio with Docker Compose
<div align="center"> <a href="#Sobre">Sobre</a> • <a href="#Tecnologias-e-bibliotecas">Tecnologias e bibliotecas</a> • <a href="#Dataset">Dataset</a> </div>
  

# Sobre
R Studio with Docker Compose foi criando tendo em vista ter um ambiente estável para estudos e análises de dados com a linguagem de programação R, este repositório tende auxiliar a novos estudantes quanto ao uso da ferramenta R Studio.
Nos últimos anos a análise de dados tem ganhado muita ênfase, e diante deste cenário, diversos setores afim de entender melhor seus indicadores, demandam constantemente este tipo de análise, e, o R é uma linguagem de programação que permite o analista gerar relatórios, cruzar dados para tomada de decisão, gerar dashboards operacionais e/ou estratégicos.

# Motivação
Esse projeto foi desenvolvido com o objetivo de auxíliar estudantes que não possuem equipamentos apropriado para desenvolvimento e analises de dados, permitindo-os estudar sem a necessidade de instalar diversos programas e bibliotecas em suas máquinas; rodando o R Studio diretamente do navegador.

1. Faça Download do projeto;
2. Caso não tenha o Docker instalado, baixe- o aqui [Docker Install](https://docs.docker.com/engine/install/);
3. Descompacte o projeto em sua pasta de preferência;
4. Abra o Terminal utilizado em seu sistema operacional;
5. Execute o comando: ``` docker-compose up -d ``` para carregar o container contendo a imagem do R Studio;
6. Em seu navegador digite: http://localhost:8787;
7. Execute o comando: ``` docker-compose down ``` para parar de rodar o container contendo a imagem do R Studio.

# Tecnologias e bibliotecas
Linguagem de programação:</br>
[R 3.5.3](https://www.r-project.org/)

Bibliotecas utilizadas:

1. [readr](#) - Utilizada para realizar leitura de arquivos .csv;
2. [foreing](#) -Utilizada para realizar leitura de arquivos .dbf;
3. [readxl](#) - Utilizada para realizar leitura de arquivos .xlsx;
4. [H2O](http://h2o-release.s3.amazonaws.com/h2o/rel-yates/1/R) - Utilizada para renderizar R Studio no Navegador;
5. [tidyverse](https://www.tidyverse.org/packages/) - Utilizada para manipular e gerar gráficos estatísticos;
6. [plotly](#) - Utilizada para criação de gráficos dinâmicos;

IDE:

Para esse projeto, optei por utilizar o aplicativo web Jupyter Notebook com Colab Google:</br>
[R Studio 1.2.1](https://www.rstudio.com/)</br>


# Dataset
Utilizamos o dataset de exemplos disponibilizado em:</br>
[Dataset](#) → Para fins didáticos, foram utilizados 3 arquivos os mesmos se encontram disponível na estrutura do projeto.
