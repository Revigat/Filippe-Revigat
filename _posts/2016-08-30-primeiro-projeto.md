---
layout: post
title: O Primeiro Projeto - Parte 1
subtitle: É muito massa
---

Fala Pythonista Djangonistas tudo bem? rsrs esperamos que sim.
Hoje iniciarei uma série de posts que vão ensinar você a ser **poderoso** de forma intuitiva e simples, aliás, simplicidade está no **DNA** do Python e do Django.

---

**Bora começar!**

Conceitos que é interessante saber.

  >Python é uma linguagem de programação de alto nível, interpretada, de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte... Ufaa, faltou até folego para falar tudo isso. [wikipedia](https://pt.wikipedia.org/wiki/Python)

>Django é um Framework Web Python de alto nível que incentiva o desenvolvimento rápido e limpo. Criado por desenvolvedores experientes, que cuidam da maior parte do trabalho de desenvolvimento Web, para que não seja preciso reinventar a roda. [Django](https://www.djangoproject.com/).

### Abra o Terminal
Digite o comando "**pwd**" (sem aspas), este comando serve para verificar o diretório em que estamos, e é aonde nosso projeto vai ser criado.

```
sh-3.2# pwd
/Users/Revigat

```

### Criando nosso ambiente de desenvolvimento com virtualenv.

Primeiro o que é uma virtualenv ? 

É um ambiente **ISOLADO** para Python, pense como se fosse uma caixa, e dentro dessa caixa nós vamos colocar ferramentas de trabalho.

* verifique se você tem a vitualenv instalada, execute o comando "**virtualenv - -version**" (sem aspas).

```
sh-3.2# virtualenv --version
15.0.3

```

Obeserve que o meu comando retornou a versão, isso significa que eu já tenho ela instalada, se o seu não retornar a versão, execute:

* Macosx: **pip install virtualenv**.

* Ubuntu ou Debian: **sudo apt-get install python-setuptools** depois **sudo easy_install virtualenv**.

Agora que estamos com nossa virtualenv instalada, **Partiu próximo passo**.

### Criando nossa **Virtualenv**.

para criar uma **Virtualenv** execute:

* virtualenv - -python=python3 primeiroambiente.
  * **- -python** (parâmetro)
  * **python3** (versão da linguagem)
  * **primeiroambiente** (nome da pasta)

```
sh-3.2# virtualenv --python=python3 primeiroambiente

```

Se tudo ocorrer bem você terá algo como

```
virtualenv --python=python3 primeiroambiente
Running virtualenv with interpreter /usr/local/bin/python3
Using base prefix '/Library/Frameworks/Python.framework/Versions/3.5'
New python executable in /Users/Revigat/primeiroambiente/bin/python3
Also creating executable in /Users/Revigat/primeiroambiente/bin/python
Installing setuptools, pip, wheel...done.

```

Yeeeeh ! já estamos como nosso ambiente criado, que tal pegar um café? depois **Partiu próximo passo!**.

Para que seja possível trabalhar, devemos **ativar** nossa virtualenv e para ativa-lá devemos estar dentro da pasta criada(primeiroambiente) anteriormente.

Execute: "**cd primeiroambiente**" depois verifique se deu certo, com o comando: "**pwd**". (ambos sem aspas).

Se tudo ocorrer bem, você verá algo como.

```
sh-3.2# cd primeiroambiente/
sh-3.2# pwd
/Users/Revigat/primeiroambiente
sh-3.2#

```

Dentro da pasta que criamos é importante verificar se contém alguns arquivos, para fazer isso execute: "**ls**"

```

sh-3.2# ls
.Python			bin			include			lib			pip-selfcheck.json
sh-3.2# 

```

Se você viu os mesmos arquivos, está no caminho certo! **Partimos ativar nosso ambiente**

### Ativando a Virtualenv

Para ativar é muito simples, basta executar: "**source bin/activate**" 

O que define se o ambiente está ativo ou não é os parenteses envolvendo o nome do ambiente criado.


```

sh-3.2# source bin/activate
(primeiroambiente) sh-3.2


```

**Ufaaaaaa, quanta coisa hein. Se você chegou até aqui está de parabéns!**

**Se ficou com dúvida ou não conseguiu executar o passo a passo, fique a vontade para perguntar, eu aprendo ensinando, então ensinar pra mim vale muito** 

Best Regards,

Filippe Revigat
