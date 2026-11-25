
# Sistema de Gerenciamento de Senhas de Atendimento Clínico

## Objetivo

Desenvolver um sistema em linguagem C para gerenciar
senhas de atendimento de uma clínica, classificando
pacientes de acordo com suas prioridades.

## Funcionalidades

- Cadastro de pacientes.
- Classificação automática de prioridades.
- Geração de senhas sequenciais.
- Filas normal, preferencial e urgente.
- Chamada de pacientes.
- Finalização de atendimentos.
- Consulta da próxima senha.
- Painel de chamadas.
- Contagem de pacientes em espera.

## Tecnologias utilizadas

- Linguagem C
- Struct
- Vetores
- Funções
- Filas FIFO
- Estruturas condicionais
- Estruturas de repetição

## Como compilar

Utilizando GCC:

```bash
gcc main.c -o clinica
```

## Como executar

Linux:

```bash
./clinica
```

Windows:

```bash
clinica.exe
```

## Funções implementadas

- inicializarFila()
- filaVazia()
- filaCheia()
- adicionarFila()
- removerFila()
- classificarPaciente()
- gerarSenha()
- cadastrarPaciente()
- consultarProximo()
- chamarProximo()
- finalizarAtendimento()
- exibirFilas()
- exibirPainel()
- exibirMenu()

## Exemplo de utilização

Cadastro de paciente:

```text
Nome: Maria
Genero: F
Idade: 35
Esta gestante? S
E lactante? N
Possui necessidade especial? N
Possui condicao de obesidade? N

Senha: P001
Categoria: PREFERENCIAL
```

Chamada:

```text
===== CHAMADA DE PACIENTE =====
Senha: P001
Nome: Maria
Categoria: PREFERENCIAL
```

## Autor

Projeto acadêmico desenvolvido em linguagem C.
