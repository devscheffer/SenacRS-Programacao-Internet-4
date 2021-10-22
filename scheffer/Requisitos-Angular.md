
# Especificação do Trabalho 2: Angular

## Requisitos

Data de entrega e apresentação: 2021-12-02

Este trabalho consiste no desenvolvimento de uma aplicação Web Single Page Application acessando os Web Services RESTful do Trabalho 1 ou trabalhando com Serverless (ex: Firebase). O objetivo deste trabalho é permitir os alunos aplicarem os conceitos, técnicas e funcionalidades de um framework front-end (no nosso caso, Angular). Nesse trabalho, a ideia é apresentar a aplicação funcional (aplicação front-end acessando o back-end e/ou serverless).

Instruções gerais:

A proposta desse trabalho é dar continuidade ao trabalho anterior, desenvolvendo uma aplicação front-end, a partir de um framework, que acesse os serviços Web realizados no primeiro trabalho e/ou trabalhe com a arquitetura Serverless. Ou seja, no final desse trabalho, o aluno deve apresentar uma aplicação SPA (Single Page Application), aplicando o uso corretamente do framework front-end e manipulando os dados dos serviços Web do Trabalho 1 ou de uma arquitetura Serverless (veremos adiante).

O tema ou domínio da aplicação a ser desenvolvida pelo aluno é opcional, mas deve relacionar pelo menos as seguintes funcionalidades:

    2 CRUDs;
    1 funcionalidade de filtro ou busca;
    1 funcionalidade de negócio;
    1 funcionalidade que tenha relacionamento com duas entidades (pode ser um CRUD ou a própria funcionalidade de negócio);
    Navegação entre telas (modelo SPA);
    Login e tratamento de segurança com Token (JWT).

A aplicação desenvolvida deverá contemplar alguns assuntos vistos em aula. Assim, a avaliação será baseada de acordo com as funcionalidades a serem desenvolvidas e com os conceitos de Angular vistos em aula empregados no desenvolvimento dessa aplicação.

Os alunos poderão optar em desenvolver a aplicação utilizando as seguintes tecnologias: Angular, Vue.js, React e Angular.js. No entanto, conforme visto anteriormente, deve-se trabalhar com os principais conceitos vistos em aula: componentes, data-binding, diretivas, injeção de dependência, filtros e modularização da aplicação.

Outros frameworks e bibliotecas integrados à tecnologia utilizada podem (e são recomendados) a serem empregados no trabalho, tais como Bootstrap, ng-bootstrap MaterializeCSS, Angular Material, PrimeNG, etc.

Avaliação

O conceito desse trabalho será baseado de acordo com as funcionalidades realizadas no trabalho e com os conceitos de Angular empregados no trabalho. Abaixo segue a relação de conceitos e features a serem realizadas no trabalho:

Conceito C (acessando Web Services do Trabalho 1 OU arquitetura Serverless):

    Apresentação de forma clara (para o professor);
    CRUDs completos (pelo menos um por aluno) na aplicação com utilização de tabela e formulário;
    Uma funcionalidade de filtro ou busca que evidencie o uso de Pipes;

Conceito B (acessando Web Services do Trabalho 1 OU arquitetura Serverless):

    Realizar as tarefas para alcançar o conceito C;
    Realizar uma funcionalidade de negócio (ou CRUD) que manipule duas entidades simultaneamente na aplicação como um todo;
    Utilização de Login, guardando o Token em LocalStorage e protegendo as rotas utilizando RouteGuard;
    Utilização dos conceitos do Angular de maneira adequada (componentes, diretivas, rotas, etc);
    Utilização de um sistema de controle de versão (ex: git) e de um ambiente de colaboração e gerenciamento de código baseado nesse controle de versão (ex: github, bitbucket). Caso o trabalho seja em dupla, a colaboração deve estar evidenciada;
    Interface Web adequada e responsiva (sugere-se utilizar Bootstrap ou frameworks semelhantes);

Conceito A (acessando Web Services do Trabalho 1 E arquitetura Serverless):

    Aplicação completa, realizando todas as funcionalidades do conceito B com regras de negócio aplicadas corretamente;
    Utilização de Web Services do Trabalho 1 E de Arquitetura Serverless para o back-end;
    Validações de campos e na submissão dos dados via formulário;
    Implantar a aplicação completa em uma plataforma em nuvem: Heroku, OpenShift, DigitalOcean, entre outros.

Apresentação e Entrega:

O trabalho deverá ser realizado individualmente. Os alunos deverão estar presentes em aula para apresentar o trabalho. A entrega deverá ser realizada pelo Blackboard da disciplina, anexando os projetos (front-end e back-end) em um arquivo zipado (zip), contendo o código fonte, o banco e todas as bibliotecas extras utilizadas (no package.json). Caso o grupo tenha utilizado o Github, deverá relacionar o link como comentário na entrega. Caso o grupo tenha implantado a aplicação, relacionar também o link da aplicação implantada no servidor.


