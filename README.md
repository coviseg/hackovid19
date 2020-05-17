# COVISEG

## Inspiração

Com o crescimento dos casos de contaminação por COVID19 pelo mundo, formas diferentes de detectar o vírus estão surgindo. Um dessas formas é a tomografia computadorizada (PET/CT) na região do pneumotórax. A técnica já é bastante conhecida pelo mundo, porém alguns desses exames feitos em pacientes com COVID19 apresentaram alguns achados importantes, tais como: (i) opacidades em vidro fosco; (ii) consolidação pulmonar; (iii) efusão pleural.  Mesmo sendo os principais achados, muitas das vezes se tornam difíceis de detectar devido a sensibilidade do equipamento utilizado.
Nos últimos anos, temos visto uma revolução do uso de Inteligência artificial na medicina, com aplicações em diagnóstico, descobrimento de remédios, dentre outros.  Portanto,nos pareceu natural aplicar métodos de inteligência artificial para podermos segmentar as áreas de interesse para os profissionais de saúde possam avaliar com maior detalhe.

## O que faz?

Nosso software segmenta imagens de Tomografia Computadorizada para ajudar a perceber situações clínicas como derrame pleural, opacificação e consolidação em vidro fosco.


## Como construimos?

Construímos uma rede neural na arquitetura UNET que faz a segmentação de tomografias computadorizadas. 

## Desafios que encontramos

Durante o desafio, encontramos problema em como utilizar modelos consolidados de Deep Learning para o nosso propósito, no entanto encontramos um modelo que satisfaz a tarefa que necessitamos e conseguimos desenvolver o software utilizando ele.

## Conquistas que estamos orgulhosos



## O que aprendemos?

Aprendemos a segmentar imagens de Tomografia Computadorizada utilizando Deep Learning.

## O que vem a seguir COVISEG - Segmentação de imagens de TC para casos de COVID19

Além de aprimorar a rede já construída através de novos dados segmentados. Também buscamos testar arquiteturas que necessitam de menos dados para obter a segmentação, podendo melhorar a precisão do nosso software. Além disso, a rede possui potencial de ser aplicada para outros exames de imagem.
