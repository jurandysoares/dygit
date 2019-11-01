# Diferença

## Diferença básica
Comando: `git diff`

## Diferença de arquivos específicos

1. Verificar quais arquivos foram modificados: `git status`
2. Verificar a diferença do arquivo específico: `git status caminho/do/arquivo.ext`

Há uma maneira melhor de listar somente os arquivos modificados. O comando é: `git ls-files -m`

## Diferença entre mestre e mestre da origem
Comando: `git diff master..origin/master`

## Referências
* [is it possible to `git status` only modified files? - Stack Overflow](https://stackoverflow.com/questions/10018533/is-it-possible-to-git-status-only-modified-files)
* [How to see code changes after git pull? - Stack Overflow](https://stackoverflow.com/questions/11284350/how-to-see-code-changes-after-git-pull/12631371)
* [See changes before pulling from remote git repository · GitHub](https://gist.github.com/jtdp/5443297)

