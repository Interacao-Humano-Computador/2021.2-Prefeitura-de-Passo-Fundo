# Histórico de versão

| Data | Versão | Modificação | Autor(res) |
| :- | :- | :- | :- |
| 09/02/2022 | 0.1 | Criação do documento | [Kathlyn Lara Murussi](https://github.com/klmurussi) |
| 10/02/2022 | 0.2 | Adição das referências usadas | [Kathlyn Lara Murussi](https://github.com/klmurussi) |

# Como Contribuir
<p style="text-indent: 20px; text-align: justify"> Antes de fazer qualquer alteração no repositório, crie uma issue e se responsabilize por essa alteração. Atente-se a [política de branchs](#política-de-branches) e a [política de commits](#política-de-commits). 

## Objetivo:
<p style="text-indent: 20px; text-align: justify">Critérios a serem seguidos por todos que queiram contribuir para o projeto, principalmente os colaboradores e desenvolvedores oficiais.

## Criação de Issue:
<p style="text-indent: 20px; text-align: justify"> Ao criar issues atente-se as seguintes questões:

- Já existe [issue](https://github.com/Interacao-Humano-Computador/2021.2-Prefeitura-de-Passo-Fundo/issues) referente ao assunto que você pretende abordar na sua? Se sim, trabalhe a partir da issue já criada
- Adicione um título que sintetize bem o problema abordado na issue
- Adicione uma descrição adequada, de modo que qualquer membro do repositório consiga compreender qual é o problema
- Adicione ao menos um Assignee
- Adicione as Labels adequadas
- Adicione a milestone referente a sprint em que o problema será trabalhado
- Utilize os templates de issue gerados automanticamente
- Se precisar modificar algo no repositório, criar uma branch para resolver a issue


## Política de Branches

<p style="text-indent: 20px; text-align: justify"> A partir das branches que serão resolvidas as issues e criados artefatos para serem adicionados ao projeto principal, após revisões.

### Padronização das Branches

#### Prefixos:
- [Main](#main)
- [Features](#features)
- [Doc](#documentation)

#### Formato:
```
<prefixo>#número da issue/assunto
```

Não esquecer de dividir as palavras(sempre minúsculas) do assunto com "-".
Exemplo: 
```
feature#87/novo-menu
```


### Main

**Existe somente uma branch Main!** Essa branch contém o projeto em seu estado mais estável. É nessa branch que deve-se ter todos os arquivos antes de alguma release. Quando alguma funcionalidade é implementada, deve ser feito um pull request para essa branch, que será analisada pelo colaborador responsável. Nenhum colaborador é autorizado a fazer commits diretamente na *main.*

### Features

Como o nome já diz, são branches na qual são desenvolvidos novos recursos ao projeto. São criadas começando com o prefixo **feature/**.
Comando de exemplo sobre criar uma branch desse tipo:

```git
git branch feature#22/novo-layout
git checkout feature#22/novo-layout
```

ou ainda

```git
git checkout -b feature#22/novo-layout
```

### Documentation

Branches na qual são desenvolvidos os documentos do projeto. São ciradas começando com o prefixo **doc/**.
Comando de exemplo sobre criar uma branch desse tipo:

```git
git branch doc#32/documento-de-visao
git checkout doc#32/documento-de-visao
```

ou ainda

```git
git checkout -b doc#32/documento-de-visao
```

#### Template
Os documentos deverão seguir o seguinte modelo:

```
# Histórico de versões

| Data | Versão | Modificação | Autor(es) |
| :--: | :----: | :-------: | :-------: |
|      |        |           |           |
|      |        |           |           |

***Todos documentos devem ter seus autores registrados.

# 1. Introdução
Porque esse documento está sendo escrito e sobre o que é ele.

# 2. Tópico 1

# 3. Tópico 2

...

# 100. Referências

- As referências devem estar em formato ABNT.
```

## Política de Commits

Os commits são essenciais para acompanharmos as alterações e adições ao projeto. 

Deve ser usado o modo imperativo (ações e ordens assertivas) para mencionar o que foi feito.

Sempre dividir em pequenos e significativos commits, fazendo com que cada commit tenha apenas uma funcionalidade.


### Formato
```
#numero-da-issue/mensagem
```

Comando de exemplo sobre como fazer um commit:

```git
git commit -m "#32/documento-de-visao"
```


## Política de Pull Request
Para unir branches a main, devemos fazer um PR (Pull Request), indicando sobre o que é, o que foi feito, revisores e qual issue(s) será cumprida através do Merge.

### Príncipios
Nunca dar merge no seu próprio PR, espere outra membro da equipe revisar e aprovar

Utilizar o template disponível no repositório

Lembrar de linkar o PR na issue

# Referências

Guia de Contribuição. Disponível em: <https://github.com/fga-eps-mds/2021.1-AlligaBot/blob/main/docs/_posts/2021-08-16-como-contribuir.md>. Acesso em: 09 de jan. de 2022

Políticas de Branches. Disponível em: <https://github.com/fga-eps-mds/2021.1-AlligaBot/blob/main/docs/_posts/2021-08-19-branches.md>. Acesso em: 09 de jan. de 2022

Políticas de Commit. Disponível em: <https://github.com/fga-eps-mds/2021.1-AlligaBot/blob/main/docs/_posts/2021-08-18-commits.md>. Acesso em: 09 de jan. de 2022

PORTO, Patrick - 4 branching workflows for Git. Disponível em: <https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf>. Acesso em: 10 de jan. de 2022

GitHub Flow. Disponível em: <https://docs.github.com/en/get-started/quickstart/github-flow#following-github-flow>. Acesso em: 10 de jan. de 2022
