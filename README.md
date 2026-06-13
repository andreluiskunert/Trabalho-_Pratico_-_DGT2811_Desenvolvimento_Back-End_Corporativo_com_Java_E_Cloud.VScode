# Trabalho Prático – DGT2811 Desenvolvimento Back-End Corporativo com Java e Cloud

## Autor

André Luis Kunert

## Disciplina

DGT2811 – Desenvolvimento Back-End Corporativo com Java e Cloud

## Objetivo

Desenvolver um sistema cadastral Web utilizando tecnologias da plataforma Java Enterprise Edition (JEE), implementando persistência de dados com JPA, regras de negócio com EJB, interface Web com Servlets e JSP, além da utilização do framework Bootstrap para melhoria visual da aplicação.

## Tecnologias Utilizadas

* Java JDK 8+
* Visual Studio Code (VS Code)
* Jakarta EE 8
* GlassFish Server 6.2.1
* SQL Server
* JDBC Driver SQL Server
* JPA (Java Persistence API)
* EJB (Enterprise Java Beans)
* Servlets
* JSP (Java Server Pages)
* Bootstrap 5
* Git e GitHub

## Desenvolvimento do Projeto

O projeto foi desenvolvido utilizando a IDE Visual Studio Code, devido à familiaridade com a ferramenta e à sua praticidade para edição e organização do código-fonte.

Embora o roteiro da disciplina utilize o NetBeans como referência, todas as funcionalidades exigidas foram implementadas seguindo os mesmos conceitos e tecnologias propostas.

O sistema foi dividido em camadas:

### Camada de Persistência (JPA)

Responsável pela comunicação com o banco de dados SQL Server através de entidades JPA.

Foram criadas classes de entidade representando as tabelas do banco de dados da aplicação.

### Camada de Negócio (EJB)

Implementada utilizando Session Beans para encapsular as regras de negócio e operações CRUD.

### Camada Web

Desenvolvida utilizando:

* Servlets para controle das requisições;
* JSP para apresentação dos dados;
* Bootstrap para melhoria da interface gráfica.

## Funcionalidades Implementadas

### Cadastro de Produtos

Permite incluir novos produtos no sistema.

### Listagem de Produtos

Exibe todos os produtos cadastrados no banco de dados.

### Alteração de Produtos

Permite editar os dados de produtos existentes.

### Exclusão de Produtos

Permite remover produtos cadastrados.

## Estrutura do Projeto

```text
CadastroEE
│
├── CadastroEE-ejb
│   ├── model
│   ├── controller
│   └── persistence.xml
│
├── CadastroEE-war
│   ├── servlets
│   ├── jsp
│   └── web.xml
│
└── Banco SQL Server
```

## Interface

A interface foi construída utilizando JSP e Bootstrap, garantindo:

* Layout responsivo;
* Melhor organização visual;
* Facilidade de navegação;
* Compatibilidade com diferentes dispositivos.

## Resultados Obtidos

O sistema foi executado com sucesso realizando:

* Cadastro de produtos;
* Consulta de produtos;
* Alteração de registros;
* Exclusão de registros;
* Persistência dos dados no SQL Server.

## Análise e Conclusão

### Como é organizado um projeto corporativo Java?

Um projeto corporativo Java é organizado em camadas, separando persistência, regras de negócio e interface, facilitando manutenção e reutilização do código.

### Qual o papel do JPA e do EJB?

O JPA é responsável pelo mapeamento objeto-relacional e persistência dos dados. Já o EJB centraliza as regras de negócio e o gerenciamento dos componentes corporativos.

### Como o VS Code auxiliou no desenvolvimento?

O Visual Studio Code forneceu recursos como:

* Destaque de sintaxe;
* Integração com Git;
* Extensões Java;
* Terminal integrado;
* Organização do projeto.

Esses recursos contribuíram para aumentar a produtividade durante o desenvolvimento.

### O que são Servlets?

Servlets são componentes Java executados no servidor responsáveis por processar requisições HTTP e gerar respostas para o usuário.

### Como ocorre a comunicação entre Servlets e EJBs?

A comunicação ocorre através da injeção dos Session Beans utilizando a anotação @EJB, permitindo que os Servlets utilizem os serviços disponibilizados pela camada de negócio.

## Bootstrap e Responsividade

O Bootstrap foi utilizado para melhorar o design da aplicação através de componentes prontos e classes CSS responsivas.

Com isso, a aplicação tornou-se mais amigável visualmente e adaptável a diferentes tamanhos de tela.

## Repositório GitHub

Adicionar aqui o link do repositório:

```text
https://github.com/seu-usuario/seu-repositorio
```

## Considerações Finais

O desenvolvimento deste trabalho permitiu aplicar conceitos fundamentais de aplicações corporativas Java, incluindo persistência de dados, regras de negócio, desenvolvimento Web e integração com banco de dados, proporcionando experiência prática com tecnologias amplamente utilizadas no mercado.
