# Manual-Git
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/261cfbed-5cc7-4418-b7fe-055e414417e7)

Um guia prático e rápido pra utilizar Git.

# O que é Git?
Git é um sistema de controle de versões distribuído.
Usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.
Por meio dele podemos desenvolver um único projeto para que toda equipe trabalhe sobre ele, tudo organizado com ramificações.

## Utilização
O Git guarda regsitros de versão com snapshots(fotos) de um estado de um projeto.
Grande parte das operções feitas são locais e praticamente instantâneas.

Estados de um projeto no Git:
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/bb3d1053-8b04-4abe-b163-b1bcabd00957)

Site oficial:
https://www.git-scm.com

Documentação oficial:
https://www.git-scm.com/docs

# Comandos básicos

## git init
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/4af40edb-e5b2-4bda-9d17-544b20fe1f00)

Inicializa um repositório git dentro da pasta.

## git clone
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/32587009-8d54-4e96-b35e-ad86aea4f05b)

Clona um repositório, com o seu histórico.
Geralmente usado como:

- git clone -link HTTPS-

## git status
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/ce5d63cd-365e-48f0-b23d-3c9a6430b852)

Checa o status atual da branch que está sendo trabalhada.

## git add
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/371ca424-cb3e-4da6-a42b-d7aa05e1c0ab)

Adiciona uma alteração de arquivos para Staged Changes(mudança sem commit).
Geralmente usado como:

- git add .
(todas as alterações)

- git add .\path
(alterções num único arquivo)

## git diff
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/85c1f120-f57b-4559-a9e4-e7db23b5d694)

Checa as diferenças em relação a commits e/ou branch que estão sendo trabalhadas.

## git commit
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/bf5f8d55-670e-4d47-b375-cf66046c64c1)

Cataloga mudanças em um repositório.
Geralmente usado como:

- git commit -m "Nome da alteração"

## git log
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/e087102c-a4ba-431d-a520-0abe1aa55cdc)

Mostra os úttimos commits que foram feitos.

## git restore
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/dff86039-39fa-4761-92e6-c80d5b0da3b1)

Retornar arquivos modificados, para voltarem ao estado que está na branch.
Podem trazer um arquivo de: 
- staged chnages para changes(git restore --staged .\nomeArquivo)
- changes para original

## git push
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/c8d1c6b5-6b80-4d4b-a6d8-dd1f4818d58a)

Empurra um arquivo para a branch.
Geralmente usado como:
- git push
- git push origin -nome da branch-

## git pull
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/5113b73c-5bd9-46e9-8604-9e399cfd74b0)

Puxa os arquivos de uma determinada branch, ele faz um merge automático.
Geralmente usado como:
- git pull
- git pull origin -nome da branch-
 
## git fetch
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/dbe09712-8f02-4635-9307-93ac95fa57b1)

Baixa tudo que está no repositório remoto.

## git branch
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/6b52cdb5-596a-4708-be7b-e7c1d74fbfa0)

Cria um branch.
Geralmente usado como:
- git branch -nome da branch-
  
## git checkout
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/fb0bc6af-2750-4480-a1b0-e9905908bd20)

Alterna a atual branch.
Geralmente usado como:
- git checkout -nome da branch-

## git merge
![image](https://github.com/thiagodouradof/manual-git/assets/165097038/e0571192-c798-4861-bed8-ae6966333ebc)

Mescla uma branch com outra, muito utilizado quando se quer colocar algo na master.
Geralmente usado como:
- git merge -nome da branch-




