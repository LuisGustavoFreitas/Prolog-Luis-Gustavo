# Sistema de Carreira em Prolog

**Instituição:** PucPr  
**Disciplina:** Programação Lógica e Funcional  
**Professor:** Frank Coelho de Alcantara  
**Aluno:** Luis Gustavo Freitas Kulzer  

## Estrutura do Projeto

- 'questionario.pl': Código principal  
- 'perfil_teste_1.pl': Arquivos de teste 1   
- 'perfil_teste_2.pl': Arquivos de teste 2  
- 'perfil_teste_3.pl': Arquivos de teste 3  

## Como executar

### 1- IDE utilizada:
O sistema foi desenvolvido com **SWI-Prolog**
### 2- Para carregar o arquivo digite:
```prolog
?- [questionario].
```
### 3- Para responder o questionario interativo digitar:
```prolog
?- iniciar.
```  
### 4- Para testar com respostas já prontas digite:  
```prolog
- ?- consult('questionario.pl'), consult('perfil_teste_1.pl'), resultado.  
- ?- consult('questionario.pl'), consult('perfil_teste_2.pl'), resultado.  
- ?- consult('questionario.pl'), consult('perfil_teste_3.pl'), resultado.
```
