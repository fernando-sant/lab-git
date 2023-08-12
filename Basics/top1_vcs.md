# O básico sobre VCS

Um sistema de controle de versões tem as seguintes funções:

 - Guardar um histórico de todas as mudanças feitas nos arquivos (rastrear): o VCS deve possibilitar o controle dos arquivos por meio de datas de modificação, comentários feitos para caracterizar cada versão, voltar/avançar de versão, compará-las... Como vimos no início, este diretório onde todas essas mudanças acontecem e são registradas é chamado de repositório (ou repo, carinhosamente)

 - Permitir que um desenvolvimento colaborativo: cada usuário que trabalha no projeto deve poder ser identificado e controlado por meio de direitos (às vezes um usuário deve poder criar arquivos e outro não, por exemplo)

 - Deixar o desenvolvedor decidir quando as alterações que ele fez devem ser colocadas sob o controle do VCS: isso é chamado de commit.

 - Mesclar (fusão) diferentes modificações feitas no mesmo arquivo; essa função é necessária quando vários desenvolvedores trabalham no mesmo arquivo.

 - Etiquetar (tag) um conjunto de arquivos como pertencentes à mesma versão.

 - Possibilitar a criação de uma cópia dos arquivos que é igualmente gerenciável e que serve para modificar os arquivos sem prejudicar a versão funcional. Se você estiver satisfeito com suas modificações, pode optar por mesclá-las (merge) à versão principal; caso contrário, pode mantê-las separadas, talvez para uma versão específica, ou simplesmente excluí-las. Essa cópia é chamada de ramificação (branch em inglês)

A partir de agora, vamos usar uma série de termos ao longo desta formação. Para garantir uma maior naturalidade com eles, avance para [Vocabulário](./top2_voca.md)