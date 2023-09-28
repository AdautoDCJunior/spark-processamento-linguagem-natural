![Badge](https://img.shields.io/badge/Status_curso-Em_andamento-red)

# Problema ❗

Nós trabalhamos na empresa Alura Movies e recebemos uma solicitação para analisar os depoimentos sobre os filmes da plataforma e classificá-los.

Para resolver esse problema, a ideia é utilizar técnicas de Processamento de Linguagem Natural (PLN) com o objetivo de determinar se os depoimentos são de natureza positiva ou negativa.

# Proposta 🎯

Nossa proposta para esse problema é criar um modelo de linguagem natural capaz de fazer a classificação entre depoimentos positivos e negativos.

Para isso, vamos utilizar uma base de dados que nos foi disponibilizada, contendo frases em inglês, suas respectivas traduções em português, e a indicação se a frase é de natureza positiva ou negativa. Você pode fazer o download da base de dados através do seguinte [link](https://www.kaggle.com/datasets/luisfredgs/imdb-ptbr).

Utilizaremos o PySpark para fazer isso, principalmente o modo Spark DataFrame SQL e o MLlib. Com essa ferramenta faremos todo o pipeline da linguagem natural, passando pela etapa de tratamento dos dados, ajuste dos modelos, otimização e, por fim, a validação dos modelos.

Ao final do pipeline, entregaremos um modelo capaz de classificar novos depoimentos como frases positivas ou negativas.
