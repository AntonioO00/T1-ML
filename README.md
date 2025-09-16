# **Classificação de cliente do Banco**
Este notebook realiza um estudo de classificação usando o dataset Bank Marketing (da UCI Machine Learning Repository). O objetivo é prever se um cliente irá ou não aderir a um depósito a prazo com base em variáveis socioeconômicas e de campanhas de marketing.


**Tecnologias utilizadas:**
  - Python 3  
  - Pandas — manipulação de dados  
  - NumPy — operações numéricas  
  - Matplotlib — visualização  
  - Scikit-learn — pré-processamento e algoritmos de Machine Learning  
Dataset:
  - [Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)
  - A variável alvo (y) indica se o cliente aderiu ao produto:  
      yes → 1 (aderiu)  
      no → 0 (não aderiu)
       
**Como executar:**
- Baixe o arquivo no seu computador
- Faça upload do notebook no Google Colab
- Instale as dependências
  ```
  pip install pandas numpy matplotlib scikit-learn
  ```
- Execute o notabook no botão "Excutar tudo" ou rode célula por célula (Shift+Enter)

**OBS:** 
- O dataset é desbalanceado (mais respostas "não"), o que pode afetar a performance dos modelos.  
- Podem ser testadas técnicas de balanceamento (ex: SMOTE) ou ajuste de hiperparâmetros para melhorar resultados.  
- Este notebook é didático, mostrando desde a análise inicial até a comparação entre modelos clássicos de classificação.
