
# **Predição de Risco de de Reincidênca Criminal**  

***

<table>

<td>

## **Detalhes do modelo**

***

**Descrição**: 
- Modelo desenvolvido para a disciplina de Aprendizado de Máquina Ético da Universidade Estadual de Campinas.
 
**Desenvolvedores**: 
- Bruno S. Martins, Guilherme P. Corrêa, Igor K. I. O. Nakashima
 
**Versão**: 
- 1.0

**Caso de Uso**: 
- Estimativa de risco de reincidência criminal para ex-detentos do estado de Santa Catarina por parte de organizações não governamentais.
- Alocação de recursos para a reintegração de indivíduos com maior possibilidade de reincidência criminal.
 
**Fora de Escopo**: 
- Esse modelo não deve ser utilizado para casos de uso
que representam grandes riscos a liberdade ou bem estar de indivíduos. 
- Não deve ser utilizado dentro do ambiente jurídico ou influenciar em possíveis reduções ou aumentos na pena de cada indivíduo.

**Fatores**:
- Os fatores envolvem possíveis riscos para grupos específicos de pessoas com base em gênero, cor de pele e educação. 
 
**Métricas**:
- A principal métrica escolhida para o modelo foi o Recall. Isso se deve ao fato de que o modelo se destina a reintegração de pessoas por parte de organizações não governamentais,
de modo que se usado adequadamente, esse modelo não deve causar danos a indivíduos.

**Dados de Avaliação**:
- Avaliado com dados particionados do dataset original. Aproximadamente 25% dos dados foram utilizados para teste.

**Dados de Treinamento**:
- O modelo foi treinado com aproximadamente 75% das amostras do dataset original.

**Arquitetura**: 
- Regressão Logística calibrada e com hiperparâmetros escolhidos para maximizar o Recall.

**Data de Criação**: 
- 08 de Novembro de 2023.

**Informações de Contato**: 
- Em caso de dúvidas ou questionamentos, qualquer um 
dos autores do trabalho pode ser contactado.
 
**Pegada de Carbono**: 
- Treinado diversas vezes utilizando a plataforma colaborativa google colab.

**Dados de Treinamento**: 
- O classificador foi treinado utilizando o conjunto de dados 
"Reincidência Criminal por Gênero em Santa Catarina", disponibilizado pela 
Universidade Federal de Santa Catarina.

**Métricas Avaliadas**: 
- Utilizamos o Recall como principal métrica de avaliação. 
Desse modo, todos os hiperparâmetros do modelo foram otimizados para 
maximizar essa métrica.

**Resultados de Avaliação**: 
- O modelo apresentou 64% de Recall no conjunto de 
teste utilizado. 
 
</td>

<td style="vertical-align: top">

## **Análise Quantitativa**
***

<img src="./assets/recall_per_group.png" style="margin-bottom: 35px">

<img src="./assets/precision_per_group.png">

## **Considerações Éticas e Limitações**

***

**Utilização Jurídica**: 
- O modelo visa apoiar instituições no fornecimento de serviços de ressocialização, não sendo destinado à tomada de decisões judiciais. Isso minimiza preocupações éticas relacionadas a influências indevidas no sistema jurídico.

**Diversidade Geográfica**:

- O modelo pode não se comportar bem ao ser aplicado a dados de regiões geográficas distintas daquelas em que foi originalmente treinado.

**Temporalidade**:

- A performance do modelo pode ser reduzida com o passar tempo devido a mudanças não previstas nos dados utilizados, como por exemplo a pandemia de COVID-19.

</td>

</table>
