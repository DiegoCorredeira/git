# Um pouco sobre o GIT

Na programação e desenvolvimento de software, o Git é uma ferramenta fundamental para o controle de versão de código. Para entender como o Git funciona, é importante entender os diferentes estágios pelos quais os arquivos passam durante o processo de rastreamento e versionamento.


# Estágios

  **Working Directory :** Este é o estágio inicial do seu projeto, onde você possui seus arquivos e pode edita-los, cria-los e etc...
    
  **Staging Area :** Aqui, você seleciona os arquivos que deseja incluir em seu próximo commit. Isso permite que você controle quais modificações serão registradas. A área de preparação age como uma espécie de "pré-commit," onde você organiza as alterações antes de confirmá-las.
    
  **Local Repository :** Uma vez que os arquivos estejam na área de preparação, você pode realizar um commit. Isso efetivamente salva suas alterações no repositório local. Cada commit é uma unidade de alteração que possui um histórico descritivo de suas modificações.
     **Remote Repository :** Para colaboração e compartilhamento de código com outros membros da equipe ou através de plataformas como o GitHub, Bitbucket ou GitLab, você envia seus commits para um repositório remoto. Isso permite que outros acessem, revisem e colaborem com seu código.

# Comandos Básicos
Os comandos mais básicos do GIT que os desenvolvedores precisam conhecer são: 

1.  **git init:** Este é o ponto de partida. Execute este comando em um diretório para iniciar um novo repositório Git. Ele cria uma estrutura oculta que rastreará todas as alterações em seus arquivos.
    
2.  **git clone:** Use este comando para criar uma cópia local de um repositório remoto. Basta fornecer o URL do repositório que deseja clonar, e o Git fará o trabalho para você. Exemplo de uso: ``git clone https://github.com/DiegoCorredeira/CursoREST-API.git``
    
3.  **git add:** Este comando move arquivos do seu diretório de trabalho para a área de preparação (staging area). É o primeiro passo para preparar suas alterações para um commit. Use "git add" seguido do nome do arquivo ou "." para adicionar todos os arquivos modificados.
    
4.  **git commit:** Após adicionar seus arquivos à área de preparação, você pode criar um commit com "git commit." Isso registrará suas alterações no histórico do Git, e você deve incluir uma mensagem descritiva do que foi feito. Exemplo de uso: ``git commit -m "esse é meu primeiro commit"``
    
5.  **git pull:** Para obter as atualizações mais recentes de um repositório remoto, use "git pull." Isso traz as mudanças de outros colaboradores para o seu repositório local.
    
6.  **git push:** Quando você quiser enviar suas alterações para um repositório remoto, use "git push." Isso atualiza o repositório remoto com seus commits. 
    
7.  **git status:** Para verificar o estado atual do seu repositório, use "git status." Ele mostra quais arquivos foram modificados, adicionados ou estão prontos para commit.
    
8.  **git log:** Quer ver o histórico de commits do seu projeto? "git log" exibirá uma lista dos commits anteriores, incluindo informações como autor, data e mensagem.
    
9.  **git branch:** Para listar todas as ramificações (branches) em seu repositório e destacar qual ramificação você está atualmente, utilize "git branch."
    
10.  **git merge:** Quando você deseja combinar as alterações de uma branch em outra, "git merge" é o comando a ser usado. Ele permite a fusão de duas ramificações diferentes.

## O que são branchs

Em termos simples, uma branch é uma "cópia" código do projeto em um determinado momento. Isso permite que os desenvolvedores testem e desenvolvam novos recursos sem afetar o código principal.

Por exemplo, imagine que você está trabalhando em um projeto e precisa adicionar uma nova funcionalidade. Você pode criar uma nova branch a partir do código atual (geralmente chamado de branch "main" ou "principal"). Nesse novo branch, você pode adicionar, modificar e testar o código da nova funcionalidade sem afetar o código na branch principal.

Uma vez que a nova funcionalidade esteja completa e testada, você pode mesclá-la de volta na branch principal (geralmente chamada de "merge"), incorporando as alterações ao projeto principal. Isso permite que você mantenha um histórico limpo e organizado de todas as alterações feitas ao longo do tempo.
## A importância do commit

Cada commit captura um conjunto específico de alterações no código, fornecendo um registro preciso de cada passo do desenvolvimento. vou explicar por que os commits são tão cruciais.

Primeiramente, os commits permitem um rastreamento preciso das alterações. Cada commit é como uma fotografia instantânea do estado do código em um determinado momento. Isso facilita a identificação de quando e por que uma mudança específica foi introduzida.

Além disso, os commits fornecem uma camada de segurança. Se algo der errado ou se uma alteração causar problemas inesperados, é possível voltar para um commit anterior e restaurar o código para um estado funcional. Isso evita perdas irreparáveis de trabalho.

Os commits também desempenham um papel fundamental na colaboração em equipe. Cada commit é acompanhado por uma mensagem descritiva que explica o que foi feito e por quê. Essas mensagens ajudam outros desenvolvedores a entenderem suas mudanças sem a necessidade de examinar o código em detalhes.

Além disso, os commits fazem parte da documentação viva do projeto. Eles registram decisões de design, correções de bugs, novas funcionalidades e ajustes, fornecendo contexto para o histórico de desenvolvimento. Isso é valioso para desenvolvedores futuros que precisam entender as decisões tomadas ao longo do tempo.

Os commits também são essenciais para revisões de código. Eles permitem que outros desenvolvedores revisem suas alterações de forma estruturada, garantindo a qualidade do código e identificando problemas rapidamente.


# Continua...

