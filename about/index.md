---
layout: page
title: Sobre o LabCidades
tags: [about, Jekyll, theme, moon]
date: 2016-03-21
comments: false
---
    
<center><a href="https://github.com/LabCidades"><b>LabCidades</b></a> é o Laboratório de Cidades Inteligentes e Gestão do Conhecimento da Universidade Nove de Julho - UNINOVE.</center>

## O LabCidades possui como objetivo elaborar pesquisas para apoio à:
* formulação de políticas públicas
* tomada de decisão

## As principais técnicas são:
* modelos estatísticos Bayesianos
* algoritmos de aprendizagem de máquina
* sistemas baseados em evidências

## Contexto de atuação:
* *Big Data*
* ferramentas open source
* *Open science*: dados e código abertos para replicabilidade e transparência

## LabCidades UNINOVE - Equipe:

### Pesquisador Responsável

{% for membro in site.mini_bios %}
    {% if membro.posicao == "responsavel" %}
* {{ membro.title }}
    {% endif %}
{% endfor %}

### Pesquisadores Associados

{% for membro in site.mini_bios %}
    {% if membro.posicao == "associado" %}
* {{ membro.title }}
    {% endif %}
{% endfor %}

### Pesquisadores Assistentes

{% for membro in site.mini_bios %}
    {% if membro.posicao == "assistente" %}
* {{ membro.title }}
    {% endif %}
{% endfor %}

### Alunos de Iniciação Científica

{% for membro in site.mini_bios %}
    {% if membro.posicao == "ic" %}
* {{ membro.title }}
    {% endif %}
{% endfor %}
