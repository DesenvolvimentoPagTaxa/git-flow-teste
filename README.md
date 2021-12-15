# git-flow-teste
Testando git flow

# Para começar
```sh
brew install git-flow
```
- Configurar repositório git flow
```sh
git flow init
```
- Criar feature branch no git flow
```sh
git flow feature start "nome_branch"
```
- Integrar feature branch para develop
```sh
git flow feature finish "nome_branch"
```
- Criar release/tag branch baseado no develop
```sh
git flow release start 0.1.0
```
- Fechar/integrar branch e criar o tag
```sh
git flow release finish 0.1.0
```
- Criar hotfix branch baseado no master
```sh
git flow hotfix start 0.1.1
```
- Fechar/integrar branch e criar o tag
```sh
git flow hotfix finish 0.1.1
```
To check tag
```sh
git tag
```
To push tag
```sh
git push origin "nome_tag"
```
