<div id="top"></div>

## Dimension reduction, Clustering and Multiclasses classification using Spark MLlib

Muitos projetos de Big Data em uso em grandes companhias ainda usam bibliotecas que não estão preparadas para serem executadas em processamento distribuído, como por exemplo, scikit klearn.

Esse projeto é apenas para apoiar profissionais que estão fazendo a implementação da biblioteca MLlib usando PySpark.

**Modelagens realizadas:**

Foram as seguintes bibliotecas Spark:

* Redução de dimensionalidade usando [PCA](https://www.postgresql.org/)
* Clusterização usando [KMeans](https://debezium.io/)
* Classificação usando [Random Forest](https://kafka.apache.org/)

<p align="right">(<a href="#top">voltar ao início</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Aqui um exemplo de como deixar o ambiente operacional para realizar alguns testes do ambiente de CDC.

### Pré-requisitos

Todas as operações serão realizadas em plataformas instalada em um container Docker. Portanto, precisamos que o docker esteja instalado corretamente.

[Aqui está o link da documentação do Docker](https://docs.docker.com/compose/install/) para realizar a instalação.

Para testar se a instalação está correta, pode ser usado o comando `docker-compose --version`. Você deve ver um resultado similar ao apresentado abaixo.

```sh
   $ docker-compose --version
   docker-compose version 1.29.2, build 1110ad01
   ```


### Instalalação

1. Clone o repositório
   ```sh
   git clone https://github.com/walmeidadf/spark-mllib.git
   ```
2. Construa e execute o aplicativo com o comando do Docker Compose na pasta do projeto.
   ```sh
   cd cdc
   docker-compose up
   ```

<p align="right">(<a href="#top">voltar ao início</a>)</p>


<!-- USAGE EXAMPLES -->
## Uso

Para acessar o notenook vc pode acessar a porta redirecionada pelo docer, no meu exemplo a porta `8080`. Assim o notebook pode ser acessado usando o link  `http://localhost:8080`.

Na pasta `work` existem alguns notebook que dão alguns exemplos de como rodar o modelo..

<!-- ROADMAP -->
## Roadmap

- [ ] Adicionar as referências
- [ ] Configurar o container do Jupyter para remover a senha de acesso 
- [ ] Fazer a documentação em inglês.

<p align="right">(<a href="#top">voltar ao início</a>)</p>


<!-- CONTACT -->
## Contato

Wesley Almeida - [@walmeidadf](https://twitter.com/your_username) - walmeida@gmail.com

Link do Projeto: [https://github.com/walmeidadf/spark-mllib](https://github.com/walmeidadf/spark-mllib)

<p align="right">(<a href="#top">voltar ao início</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Referências

Algumas das páginas de documentação, artigos e posts que me ajudaram a desenvolver esse projeto:

* a definir

<p align="right">(<a href="#top">voltar ao início</a>)</p>
