# 💻 Como transferir atualizações do repositório local para o repositório remoto 

Com o Git e o Github 💻
## 📋 Passo a passo:
Ao fazer as suas alterações no repositório local (aqui exsecutadas pelo bloco de notas) e salvas como vemos nas imagens, seguiremos o passo a passo a seguir para tranferir para o repositório remoto.

![imagem 3](https://github.com/Lai1a202/Usando-o-Git/assets/148493926/79f0df28-9244-4d56-9041-5fbcf1aafc67)


### Primeiro passo:
- Use o comando `git status` para ver as 
alterações.

![imagem 2](https://github.com/Lai1a202/Usando-o-Git/assets/148493926/8e93c301-8f8f-46ce-8277-91ac67f1ae02)


### Segundo passo:
- Use o comando` git add .` para salvar todas as alterações, como vemos nas imagens após usar o comando `git status` novamente persebemos que as alterações foram salvas.

![imagem 4](https://github.com/Lai1a202/Usando-o-Git/assets/148493926/08a0b3de-6609-4d6f-856c-d539f4bf1b51)


### Terceiro passo:
- Utilise o comando `git commit -m "imformações da sua preferencia"` para intitular as suas alterações.

![imagem 5 (2)](https://github.com/Lai1a202/Usando-o-Git/assets/148493926/f0ba01a3-b254-4195-b5c1-c0584ae7a35a)


### Quarto passo:
- Depois de ter feito o esposto acima, se você estiver trabalhando em equipe ou tiver feito alguma alteração no repositório remoto recentemente e não tiver passado as auterações para o repositório local, usar o comando `git pull origin main` antes de usar o comando `git push origin main`. Se não estiver trabalhando em equipe ou tiver feito alguma alteração no repositório remoto recentemente basta usar o `git push origin main` e todas as alterações serão transferidas para o repositório remoto.

 ![imagem 6 (2)](https://github.com/Lai1a202/Usando-o-Git/assets/148493926/f44aa3b0-8d00-42f0-87a8-cc1ec33a9812)

 
## 📘 Para mais informações acesse :
- [Documentação do Git](https://git-scm.com/doc)
