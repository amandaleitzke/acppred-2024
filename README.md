# acppred

By amanda fonseca leitzke

anticancer peptide prediction software

## Setup

Run the following command to install the acppred program (mamba is required)

```
$ make setup
```

-`Makefile`: arquivo que lista os `comandos` a serem executados pelo programa `make`.

-`environment.yml`: arquivo que lista as `dependências` que precisam ser instaladas pelo programa `Mamba`.

-`requirements.txt`: arquivo que lista as `bibliotecas` Python que precisam ser instaladas pelo programa `Pip`.

# Atividade final

# O que é a ferramenta conda, e qual a sua utilidade no desenvolvimento de programas em Python?
A ferramenta conda é uma ferramenta utilizada para criação de “ambientes virtuais”. Permite a instalação de interpretadores, compiladores e bibliotecas a partir de arquivos de configurações. Além disso, permite instalar, configurar e gerenciar pacotes para projetos em Python. Como a conda permite criar ambientes virtuais isolados, isso se torna extremamente útil ao trabalhar em projetos com diferentes versões de pacotes ou dependências, pois garante que cada projeto tenha seu próprio ambiente Python independente, evitando conflitos e problemas de compatibilidade.

# Como funciona a ferramenta ACPred? Qual a sua finalidade?
O ACPred foi desenvolvido a partir da utilização de diferentes características de peptídeos e dois poderosos algoritmos de aprendizado de máquina, incluindo Random Forest (RF) e Support Vector Machine (SVM). A partir disso, foram obtidos insights sobre o mecanismo de ação de peptídeos anticâncer por meio dos recursos interpretáveis importantes identificados e da análise aprofundada subsequente referente às propriedades biofísicas e bioquímicas subjacentes das atividades anticâncer dos peptídeos. Com isso, a finalidade da ferramenta ACPred é a predição de peptídeos anticâncer.

# O que são aplicações CLI? Quais os comandos e opções (argumentos) criadas para a ferramenta desenvolvidas no projeto?
Uma interface de linha de comando (CLI) é um mecanismo de software utilizado para interagir com o sistema operacional usando o teclado. É uma interface baseada em texto na qual pode-se inserir comandos que interagem com o sistema operacional de um computador.

Dentre os comandos criados pode-se citar:

- ls: Lista o sistema de diretórios (pastas).
- cd pathname: Altera o diretório (pasta) no sistema de arquivos.
- cd ...: Move um nível acima (uma pasta) no sistema de arquivos.
- mkdir: Cria um novo diretório (pasta).
  
Alguns comandos utilizados para passar os dados do repositório para o github:

- git commit: que abrirá o editor de texto padrão; 
- git checkout main: mudar para a ramificação principal do repositório;
- git add .: adicionar todos os arquivos que modificou em um determinado diretório;
- git push: para enviar as alterações para a ramificação atual do seu repositório bifurcado;
  
Após a utilização desses comandos, realiza-se uma pull request para o repositório original no github.
O módulo utilizado para ler os argumentos da linha de comando do Python na disciplina foi o argparse, o qual facilita a criação de interfaces de linha de comando fáceis de usar. Algumas funções utilizadas dentro do argumento de cada arquivo (models.py, predict.py, preprocess.py, server.py e train.py) import, if, print, else, elif, dentre outros.

# O que é back-end e front-end no contexto de aplicação web?
O back-end é a camada oculta, ou seja, a parte que lida com a lógica dos negócios e com o processamento dos dados. É ele quem gerencia as informações, realiza cálculos, promove autenticações de segurança e integra um software ou aplicativo com outros sistemas. Geralmente, o back-end é desenvolvido por meio de linguagens de programação como Java, Python, Ruby, entre outras. O front-end é uma camada de aplicação responsável por apresentar a interface ao usuário. Ou seja, a parte visual e interativa. Para isso, é composto por variadas tecnologias como HTML, CSS e JavaScript - recursos utilizados na criação de páginas web interativas, aplicativos móveis e outros sistemas que podem ser acessados por meio de um navegador web ou dispositivo móvel.

# O que são testes unitários? Qual a sua importância no desenvolvimento de software?
São testes utilizados para avaliar o comportamento de componentes da aplicação, testando não o programa inteiro, mas cada módulo separadamente. Sua importância se dá pois é possível testar a funcionalidade de diferentes programas e assim garantir que cada módulo esteja correto.

