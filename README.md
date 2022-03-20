# Documentos da Mentoria IaC

Repositório de documentos gerados duranto os trabalhos da Mentoria IaC. As
seções a seguir descrevem em mais detalhes cada tipo de documento.

## RFCs

Uma [RFC][wiki_rfc] é um documento utilizado para propor uma idéia e obter
comentários e sugestões. A origem da sigla vem do inglês "Request for
Comments", que significa "pedido de comentários".

No âmbito da Mentoria, o objetivo de uma RFC é criar um processo colaborativo
onde todas as vozes são válidas e consideradas igualmente na tomada de
decisões. Ao agregar as vozes de várias  pessoas o resultado final será melhor
do que decisões tomadas de forma unilateral.

Por ser um processo assíncrono, a criação de uma RFC permite que pessoas que
não podem participar ativamente das reuniões da Mentoria acompanhem os
trabalhos no seu próprio tempo e colaborem nas decisões dos projetos, seguindo
a evolução das RFCs.

Para pessoas novas, as RFCs representam um ponto de entrada para entender os
projetos, o que já foi feito, o que está sendo feito e o que falta fazer. As
RFCs também permitem entender o porquê dos trabalhos estarem sendo feitos de
certa maneira.

Ter as propostas escritas em um documento também ajuda na obtenção de concenso
sobre a visão e direção dos projetos. Descrever a solução antes de
implementá-la permite que as pessoas envolvidas na RFC validem a proposta antes
mesmo de começar a escrever código. Esse exercício pode ajudar a gerar novas
ideias ou a identificar problemas e partes que estejam faltando com mais
antecedência.

As RFCs da Mentoria ficam na pasta [`rfcs`][rfcs].

### Estrutura de uma RFC

Para facilitar a leitura e escrita do documento, todas as RFCs seguem uma
estrutura base padrão. Para mais detalhes sobre cada seção consulte o [template
de RFC][rfc_template].

### Visão geral do processo

Uma RFC é criada sempre que é preciso decidir algum ponto importante de um
projeto, como a arquitetura de infraestrutura, organização de módulos e
pipelines etc.

A RFC é proposta a partir de um [pull request (PR)][glossario_pr] que qualquer
pessoa pode acessar, ler e comentar. A RFC é atualizada constantemente com base
nesses comentários até atingir um ponto onde ela esteja pronta para ser aceita.

O PR então é aceito e é realizado o merge. Apesar de o PR ser fechado depois do
merge, comentários ainda são aceitos e bem-vindos. Se, após aprovado, alguma
coisa precisar ser alterada da ideia inicial uma nova RFC pode ser criada para
descrever o que mudou e o porquê da mudança.

Por ser um processo assíncrono e voluntário, pode levar um tempo para uma RFC
ser concluída. Por conta disso, os trabalhos podem ser iniciados a qualquer
momento. Em geral, o próximo passo será criar [issues][glossario_issue] com
base na proposta e agendar reuniões de trabalho. Se houver alguma mudança
significativa na RFC os trabalhos podem ser ajustados de acordo.

### Como colaborar com uma RFC

A principal forma de colaborar com uma RFC é adicionar comentários em um PR.
Todas as pessoas são bem-vindas a participar, sem restrição do nivel de
conhecimento técnico nem de envolvimento prévio com o projeto ou a Mentoria em
si.

Uma RFC deve ser um documento auto-explicativo, ou conter links para documentos
auxíliares. Se você não conseguiu compreender alguma parte de uma RFC, coloque
uma pergunta pois isso indica que o documento não está claro o sufiente. Você
estará ajudando não só a melhorar a nossa documentação como também a responder
dúvidas que outras pessoas também tem ou terão no futuro.

Existem várias formas de comentar em um PR: comentários gerais, comentários em
uma (ou mais) linhas e sugestões. Consulte a [documentação do
GitHub][gh_pr_docs] para mais detalhes.

**Comentários gerais** são feitos em resposta à proposta em si, sem apontar
para alguma parte específica do documento. Eles podem ser, por exemplo, dúvidas
mais genéricas, como pedidos para mais referências sobre o assunto, ou elogios
à solução apresentada.

**Comentários em linhas** são feitos para iniciar uma conversa sobre uma parte
específica da RFC. O comentário pode ser uma dúvida, uma sugestão de ideia nova
ou o compartilhamento de experiências prévias.

Uma variação do comentário em linha é uma **sugestão**. Elas são feitas para
propor uma alteração específica no texto, como correção de erros ortográficos,
adição de novos conteúdos ou remoção de partes desnecessárias. Essas sugestões
podem então ser aprovadas pelas pessoas responsáveis pela RFC e serão
incorporadas ao documento.

### Como criar uma nova RFC

Uma RFC pode ser criada por qualquer pessoa. Em geral elas são criadas com o
apoio da equipe de moderação da Mentoria, mas isso não é necessário.

Os passos básicos para a criação de uma nova RFC são:

1. Crie um fork do repositório na sua conta.
2. Crie uma sub-pasta dentro da pasta `rfcs` seguindo o próxmimo número.
3. Faça uma cópia do [template][rfc_template] para a sub-pasta e renomeie o
   arquivo para o mesmo nome da sub-pasta.
4. Siga as orientações do template e escreva o texto.
5. Abra um PR para iniciar o processo de revisão.

[gh_pr_docs]: https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/commenting-on-a-pull-request
[glossario_issue]: https://github.com/mentoriaiac/glossario#issue
[glossario_pr]: https://github.com/mentoriaiac/glossario#pull-request
[rfc_template]: rfcs/.template.md
[rfcs]: rfcs
[wiki_rfc]: https://pt.wikipedia.org/wiki/Request_for_Comments
