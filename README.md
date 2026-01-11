# Nome do Projeto: Tech Challenge - Modelo de Classificação

**Objetivo:** Ecrever aqui

## Equipe
* Marcelo Mendonça Lira - RM369892
* Stefanie Barcelos de Franco - RM369893

## Link do Dataset
https://www.kaggle.com/datasets/shashwatwork/cerebral-stroke-predictionimbalaced-dataset

## Objetivo
Considerando que, no contexto de AVC, a maioria dos atendimentos resulta em diagnóstico negativo, 
o modelo de IA será orientado prioritariamente à identificação de pacientes com baixa probabilidade 
de AVC. Essa abordagem visa otimizar a triagem clínica, reduzindo a fila de espera para os casos 
com maior suspeita e, consequentemente, agilizando o acesso aos exames de 
imagem — Tomografia Computadorizada (TC) e Ressonância Magnética (RM) de Crânio — para 
os pacientes com maior risco.

## Análise dos Gráficos (Insights para o Modelo)
Idade (Age): É o preditor mais forte. Note que o pico de AVC (laranja) ocorre a partir dos 60 anos, 
enquanto os casos negativos estão distribuídos em todas as idades.

Glicose (avg_glucose_level): Há uma distribuição bimodal. O segundo pico de glicose alta (>200) mostra 
uma concentração proporcionalmente maior de casos de AVC.

Desbalanceamento: O gráfico de "hypertension" e "heart_disease" mostra que, embora essas condições 
aumentem o risco, a vasta maioria da sua base não as possui e não teve AVC. Isso pode fazer com que 
modelos simples "ignorem" quem tem hipertensão por falta de exemplos positivos suficientes.

## Como executar o projeto
**Baixar via Https**
https://github.com/StefanieFranco/ML-Classification-Stroke.git
**Baixar via git**
git@github.com:StefanieFranco/ML-Classification-Stroke.git
pip install -r requirements.txt

## Resultados Obtidos
