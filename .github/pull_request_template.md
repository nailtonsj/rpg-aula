Copie o texto do bloco abaixo para o arquivo .github/pull_request_template.md do repositório do squad (crie a pasta .github na raiz, se ainda não existir). A partir do merge, todo PR novo abre com a descrição já preenchida.

O squad ainda não tem o modelo? git switch main · git pull · git switch -c docs/modelo-pr · crie o arquivo com o texto · git add .github/pull_request_template.md · git commit -m "docs: modelo de pull request" · push, PR, revisão e merge.
Já tem o modelo antigo? Troque o texto pelo de baixo numa branch docs/modelo-pr-npm-test, commit docs: modelo de PR com npm test, PR, revisão e merge.

## O que muda

(uma ou duas frases: o que este PR faz no jogo)

## Cartão do Trello

(link do cartão)

## Como testar

1. git fetch e git switch nome-da-branch
2. npm test (termina com "Tudo certo.")
3. Jogando, confira também: (digite ... e veja ...)

## Checklist do autor

- [ ] npm test passou
- [ ] Pus no teste.js uma frase nova do que este PR faz (se mudou o jogo)
- [ ] Mexi só no que o título diz
- [ ] Commits com tipo(escopo): mensagem
