# desafio-github-markdown

🐱 Git & GitHub Cheat Sheet: Guia de Consulta Rápida

Repositório criado como Desafio de Projeto para a disciplina de Git/GitHub e Markdown na Digital Innovation One (DIO). Este guia serve como um manual prático dos comandos mais utilizados no dia a dia de um desenvolvedor colaborativo.

👥 Integrantes do Projeto

🛠️ Comandos Básicos

git initInicializa um repositório Git local na pasta atual.
git clone <url>Clona um repositório remoto existente para a sua máquina.
git status Mostra o estado atual dos arquivos (modificados, salvos ou não rastreados).


📝 Ciclo de Vida dos Arquivos (Salvar Alterações)

Para salvar suas alterações locais e enviá-las ao GitHub, siga o fluxo de comandos abaixo:

1. Adicionar arquivos para a área de preparação (Staging):

``` bash
git add nome-do-arquivo.txt  # Um arquivo específico
git add .                     # Todos os arquivos modificados
```
2. Gravar as alterações na história do projeto (Commit):

``` bash
git commit -m "feat: adiciona comando x no cheat sheet"
```
3. Enviar as alterações para o servidor remoto (GitHub):

``` bash
git push origin main
```
------

🔀 Ramificações (Branches) e Trabalho em Equipe

Trabalhar com Branches permite que múltiplos desenvolvedores alterem o código sem interferir no trabalho uns dos outros.

Criar uma nova branch:
```bash
git checkout -b feature/nome-da-sua-tarefa
```

Listar as branches existentes:
```bash
git branch
```

Mudar de uma branch para outra:
```bash
git checkout main
```

Atualizar seu repositório local com o que está no GitHub:
```bash
git pull origin main
```







