+++
# Date this page was created.
date = "2018-09-03"

# Project title.
title = "Desenvolvimento de um Algoritmo para Contagem Automática de Cromossomos"

# Project summary to display on homepage.
summary = "Este projeto tem como objetivo principal desenvolver um sistema para segmentar, classificar e realizar con- tagem automática de cromossomos. O projeto visa acelerar e melhorar precisão da análise de cromossomos, a qual é feita de forma manual em laboratórios de Pernambuco. O projeto tem como objetivo fornecer uma ferramenta de auxílio ao profissional, melhorando a qualidade e eficácia dos diagnósticos realizados."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "cromo.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["cromosome", "segmentation", "computer vision"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

O estudo dos cromossomos, de sua estrutura e herança é chamado de Citogenética. A Citogenética tem papel importante na medicina, pois os genes codificados no DNA têm influência sobre características e estado de saúde das pessoas, tornando a análise dos cromossomos um importante procedimento para o diagnóstico. Anormalidades citogenéticas são manifestadas como a presença de cromossomos extras ou menor do que a normal, que são de 23 pares de cromossomos para célula humana [2]. Esta análise pode identificar várias anomalias associadas a alterações na estrutura dos cromossomos, tais como síndrome de Down (indivíduo apresenta 47 cromossomos) ou de Turner (quando há apenas um cromossomo sexual ou o segundo apresenta deformação) [3]. Além disso, essa análise pode ser utilizada para a identificação de vários tipos de câncer, através da contagem de aberrações cromossômicas, e é essencial no diagnóstico pré-natal, permitindo o tratamento da criança ainda dentro do útero.


O trabalho proposto é parte de um projeto desenvolvido em parceria com o Centro Regional de Ciências Nucleares do Nordeste (CRCN - NE), um instituto da Comissão Nacional de Energia Nuclear (CNEN) que atua no desenvolvimento e aplicação de tecnologias nucleares e correlatas nas regiões Norte e Nordeste.Atualmente, no CRCN, o processo de análise cromossômica é feito manualmente, ou seja, um especialista por meio de um microscópio óptico analisa ao menos 1000 lâminas por cada amostra irradiada.

O processo de contagem automática de cromossomos tem um impacto importante: primeiramente, o pro- cesso irá reduzir o tempo de seleção manual dos cromossomos na imagem, e por consequência, irá eco- nomizar tempo de processamento e análise de imagens de cromossomo para propósitos de segmentação e classificação. O trabalho proposto visa desenvolver um algoritmo para realizar a contagem automática de cromossomos, fornecendo uma ferramenta de auxílio ao médico, permitindo um diagnóstico mais rápido e preciso. O trabalho inicialmente desenvolvido com o CRCN poderá ser estendido a outros órgãos nacionais.
