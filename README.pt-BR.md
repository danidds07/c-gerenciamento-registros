[English](README.md) | **Português**

# Sistema de Gerenciamento de Registros em C

Aplicação de terminal em C para gerenciar registros salvos direto em arquivo binário,
feita para a disciplina de Algoritmos 2. O foco é em manipulação de arquivos, não em
banco de dados: os registros são lidos e gravados diretamente em disco com `fread`,
`fwrite` e `fseek`.

## O que dá para fazer

- criar, listar, atualizar e buscar registros (por ID ou por nome);
- excluir um registro de forma lógica, marcando-o como inativo sem apagar os dados;
- excluir um registro de forma física, reescrevendo o arquivo sem aquele registro;
- validar a entrada de números e textos, para que dados inválidos não cheguem ao arquivo;
- abrir um manual de ajuda com F1, guardado em um arquivo separado e ofuscado com XOR.

Os registros são modelados com structs e ficam guardados em um único arquivo binário,
sem depender de nenhuma biblioteca externa.

## Tecnologias

- C
- Biblioteca padrão (stdio, stdlib, string, ctype)
- Manipulação de arquivos binários (fread, fwrite, fseek)
- Modelagem de dados com structs

## Como executar
```bash
gcc sistemaregistro.cpp -o record-system
./record-system
```

## Estrutura do projeto
```text
c-record-management-system/
|-- sistemaregistro.cpp
`-- README.md
```

## Contexto acadêmico

Feito para a disciplina de Algoritmos 2, como exercício de manipulação de arquivos
binários, ponteiros de arquivo e persistência de dados sem usar banco de dados.

## Autor

Desenvolvido por Daniel Augusto Silva.
