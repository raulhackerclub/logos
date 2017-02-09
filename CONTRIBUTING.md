# Como contribuir com nosso Repo de artes

A maneira mais simples de guardar as imagens do Raulzito é enviando pra esse repositório.
Se as artes estiverem em algum modelo aberto pra edição como SVG, EPS, AI, PSD é mellhor paras as futuras edições dos eventos.

Mas se tiver apenas em PNG ou JPG, nos envie também, pois serve como referência para novas criações!!

## Instalando git

Para nos enviar as imagens você precisa ter o git, se estiver usando uma distribuição .deb(Debian, Ubuntu, Mint, Elementary...):

```
sudo apt-get install git

```


## criando chave ssh


```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

```

 1. Isso vai criar sua chave e a label será seu email.

 2. Aperta enter para confirmar o local, e depois só escolher a senha e confirmar.

 3. Depois é só adicionar na sua conta do github.


## Clonando nosso repósitorio

 1. Primeiro você da um fork em nosso repositório (clicando em fork).
 2. Depois é só clonar o repo em sua máquina. Não esquece de trocar onde tem "seunick" para o seu nick :D

```
git clone git@github.com:seunick/logos.git
``` 

## Fazendo modificações ou adcionando algo novo

 1. Entre na pasta
 2. Edite o que quer editar ou adcione sua nova imagem dentro da sua categoria e na pasta do tipo de arquivo.
 3. Use o comando git status para ver sua modificações

```
 git status

```
 4. Add essas alterações para serem comitadas.

```
git add --all

```

 5. Depois é só comitar e descrever a modificação

```
git commit -m "Aqui vai sua descrição"
```

 6. E empurrar pra seu repósitorio remoto

```
git push origin master
```

 7. Feito isso é só enviar um PR clicando em Pull request no seu repo remoto na página do GitHub.

 8. Espere pelo merge de alguém ou sugestão de melhoras!
