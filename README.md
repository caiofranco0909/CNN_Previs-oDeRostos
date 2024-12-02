# CNN para Previsão de Rostos
Projeto Referente à Unidade 10 da Trilha de Ciência de Dados do ResTIC36, Grupo 2.

## Objetivo do Projeto
Este projeto busca classificar imagens faciais como sendo de rostos masculinos ou femininos utilizando redes neurais convolucionais (CNNs). A abordagem inclui a aplicação de diferentes métodos de pré-processamento de imagens, como conversão para preto e branco e data augmentation, além de ajustes de hiperparâmetros com ferramentas especializadas. O objetivo principal é avaliar a eficácia das técnicas aplicadas e compreender como diferentes preprocessamentos afetam o desempenho do modelo, medido através de métricas como Acurácia, F1-Score e AUC-ROC.

## Requisitos de Software
Python (versão 3.8 ou superior)

## Dependências:

tensorflow

numpy

matplotlib

pandas

keras-tuner

## Dataset
Utilizamos o CUHK Face Sketch Database (CUFS), disponível no Kaggle.

## **Como Executar no Google Colab**

### **Passo a Passo**
1. **Acesse o Notebook**:
    - Abra o Google Colab e importe o notebook utilizando o link do repositório ou faça upload manual do arquivo `Unidade_10_Restic.ipynb`.
  
2. **Instale Dependências**:
    - Execute a célula que contém o código para instalar as bibliotecas necessárias no ambiente do Colab
  
3. **Execute o Notebook**:
    - Siga as células sequencialmente para realizar as análises.
---
## **Estrutura dos Arquivos**

- O arquivo Unidade_10_Restic.ipynb é o notebook que deve ser aberto no Google Colab
- O arquivo Relatório_CNN___Previsão.pdf se refere ao Relatório do Projeto

## Principais Conclusões
  Melhor Desempenho: Imagens em preto e branco apresentaram os melhores resultados entre as abordagens testadas.
  
  Impacto do Data Augmentation: Apesar de esperado um ganho significativo, ele teve um impacto menor que a conversão para preto e branco.
## Análise de Erros:
  Mulheres com cabelos curtos ou presos frequentemente foram classificadas como homens.
  
  Crianças também tiveram maior taxa de erro devido ao desequilíbrio das classes no dataset.
## Limitações
  Desequilíbrio de Classes: A quantidade desigual de imagens masculinas e femininas impactou a generalização do modelo.
  
  Simplicidade da Arquitetura: A arquitetura utilizada, propositalmente simples, pode ser melhorada com camadas adicionais ou técnicas como Dropout e Batch Normalization.
  
## Melhorias Futuras
Aprimoramento da Arquitetura: Experimentar modelos mais complexos, como ResNet ou EfficientNet.

Diversidade do Dataset: Incluir conjuntos de dados mais variados e balanceados.

Técnicas Avançadas: Implementar equalização de histograma e Grad-CAM para maior interpretabilidade e desempenho.

## **Autores e Colaboradores**

- **Caio Franco e Camilo Alves Mascarenhas**

Se você tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato!
