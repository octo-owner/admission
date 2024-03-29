# Mostre-nos o talento que existe dentro de você

Sobre a OCTO Tecnologia e Consultoria
-------
Somos uma Fábrica de Software onde buscamos atender com Qualidade e Pontualidade os projetos onde estamos inseridos.
Atualmente possuímos 4 produtos SaaS (Software as a Service) e outras frentes de trabalho em Consultoria, Outsourcing e Gestão e Mentoria de Projetos

Perfil
-------

Buscamos profissionais apaixonados por Programação e entusiasmados com a possibilidade de conhecer novos horizontes, aplicar e compartilhar tudo aquilo que vem estudado em sua trajetória.

Desafio
-------

Propomos um desafio Hands-On, onde você demonstrará sua capacidade em resolver problemas e também o quão preparado está para as rotinas do seu dia-a-dia como desenvolvedor

Para isto, escolha suas trilhas:

<!--- 
<trilha>FrontEnd </trilha> 
------------

<trilha>BackEnd</trilha>
------------
-->
## Desenvolvedor .Net Full-Stack

### Avaliação de Proficiência Tecnológica / Negócios

**IMPORTANTE:** Para a realização destas atividades, você deverá **contabilizar o tempo utilizado** para cada uma das partes da avaliação.

#### Parte 1: C# + Asp.Net Core, SQL Server e VueJS

##### Dicionário de Dados

| Cliente	| Telefone | Endereco |
|---|---|---|
| Codigo *	| Codigo *	| Codigo * |
| Nome *	| Tipo *	| Tipo * |
| Tipo (Física ou Jurídica) *	| DDD * |	Logradouro * |
| CPF / CNPJ *	| Numero *	| Numero * |
| RG / Inscrição Estadual *	| Observacoes	| Complemento |
| Email *	| CodigoPessoa * | Bairro * |
| Data de Nascimento / Fundação | |	Cidade * |
| Data de Cadastro (automático/sistema) | |	UF * |
| | |	CEP * |

##### Roteiro

Criar um **CRUD** para cadastro de **Clientes (pessoas físicas e/ou jurídicas)** de uma rede de **distribuidora de bebidas** seguindo o [Dicionário de Dados](#dicionário-de-dados) definido acima, onde, para cada Cliente:
* Deverá permitir a inserção de múltiplos telefones e para cada telefone indicar o seu tipo (celular, residencial ou comercial).
* Deverá permitir a inserção de múltiplos endereços e para cada endereço indicar seu tipo (cobrança, comercial, correspondência, entrega ou residencial).

Na tela de listagem de Clientes:
* Deverá exibir os seguintes campos: Nome, CPF, CNPJ e Email.
* Pesquisa por Nome
* Ordenação (todos os campos)
* Paginação de registros

_Validações:_
1. Campos **Codigo** deverão ser **auto-numéricos**.
1. Campos marcados com * no [Dicionário de Dados](#dicionário-de-dados) são obrigatórios;
1. Deverá existir pelos menos um telefone e um endereço;
1. De acordo com o tipo de cliente, aplicar as máscaras necessário nos documentos pessoais;

**_Diferenciais:_**
1. Validar Email.
1. Validar CPF e CNPJ de acordo com a regra específica de validação de cada um.
1. Validar Inscrição Estadual de acordo com a regra da Sefaz de SP.

Ficará a critério do programador utilizar **Code First** ou **Database First** (caso escolha Database First, você deverá incluir o Script SQL de criação do Banco de Dados - tabelas, relacionamentos e etc - no projeto a ser enviado), justifique sua escolha no [email de envio da atividade](#parte-2-publicar-avaliações-no-github) .

**Após o término do desenvolvimento:**

Criar um script que insira cem clientes com pelo menos um telefone e um endereço e deixar salvo o script para avaliação (o conteúdo escolhido para ser inserido não será validado, poderá ser adodato qualquer critério pelo desenvolvedor, ex: inseridos cem Roberto, desde que tenha uma distinção entre eles, como Roberto, Roberto1, Roberto2 etc.).

#### Parte 2: Publicar avaliações no GitHub
Crie uma Conta no GitHub (caso já possua uma, utilize a sua), publique (sim, deixar o repositório público) as avaliações no seu GitHub e envie o link do repositório para: rh@octoti.com.br com o Assunto: _**Vaga Desenvolvedor FullStack - Avaliação de Proficiência Tecnológica / Negócios**_.

No corpo da mensagem enviar o **tempo contabilizado** para a realização de cada uma das partes da Avaliação, bem como a **Justificativa** da escolha entre **Code-First** e **Database-First**.

