
# **Predição de Risco de de Reincidênca Criminal**

<table>

<td style="vertical-align: top">

## **Detalhes do Modelo**

**Desenvolvedores**: Bruno S. Martins, Guilherme P. Corrêa, Igor K. I. O. Nakashima

**Entrada**: Vetor de *features* 

**Saída**: Rótulo binário ou probabilidade 

**Arquitetura**: Regressão Logística calibrada e com hiperparâmetros escolhidos <br>
para maximizar o Recall.

**Data de Criação**: 08 de Novembro de 2023.

**Informações de Contato**: Em caso de dúvidas ou questionamentos, qualquer um <br>
dos autores do trabalho pode ser contactado.
 
**Caso de Uso**: Organizações não governamentais e assistentes sociais <br>
interessadas pela reinserção de ex-detentos na sociedade. 

**Fora de Escopo**: Esse modelo não deve ser utilizado para casos de uso <br>
que representam grandes riscos a liberdade ou bem estar de indivíduos. 

**Pegada de Carbono**: Treinado diversas vezes utilizando a plataforma colaborativa <br> google colab.

**Dados de Treinamento**: O classificador foi treinado utilizando o conjunto de dados <br>
"Reincidência Criminal por Gênero em Santa Catarina", disponibilizado pela <br>
Universidade Federal de Santa Catarina.

**Métricas Avaliadas**: Utilizamos o Recall como principal métrica de avaliação. <br>
Desse modo, todos os hiperparâmetros do modelo foram otimizados para <br>
maximizar essa métrica.

**Resultados de Avaliação**: O modelo apresentou 64% de Recall no conjunto de <br>
teste utilizado. 

## **Considerações Éticas e Limitações**

**Utilização Jurídica**: Existem sérios problemas associados a utilização desse <br>
modelo dentro do contexto jurídico. 

</td>

<td style="vertical-align: top; width: 400px; text-align: center">

## **Análise Quantitativa**

<img src="./assets/recall_per_group.png" style="margin-bottom: 30px">

<img src="./assets/precision_per_group.png">

</td>

</table>