# Uma introdução ao Git e ao GitHub

Um tutorial passo a passo para o git e o GitHub.

<h3>Etapa 1. Crie o repositório</h3>

Inicialmente, o repositório que você criar no Bitbucket ficará vazio sem nenhum código nele. Tudo bem porque você começará a adicionar alguns arquivos a ele em breve. Este repositório Bitbucket será o repositório central para seus arquivos, o que significa que outras pessoas podem acessar esse repositório se você der permissão a eles. Depois de criar um repositório, você copiará uma versão para seu sistema local - dessa forma, você poderá atualizá-lo de um repositório e depois transferir essas alterações para o outro.

<h3>Etapa 2. Tutoriais avançados do Git</h3>

<h4>Merging vs. Rebasing</h4>
git mergee git rebasecomandos oferecem formas alternativas de integrar commits de diferentes branches, e ambas as opções vêm com suas próprias vantagens. Neste artigo, discutiremos como e quando uma git mergeoperação pode ser substituída por um rebase.

**Visão geral conceitual**
A primeira coisa a entender sobre **git rebase** que ele resolve o mesmo problema que **git merge**. Ambos os comandos são projetados para integrar as alterações de uma ramificação em outra ramificação - eles apenas fazem isso de maneiras muito diferentes.
Considere o que acontece quando você começa a trabalhar em um novo recurso em uma ramificação dedicada e, em seguida, outro membro da equipe atualiza o **dev branch** com novos commits. Isso resulta em um histórico bifurcado, que deve ser familiar para qualquer pessoa que tenha usado o Git como uma ferramenta de colaboração.
![Linhas temporais](img/1.png)
