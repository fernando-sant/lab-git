# Introdução ao Terminal: O Que é e Como Usar

Para muitos usuários não técnicos, o terminal é como se fosse uma caixinha de surpresas. Porém ele nada mais é do que uma forma de conversar com o seu computador, mas em texto. Você pode dar comandos e o computador fará o que você pedir. Vamos ver alguns comandos básicos para trabalharmos com Git com mais conforto.

## Abrindo o seu terminal

### Windows
:warning: Se você estiver usando Windows, antes de seguir as instruções desta página, certifique-se de que você seguiu todas as etapas em [Aos usuários de Windows](./top_windows.md)

Caso você tenha seguido corretamente os passos indicados, inicialize a aplicação "Git Bash", uma tela irá se abrir e você já poderá digitar comandos.

### Mac OS

O terminal já vem instalado por padrão. Você poderá encontrá-lo no menu de aplicações (pasta de utilitários)

### Linux

Normalmente, você já sabe onde fica o terminal e como acessá-lo.


## Comandos Básicos

Aqui estão alguns comandos simples que você usará:

1. **pwd** (Mostrar Diretório): Mostra onde você está no computador.

```
$ pwd
```

2. **cd** (Mudar de Pasta): Vai para outra pasta. Imagine como entrar em pastas em um armário.

```
$ cd nome_da_pasta/
```

3. **ls** (Listar): Mostra o que está dentro da pasta onde você está.

```
$ ls -la
```

:point_right: os comandos -l e -a servem para mostrar de um jeito mais organizado os arquivos da pasta de trabalho, além de mostrar os arquivos ocultos (o que é útil trabalhando com Git)

4. **mkdir** (Criar Pasta): Cria uma nova pasta.

```
$ mkdir
```

5. **touch** (Criar Arquivo): Cria um novo arquivo vazio.

```
$ touch
```

6. **rm** (Remover): Apaga um arquivo (cuidado, não há lixeira!).

```
$ rm
```

:point_right: caso você queira remover uma pasta, você deve usar a seguinte opção

```
$ rm -r caminho/para/pasta
```

7. **cp** (Copiar): Faz cópias de arquivos.

```
$ cp
```

8. **mv** (Mover): Move arquivos de um lugar para outro.

```
$ mv
```

9. **clear** (Limpar Tela): Limpa a tela para ficar organizado.

```
$ clear
```

## Atalhos Úteis (para facilitar sua vida)

Alguns atalhos para tornar as coisas mais fáceis:

- **Tab**: Complete automaticamente nomes de pastas e arquivos.

- **Ctrl + C**: Para interromper um comando que está demorando.

- **Ctrl + D**: Sair do terminal.

- **Ctrl + L**: Limpar a tela.

## Caminhos e Pastas

No terminal, você precisará dizer onde quer fazer algo. Pode ser em uma pasta. Alguns termos para entender:

- **Caminhos Absolutos**: Começam na raiz do computador (por exemplo, C:/Usuarios/SeuNome/Pasta).

- **Caminhos Relativos**: São em relação à pasta onde você está (por exemplo, ./arquivo para um arquivo na pasta atual).

### Para entender melhor os caminhos relativos

- **~/** : "apelido" da pasta do usuário

- **./** : o ponto é um "apelido" para a pasta atual de trabalho

- **../** : os dois pontos seguidos são um "apelido" para a pasta pai da pasta atual de trabalho

Esses apelidos são melhores do que ter que digitar o caminho inteiro da pasta (caminho absoluto) a cada vez que você precisar.
## Próximos Passos

Agora que você conhece o básico, vamos usar essas habilidades para trabalhar com o Git no próximo tópico.

[Avançar para Instalando o Git (Parte 1)](./top2_instalando.md)