## Como instalar o GIT ⚙

Primeiramente, você precisará baixá-lo através do site 👉🏻 [Git](https://git-scm.com/downloads)
![App Screenshot](/images/git.png)

Depois de baixá-lo, é hora de configurarmos em nosso PC.


![Abrindo](/images/opengit.png)

Clique com o botão direito do mouse em qualquer parte da sua área de trabalho e selecione em "Git Bash Here". Um terminal abrirá e é nele que iremos configurar algumas informações essenciais.


Utilizaremos a função abaixo para definir o nosso nome:

```bash
  git config --global user.name "Escreva aqui o seu nome"

```

Agora iremos definir o nosso e-mail ao Git:
```bash
  git config --global user.email "Informar o seu e-mail"
```

Utilizamos "global", pois queremos que essas informações sejam registradas globalmente, ou seja, em todo o nosso sistema. 

É possível também indicar qual será o editor de código utilizado:

```bash
git config --global core.editor "informar nome do editor utilizado"

```

Após realizarmos essas configurações, é possível verificar se tudo está corretamente cadastrado:

Nome / E-mail / Editor
``` bash
git config user.name

git config user.email

git config core.editor

```

Também é possível ver todas as configurações registradas:

``` bash
git config --list

```


Agora temos os principais registros no Git e poderemos seguir para as próximas etapas. Caso queira conhecer outras configurações, basta utilizar o seguinte comando no terminal:

``` bash
git config

```

[Menu Principal](/README.md)