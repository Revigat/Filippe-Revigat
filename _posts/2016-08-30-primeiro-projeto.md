---
layout: post
title: O Primeiro Projeto
subtitle: Esse é o mais Power
---

Fala Pythonista Djangonistas tudo bem? rsrs esperamos que sim.
Hoje iniciarei uma série de posts que vão ensinar você a ser **poderoso** de forma intuitiva e simples, alias, simplicidade está no DNA do Python e do Django.

---

**Bora começar!**

Conceitos que é interessante saber.

  >Python é uma linguagem de programação de alto nível, interpretada, de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte... Ufaa, faltou até folego para falar tudo isso. [wikipedia](https://pt.wikipedia.org/wiki/Python)

>Django é um Framework Web Python de alto nível que incentica o desenvolvimento rápido e limpo. Criado por desenvolvedores experientes, que cuidam da maior parte do trabalho de desenvolvimento Web, para que não seja preciso reinventar a roda. [Django](https://www.djangoproject.com/).

### Abra o Terminal
Digite o comando "**pwd**" (sem aspas), este comando serve para verificar o diretório em que estamos, e é aonde nosso projeto vai ser criado.

```
sh-3.2# pwd
/Users/Revigat

```

### Criando nosso ambiente de desenvolvimento com virtualenv.

Primeiro o que é uma virtualenv ? 

É um ambiente **ISOLADO** para Python, pense como se fosse uma caixa, e dentro dessa caixa nós vamos colocar ferramentas de trabalho.

* verifique se você tem a vitualenv instaladada, execute o comando "**virtualenv --version**" (sem aspas).

```
sh-3.2# virtualenv --version
15.0.3

```

Obeserve que o meu comando retornou a versão, isso significa que eu já tenho ela instalada, se o seu não retornar a versão, execute:

* Macosx: **pip install viratualenv**.

* Ubuntu ou Debian: **sudo apt-get install python-setuptools** depois **sudo easy_install virtualenv**.

Agora que estamos com nossa virtualenv instalada, **Partiu próximo passo**.

### Criando nossa **virtualenv**.

para ciar uma **Virtualenv** execute:

* virtualenv --python=python3 primeiroambiente.
* --python (parâmetro)
* python3 (versão da linguagem)
* primeitoambiente (nome da pasta)

```
sh-3.2# virtualenv --python=python3 primeiroambiente

```




