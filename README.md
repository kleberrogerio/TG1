# TG1 - 4º semestre de BD

 

Professor da Disciplina: Giuliano Bertoti 

 

# TG

 

Aluno: Kleber Rogério do Nascimento - 1460281723059
Orientador: Me. Fabiano Sabha Walczak

 

Título do TG: SISTEMA DE GERENCIAMENTO DE FUNCIONÁRIOS E COOPERADOS

 

# 1ª Quinzena de maio

# INTRODUÇÃO

Uma cooperativa tem um sistema de banco de dados que é usado para o contato com os cooperados dessa cooperativa, como foi elaborado em um sistema muito antigo, está inutilizado no momento.

A cooperativa também, por algumas mudanças nas leis está operando com poucos cooperados, teve então que se adaptar ao modelo “CLT” e com isso surge a necessidade da criação de mais um banco de dados.

Outra necessidade da empresa seria a opção de cadastrar currículos pela internet, um lugar onde o próprio interessado digite seus dados.
Baseado nesses problemas, surgiu a idéia de refazer o banco de dados na versão web, criar um banco de dados para funcionários “CLT” e nesse mesmo sistema dar a opção de cadastramento de currículos online. 

# 1.1. Objetivos do Trabalho 

O objetivo geral deste trabalho é reformular um programa de banco de dados que foi feito em Delphi 5.0, reformular as tabelas, incluir um cadastro de funcionários e dar a opção da pessoa interessada em trabalhar na empresa faça o cadastro pela internet e esses dados sejam guardados na base de dados.

Para a consecução deste objetivo foram estabelecidos os objetivos específicos:

•	Organizar as tabelas da melhor forma possível para melhor entendimento e mais rapidez em uma pesquisa.

•	Pesquisar as melhores ferramentas para utilizar nesse sistema.

•	Fazer diversos testes para evitar erros no sistema.

•	Melhorar a parte de aparência do sistema, para ficar mais agradável e mais moderno.


 

# 2ª Quinzena de maio

 

Foi verificado junto a empresa a necessidade de um cadastro de funcionários em regime de CLT,  um acesso online aos funcionários e cooperados para eles mesmo poderem cadastrar o currículo e esse currículo já entrar no nosso sistema.

O sistema terá a mesma funcões do sistema antigo com as devidas melhoras.

Será necessário o uso de MySQL, o Sistema será feito usando o Springboot.

Servidor Apache.


 

# 1ª Quinzena de junho
 
Será necessário instalar uma máquina virtual (Virtual box) pelo motivo que o sistema que vai ser reestruturado não funciona em 64 bits. 

Nessa máquina virtual será instalado o MYSQL para a organização das tabelas do banco de dados anterior.  

 

# 2ª Quinzena de junho

 

(coloque aqui tudo que você fez referente ao capítulo 3 no formato exato de BD) + crie um pasta chamada "Desenvolvimento" e coloque o início do código

 

# 1ª Quinzena de julho

# Levantamento de requisitos do sistema atual.
## CADASTRANDO COOPERADOS

![CadastroCooperados](https://github.com/kleberrogerio/TG1/blob/master/Cadastro_cooperados.jpg) 
 
O cadastro de cooperados será feito somente pelo módulo de interessados, uma vez que o você clicar no botão Tornar cooperado no módulo interessados.

## ALTERANDO OS DADOS
	
Já que os dados de cooperados já estão previamente cadastrados podemos apenas adicionar ou alterar dados e para isso é necessário clicar no botão alterar.


## ABA DADOS PESSOAIS 

## Detalhe de preenchimento dos campos


## Veja com detalhes como deve ser o preenchimento dos campos :

## Matricula

O sistema automaticamente lhe dará um número de inscrição que será mostrado no primeiro campo na parte superior da tela. 
	


## Data de Cadastro 

O sistema colocará uma data corrente do computador, ressaltamos a necessidade de que a data do computador esteja correta.
Caso seja necessário alterá-la o preenchimento manual deve ser feito de maneira  dd-mm-aaaa.
Exemplo : 23-01-2001

## Data de Nascimento 

É necessário que a data de nascimento seja  preenchida manual deve ser feito de maneira  dd-mm-aaaa.
Exemplo : 12-01-1970

## Nº de Filhos 

O preenchimento do número de filhos deve ser feito manualmente deve ser preenchido sem zeros a esquerda.

## Nome 

É imprescindível que se preencha o campo nome o mais completo possível  e sem acentos para facilitar as pesquisas posteriores.

## Nome de Guerra

O nome de guerra não tem necessidade de ser preenchido, mas é um dado útil futuramente.

## CPF

O CPF deve ser preenchido de maneira correta e completa

## RG

O  RG deve ser preenchido de maneira correta e completa, se possível com o órgão emissor logo após o número

## Órgão Expedidor

O campo órgão expedidor deve ser preenchido com o nome correto 

## Data de Emissão 

A data de emissão deve ser preenchida como no exemplo abaixo :
dd-mm-aaaa : 05-02-2002 .


## Estado civil

O campo Estado civil já deve estar previamente preenchido, mas caso não esteja é só selecionar uma das opções disponíveis. 

## Sexo
O campo sexo deve ser preenchido com uma das opções FEM ou MASC, para facilitar é necessário digitar apenas a primeira letra do sexo.


## Data Nasc 
A data de nascimento deve ser preenchida no formato dd-mm-aaaa .
           Exemplo : 13-02-1980

## Rua
A rua deve ser preenchida se possível com o nome completo e com os complementos que existirem.

## Bairro
O bairro deve ser  preenchido somente com o nome

## Cep
É importante que se tenha o CEP correto do interessado, para que não haja problemas posteriores na hora de gerar etiquetas para correspondências.

## Cidade

A Cidade deve ser preenchida por extenso sem acentos.

## Estado
O campo estado está ordenado em ordem alfabética para facilitar a localização do mesmo, como nos demais campos do mesmo tipo, basta digitar a primeira letra do estado para que o campo seja preenchido.

## País 
O País deve ser preenchido com o país de residência do cooperado.

## Tel residencial
O campo telefone Residencial deve ser preenchido com o código de área como no exemplo a seguir :  12 - 39386000

## Tel comercial
O campo telefone Comercial deve ser preenchido com o código de área como no exemplo a seguir :  12 – 39386000

## Email 
	# O email deve ser preenchido por extenso incluindo o símbolo ‘ @’ 

## Pai
O campo pai deve ser preenchido com o nome do pai cooperado e deve ser preenchido de maneira mais completa possível.

## Mae
O campo Mãe deve ser preenchido com o nome da Mãe  cooperado e deve ser preenchido de maneira mais completa possível 

## Cônjuge 
O campo Cônjuge deve ser preenchido com o nome completo pois tal campo é importante para fins de relatórios.

## Local De Nascimento
O campo local de nascimento deve ser preenchido com estado de Nascimento do cooperado.

## Situação 
Este campo deve ser preenchido com uma das opções descritas na caixa de opções, para vê-las basta clicar na seta no canto direito da caixa.

## Nacionalidade
O campo nacionalidade deve ser preenchido com a nacionalidade do cooperado.

## Desligamento
O campo desligamento deve ser preenchido com a data do desligamento do cooperado quando houver o desligamento e não deve se esquecer que o campo situação deve ser mudado para desligado.

## Motivo
O Motivo do desligamento deve ser selecionado como nos campos anteriores clicando no canto da caixa de diálogo.

## Classificação
O campo classificação deve ser preenchido com os negócios nos quais o cooperado esta envolvido, para isto basta clicar no botão Incluir , e preencher os campos, para efetuar a exclusão de um negócio deve-se clicar no campo a ser excluído e clicar no botão excluir.

