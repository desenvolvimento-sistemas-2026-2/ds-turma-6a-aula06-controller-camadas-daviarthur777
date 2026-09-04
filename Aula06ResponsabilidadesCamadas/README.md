# Aula 6 - Responsabilidades e Camadas

## Integrantes
- Integrante A:
- Integrante B:
- Turma:

## Objetivo da aula
Criar um controller simples e ajustar o projeto para reforçar a separação de responsabilidades.

## Tabela de responsabilidades

| Pacote | Responsabilidade | Exemplo no projeto |
| :--- | :--- | :--- |
| **app** | Iniciar o sistema e montar os objetos principais[cite: 1]. | `Principal.java`[cite: 1] |
| **model** | Representar os dados do domínio[cite: 1]. | `Aluno.java`[cite: 1] |
| **repository** | Guardar e consultar os alunos em memória[cite: 1]. | `AlunoRepository.java`[cite: 1] |
| **service** | Concentrar regras simples e validações[cite: 1]. | `AlunoService.java`[cite: 1] |
| **controller** | Receber pedidos da view e acionar o service[cite: 1]. | `AlunoController.java`[cite: 1] |
| **view** | Conversar com o usuário usando JOptionPane[cite: 1]. | `MenuAlunos.java`[cite: 1] |

## Testes realizados

- [x] Projeto executou antes das alterações[cite: 1]
- [x] Cadastro de aluno funcionando[cite: 1]
- [x] Listagem funcionando[cite: 1]
- [x] Busca funcionando[cite: 1]
- [x] Opção de quantidade funcionando[cite: 1]

## Observações da dupla

Criamos a camada `controller` para intermediar as requisições da camada de apresentação (`view`) para a regra de negócio (`service`)[cite: 1]. Também atualizamos a interface textual para incluir a opção 4 que exibe a quantidade total de alunos[cite: 1].
