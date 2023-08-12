# Vocabulário básico

Neste processo de aprendizagem do Git, vamos usar vários termos com uma certa frequência. Para que eles fiquem mais naturais para você, leia as seguintes definições.

## **Repositórios**

Um repositório é um local onde o Git armazena o histórico do seu projeto, incluindo todos os arquivos e as alterações feitas ao longo do tempo.

- **Repositório Local:** É uma cópia do projeto em seu computador. Você trabalha com esse repositório, fazendo alterações, como adições, remoções e criando ramificações.

- **Repositório Remoto:** É uma cópia do projeto em um servidor, como o GitHub ou o GitLab. Pode ser usado para colaboração em equipe e compartilhamento de código.

Basicamente, um repositório é a pasta do seu projeto e, normalmmente, haverá uma pasta oculta .git (nunca mexa nesta pasta!)

## Versionamento

É um conceito bem intuitivo, consiste no estabelecimento de versões de um projeto. A cada versão, registramos as diferenças entre a versão atual e a versão anterior, sabendo o que foi mudado e quem foi o responsável pela alteração.

## Commit

Podemos considerar um commit como uma "foto" dos seus códigos naquele momento específico. Ele é caracterizado não só pelos códigos (e suas alterações), mas também por uma mensagem curta que indica o que a pessoa fez.

Cada conjunto de mudanças no projeto implica em uma nova versão do projeto (diferente da anterior). Isto é, cada commit (foto) é um **marcador de uma nova versão do projeto**.

## Branch

Digamos que você está trabalhando em uma versão do projeto e ela esta funcionando. Você quer adicionar uma nova versão e não sabe se ela vai funcionar, mas não quer estragar seu código funcional fazendo experimentos.

Neste contexto, criamos uma separação no código, uma ramificação do projeto a partir de uma versão funcional (ou outra versão específica do projeto). Cada projeto no Git é iniciado em uma ramificação por padrão **master**.

A branch master não tem nada de especial, ela só é a primeira, tenha isso em mente.

## Merge

Como na situação anterior, você criou uma ramificação nova, trabalhou na nova funcionalidade e, agora que ela está funcionando, quer adicionar àquela branch principal (que não tinha a função nova). Para isso, vamos "fundir" as duas ramificações, colocando as novas funcionalidades na branch principal. A esta operação de "fusão" dá-se o nome de **merge**.

### Exemplo básico

Suponha que estamos trabalhando na criação de um site. Na ramificação principal (branch master), as seguintes páginas estão criadas e funcionando: homepage e catálogo de produtos.

Os clientes querem entrar em contato comigo, mas o site não tem as informações de contato, ou seja, falta uma página contato. Como o meu projeto está sob controle do Git (VCS), para não correr o risco de estragar o que já está feito, eu vou criar uma nova ramificação (**branch**) e trabalhar na minha página contato.

Depois que esta página contato estiver pronta, e não houver nenhum erro, eu vou querer adicioná-la ao meu site que já estava funcionando. Para isso, eu vou registrar as modificações (**commit**) e fundir as duas ramificações (a versão que estava funcionando e a outra com a página contato), ou seja, um **merge**. Ao final desta operação, meus clientes verão então um site com as páginas: homepage, catálogo de produtos e contato. :smiley:

## Clone

Quando se deseja trabalhar em um projeto hospedado em uma plataforma online (por exemplo, um projeto no GitHub), o clone de um repositório "baixa" o conteúdo da internet para o seu dispositivo local. Com isso, ao clonar um repositório, você poderá trabalhar nele do seu computador e, posteriormente, enviar modificações de volta. (É o início de um projeto do Git que já está online)

## Pull

Quando se trabalha com um repositório local e um remoto, por exemplo, outras pessoas podem ter modificado os arquivos remotos, então, uma operação **pull** (puxar), atualiza o repositório local com os novos arquivos.

A operação **pull** faz um **merge** (fusão) entre a ramificação local e a ramificação online e possíveis conflitos entre versões podem (e devem) ser resolvidos.

## Push

É a operação pull no sentido contrário. Um **push** vai enviar os arquivos do repositório local para o repositório remoto (no GitHub por exemplo).

## Fork

Cria um clone do projeto pai no servidor remoto (não baixa no seu computador).

Com estes conceitos em mente, siga para [Criando uma conta no GitHub](top3_criaconta.md)