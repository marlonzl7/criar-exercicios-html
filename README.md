# Script para criar arquivos para lista de exercícios

Script em C que automatiza a criação de arquivos HTML com estrutura básica.

## Pré requisitos
- GCC instalado (verifique com `gcc --version`).

## Como usar?
  - Compile:
```
gcc criar-exercicios.c -o criar-exercicios
```

  - Execute:
```
./criar-exercicios
```

  - Informe o número de exercícios que quer criar:
```
Quantidade de arquivos: 5
```

  - O script criára automaticamente os arquivos:
```
exercicio-1.html
exercicio-2.html
exercicio-3.html
exercicio-4.html
exercicio-5.html
```

 - Cada arquivo terá esse HTML base:

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercício X</title>
</head>
<body>
    
</body>
</html>
```

## Personalização

**Você pode editar o código para:**
 - Alterar a extensão dos arquivos criados (.c, .cpp, .py, etc.).
 - Modificar o conteúdo base gerado dentro de cada arquivo.
