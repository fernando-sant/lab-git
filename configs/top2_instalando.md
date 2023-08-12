# Instalando o Git (Parte 1)

Agora que já desmistificamos o terminal (ou tentamos), podemos usá-lo para o Git. Mas, antes de tudo, precisamos instalá-lo em nosso computador, para isso faremos uso do terminal.

## Usuários de Windows

Se você seguiu corretamente os passos em [Aos usuários de Windows](top_windows.md), você deve ter percebido que não há necessidade de fazer absolutamente nada.

Só para agilizar o trabalho, já abra o Git Bash no menu de aplicativos. Sua parte acaba aqui e você já pode ir para [Instalando o Git (Parte 2)](top3_instalando2.md) :grin:

## Usuários de Mac OS

- Abra o seu terminal (você o encontrará no menu de aplicativos) e instale o gerenciador de pacotes Homebrew (ele permite que você possa instalar coisas que a Apple não te fornece, como o Git)

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Com o Homebrew instalado, instale o Git com o seguinte comando:

```
brew install git
```

## Usuários de Linux

### Sistemas baseados em Debian, como Ubuntu ou o próprio Debian

   - Para instalar o Git em sistemas baseados em Debian, execute o seguinte comando:
   ```
   sudo apt update && sudo apt install git
   ```

### Sistemas Red Hat, como o Fedora

   - Para instalar o Git em sistemas baseados no Red Hat, execute o seguinte comando:

   ```
   sudo yum install git
   ```

### Outras distribuições

   - Provavelmente você já sabe como instalar :smiley:

Agora que você já instalou o Git e ele está operacional, você pode avançar para [Instalando o Git (Parte 2)](./top3_instalando2.md)