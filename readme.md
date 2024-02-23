# Desafio Técnico Desenvolvedor SAE +C

Primeiramente, obrigado pelo seu interesse em trabalhar conosco!
Abaixo você encontrará todos as informações necessárias para iniciar o seu teste.

## Avisos antes de começar

-   Crie um repositório no seu GitHub **sem citar nada relacionado a SAE +C**.
-   Faça seus commits no seu repositório.
-   Envie o link do seu repositório para o email **do recrutador responsável**.
-   Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
-   Fique à vontade para perguntar qualquer dúvida aos recrutadores.
-   Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

_Corpo do Email com o link do repositório do desafio_

> Seu Nome
>
> Nome do recrutador
>
> Link do repositório
>
> Link do Linkedin

### Sobre o ambiente da aplicação:

-   Nosso desafio é a construção de uma aplicação Full-Stack, obrigatoriamente você deve implementar uma solução com .NET C#. ;)

-   Você pode, inclusive, no front-end não optar por framework nenhum.

-   Ainda assim, se optar por um framework tente evitar usar muito métodos mágicos ou atalhos já prontos. Sabemos que essas facilidades aumentam a produtividade no dia-a-dia mas aqui queremos ver o **seu** código e a sua forma de resolver problemas.

-   Valorizamos uma boa estrutura criada por você.

## Para o dia da entrevista técnica

Na data marcada pelo recrutador tenha sua aplicação rodando na sua máquina local para execução dos testes e para nos mostrar os pontos desenvolvidos e possíveis questionamentos.
Faremos um code review junto contigo como se você já fosse do nosso time, você poderá explicar o que você pensou, como arquitetou e como pode evoluir o projeto.

## Objetivo:  Gestão Eficiente de Pessoas e Cidades

O objetivo deste teste técnico é avaliar as habilidades do candidato no desenvolvimento de um sistema de cadastro de pessoas, com foco em funcionalidades como registro de dados, validação de informações, consulta de registros, restrições de cadastro, e geração de relatórios.
O candidato será avaliado quanto **à capacidade de seguir as instruções, modelar o sistema de acordo com as especificações fornecidas e implementar funcionalidades essenciais, incluindo validações e manipulação adequada de dados**. A utilização de boas práticas de programação, organização de código, serão consideradas na avaliação.
Requisitos:

## Entidades
> Pessoa:
- ID: Identificador único (integer).
- nome: (varchar, 70 caracteres).
- tipo_pessoa: (varchar , 2 caracteres) (JU=Jurídica, FI=Física).
- Cpf_cnpj: (varchar , 14 caracteres).
- cep: (varchar, 8 caracteres).
- endereco: (varchar, 100 caracteres).
- numero: (integer).
- compl: (varchar, 20 caracteres).
- bairro: (varchar, 50 caracteres).
- data_nascimento_fundacao: (date).
- dataCadastro: (date).
- e-mail: (varchar, 50 caracteres).
- celular: (varchar, 20 caracteres).
- Sit_cadastral: (varchar, 2 caracteres) - A=ativo, I=inativo.
- cidadeID: (integer).

> Cidade 
- ID: Identificador único (integer).
- nome: (varchar , 25 caracteres).
- estadoID: (integer).

> Estado
- ID: Identificador único do estado (integer).
- Nome : (varchar , 25 caracteres).

# Requisitos funcionais 

#### Registro de Pessoas:

- Validar se o CPF/CNPJ é válido conforme o tipo de pessoa.
- Validar e-mail.
- Não permitir cadastrar o mesmo CPF/CNPJ.
- Permitir cadastrar uma cidade caso não esteja na lista.

#### Consulta de Pessoas:
 - Permitir a pesquisa de pessoas por tipo (Todos, Físicas, Jurídicas), cidade e estado.
 - Exibir lista com Id, nome, CPF/CNPJ, tipo de pessoa, cidade, estado, data de cadastro e idade.

#### Relatórios de Clientes:
- Modelo 1: Dados básicos como CPF e telefone.
- Modelo 2: Todos os dados do cadastro.
- Permitir ao usuário escolher entre os dois modelos.

# Avaliação

A correção qualitativa será durante a entrevista e levará em conta os seguintes critérios:

## O que será avaliado e valorizamos

-   Se for para vaga sênior, foque bastante no **desenho de arquitetura**
-   Código limpo e organizado (nomenclatura, etc)
-   Conhecimento de padrões (design patterns, SOLID)
-   Ser consistente e saber argumentar suas escolhas
-   Apresentar soluções que domina
-   Modelagem de Dados
-   Manutenibilidade do Código
-   Tratamento de erros
-   Cuidado com itens de segurança
-   Arquitetura (estruturar o pensamento antes de escrever)
-   Carinho em desacoplar componentes (outras camadas, service, repository)

De acordo com os critérios acima, iremos avaliar seu teste para avançarmos para a entrevista técnica.
Caso não tenha atingido aceitavelmente o que estamos propondo acima, não iremos prosseguir com o processo.

## O que será um Diferencial

-   Uso de Migrations
-   Uso de Design Patterns
-   Documentação
-   Proposta de melhoria na arquitetura

## Materiais úteis

-   https://saeinfo.net.br/quem-somos
-   https://hub.packtpub.com/why-we-need-design-patterns/
-   https://refactoring.guru/
-   http://br.phptherightway.com/
-   https://www.php-fig.org/psr/psr-12/
-   https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing
-   https://github.com/exakat/php-static-analysis-tools
-   https://martinfowler.com/articles/microservices.htm
-   https://docs.guzzlephp.org/en/stable/request-options.html
-   https://www.devmedia.com.br/rest-tutorial/28912