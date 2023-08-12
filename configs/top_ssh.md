# Como Gerar uma Chave SSH ed25519 para o Git

## O que é uma Chave SSH?

Uma chave SSH é uma forma segura de autenticação que permite que você se conecte a servidores e serviços de forma criptografada, sem precisar digitar senhas a cada vez. Isso é especialmente útil ao trabalhar com o Git, pois você pode se conectar ao GitHub, GitLab ou outros serviços sem precisar digitar sua senha toda hora.

## Por que Usar ed25519?

Uma chave SSH criada com o método ed25519 é interessante pelos seguintes pontos:

1. É mais segura que criptografias anteriores;
2. As chaves geradas são menores;
3. São mais seguras e bem mais fáceis de gerar e de serem verificadas.

## Como Gerar uma Chave SSH ed25519

Siga os passos abaixo para gerar uma chave SSH Ed25519:

### 1. Abra o Terminal (ou Git Bash no Windows)

Você precisará do terminal para executar os comandos. Caso precise, volte à página [Introdução ao terminal](top1\_terminal.md)

### 2. Execute o Comando para Gerar a Chave

No terminal, execute o seguinte comando, substituindo "seu\_email@example.com" pelo seu endereço de email:

```bash
ssh-keygen -t ed25519 -C "seu_email@example.com"
```

* Quando for pedido o nome do arquivo, apenas pressione Enter ou coloque um nome de sua preferência (mas lembre-se dele depois)
* Digite uma senha para a sua chave (lembre-se dela, vamos usar mais tarde)

### 3. Copie a chave com o seguinte comando

```bash
cat ~/.ssh/id_ed25519.pub
```

* Selecione o texto que aparecer e copie-o.
