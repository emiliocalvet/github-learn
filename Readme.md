# Git Course

git init -> Inicializa o seu repositório Git. Deve ser executado no seu diretório de trabalho.

Todo arquivo recem adicionado no repositório é unmodified.

git add <nome do arquivo> -> adiciona o arquivo para staged, para ser finalizado.
git commit -m "<mensagem>" -> leva o arquivo modificado de staged para unmodified (finaliza).
git status -> mostra quais arquivos estão em que estados no repositório.
git log -> mostra um histórico do repositório (mostra a hash do commit).
git shortlog -> mostra um histórico mais simples.
git show <hash do commit> -> mostra quais foram as alterações realizadas naquele commmit.
git diff -> mostra quais foram as atualizações realizadas antes de fazer commit.
git checkout <nome do arquivo> -> traz o arquivo de modified para unmodified (desfaz modificações).
git reset HEAD <nome do arquivo> -> traz o arquivo de staged para modified.
git reset --(soft, mixed ou hard) <hash do commit> -> traz do commit para staged, modified ou unmodified respectivamente.
