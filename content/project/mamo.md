+++
# Date this page was created.
date = "2018-09-03"

# Project title.
title = "Desenvolvimento de um Algoritmo de Segmentação de Lesões em Imagens de Mamografia Digital"

# Project summary to display on homepage.
summary = "Este projeto tem como objetivo principal o desenvolvimento de uma nova técnica de segmentação de lesões em imagens de mamografia digital, a fim de permitir um diagnóstico mais preciso das lesões encontradas, fornecendo uma ferramenta de suporte à decisão para o médico. Têm-se como objetivo desenvolver um novo método de segmentação, reduzindo o esforço especialista e com qualidade de segmentação equivalente ou superior ao estado da arte."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "mamo.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["mammography", "segmentation", "computer vision"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "mamo.png"
caption = "teste"

+++

De acordo com a Organização Mundial de Saúde, o câncer de mama é a forma mais comum de câncer entre as mulheres no mundo todo, sendo um dos tipos de câncer mais fatal. Estudos mostram que o diagnóstico precoce pode contribuir para a redução da taxa de mortalidade e aumentar as opções de tratamento. Apesar da existência de várias técnicas de obtenção de imagens no auxílio ao diagnóstico de câncer de mama, a mamografia digital é ainda a tecno- logia mais eficaz e utilizada para esse fim. Consequentemente, a segmentação de imagens de mamografia é uma tarefa fundamental para auxiliar o diagnóstico, levando em consideração a forma da lesão mamária e suas bordas. No entanto, a segmentação de imagens de mamografia é uma tarefa complexa, uma vez que ela é muito dependente dos tipos de tecido mamário e da lesão. Métodos de segmentação baseados em semente obtém bons resultados de segmen- tação, mas são dependentes da marcação do especialista. Este trabalho trabalho visa propor um algoritmo de segmentação de lesões para auxílio ao diagnóstico médico, que requeira me- nos esforço para inicialização, obtendo bons resultados de segmentação quando comparado ao estado da arte. O método proposto busca utilizar uma função de pertinência fuzzy Gaussi- ana para modificar a regra de evolução de diferentes algoritmos do estado da arte e analizar o impacto na qualidade de segmentação. Esse modelo visa permitir uma maior flexibilidade na inicialização das sementes quando comparado à trabalhos no estado da arte, pois a marcação realizada pelo especialista será utilizada extraindo-se informação do conjunto de sementes, e não informações do posicionamento individual, como o presente nos algoritmos clássico. A abordagem desenvolvida será comparada qualitativamente e quantitativamente com técnicas de segmentação do estado da arte, usando métricas relacionadas à forma das regiões segmen- tadas. As análises serão avaliadas utilizando bases de dados públicas contendo imagens de mamografia. Espera-se que os resultados do algoritmo desenvolvido obtenha melhores re- sultados quando comparado com os algoritmos do estado da arte. Para validar a proposta, os resultados serão submetidos a um classificador e também serão validados por uma equipe médica.
