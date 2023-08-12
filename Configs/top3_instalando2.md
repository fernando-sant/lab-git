# Instalando o Git (Parte 2)

Agora que já desmistificamos o terminal (ou tentamos), podemos usá-lo para o Git. Mas, antes de tudo, precisamos instalá-lo em nosso computador, para isso faremos uso do terminal.


## Configuração do Nome de Usuário e Email

Após instalar o Git, é importante configurar o seu nome de usuário e endereço de email. Isso é usado para identificar quem fez as alterações nos commits (versões) do código. Execute os seguintes comandos, substituindo "Seu Nome" e "seu@email.com" pelas suas informações:

```css
$ git config --global user.name "Seu Nome"
```

```css
$ git config --global user.email "seu@email.com"
```

```css
$ git config --global color.ui auto
```

:point_right: Esse último comando só dá umas cores diferentes para as saídas (outputs)

Uma vez o Git instalado e configurado, podemos seguir para esta ferramenta propriamente dita. Por favor, avance para [O básico sobre VCS](../Basics/top1_vcs.md)