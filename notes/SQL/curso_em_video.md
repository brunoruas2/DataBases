Curso de Banco de Dados MySQL

<details>
<summary>
    <font size=5> Aula 01 - O que é um Banco de Dados </font>
</summary>

<br/>

[Link da aula](https://www.youtube.com/watch?v=Ofktsne-utM&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r)


Evolução do Armazenamento dos dados:
- Arquivo sequencial
- Arquivo direto
- Banco de dados

<br />

Composição do Banco de dados
- Base de Dados
- SGBD (ADMS)
- Linguagem de Exploração
- Programas Adicionais (administração)

<br />

Modelos propostos na dec. 60 pela IBM
1. Modelo Hierárquico
1. Modelo em Rede

<br />

O modelo que vamos usar aqui é o **Modelo Relacional** que surgiu na déc. de 70. Mas tem outros (documentos e objetos, por exemplo).

O Structured Query Language (SQL) é justamente essa linguagem de exploração pertencente ao padrão de Banco de Dados.

<br />

Soluções de Bancos SQL:
1. Oracle (paga)
1. IBM (paga)
1. Microsoft SQL Server (paga)
1. MySQL (free)
1. MariaDB (free) [de um criador do MySQL]
1. Firebird (free)
1. PostgreSQL (free)

<br/>

</details>

---

<details>
<summary>
    <font size=5> Aula 02 - Instalando o MySQL com WAMP </font>
</summary>

<br/>

[link da aula - parte 1](https://www.youtube.com/watch?v=5JbAOWJbgIA&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r&index=2)

[link da aula - parte 2](https://www.youtube.com/watch?v=R2HrwSQ6EPM&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r&index=3)


História do MySQL. Monty e Outro cara. Licença GPL. Comprado pela SUN e depois pela ORACLE. É usado em várias empresas importantes (públicas e privadas).

<br/>

Grupos de comandos dentro do MySQL:
- DDL - Definição
- DML - Manipulação
- DQL - Solicitação
- DCL - Controle
- DTL - Transações

<br/>

Características de uma boa transação:
- Durabilidade - os dados devem permanecer
- Isolamento - cada transação é indiferente das outras
- Consistência - ok antes, ok depois
- Atomicidade - cada transação é tudo ou nada

<br/>

## Instalando o MySQL no windows
Stack:
1. MySQL workbench (com requisitos)
    - pode ser com o Dbeaver
1. wampserver (com requisitos); ou
1. xampp

<br/>

user: hoot

psw: just_enter

<br/>

No console, digite `status` pra ver se tá funcionando bem.

</details>

---

<br/>

<details open>
<summary>
    <font size=5> Aula 03 - Criando o primeiro Banco de Dados </font>
</summary>

<br/>

[link da aula](https://www.youtube.com/watch?v=m9YPlX0fcJk&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r&index=4)

