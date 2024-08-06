# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

## <hl> Descrição do Projeto </hl>
Neste Projeto, trabalhamos com um dataset especialmente desenvolvido para atender a necessidades inclusivas. Utilizamos o ChatGPT para gerar um dataset que é acessível a deficientes visuais. Esse dataset foi criado com a intenção de não apenas otimizar a gestão de inventário, mas também garantir que as informações sejam inclusivas e acessíveis a todos.
## Desafio Proposto
 A criação de um sistema de previsão de estoque inteligente utilizando Machine Learning No-Code com o Amazon SageMaker Canvas
## Objetivo
O propósito é construir um modelo preditivo que melhore a gestão de estoque, antecipando a demanda futura e ajudando a evitar problemas como excesso ou falta de produtos. A utilização do SageMaker Canvas permite a construção e treinamento de modelos de Machine Learning sem a necessidade de codificação, tornando o processo mais acessível e eficiente.


## 🚀 Passo a Passo

### 1. Construindo o Dataset Inclusivo
#### Esta etapa foi executada usando o ChatGpt
![Captura de tela novo](https://github.com/user-attachments/assets/5921ef49-af53-4d0c-868b-ca01667c6046)

#### Apartir do Programa abaixo, foi gerado o DASET e salvo em CSV e usado no SageMaker
![Captura de tela 2024-08-05 224430](https://github.com/user-attachments/assets/df00e36f-e577-4973-a8d6-57abd3f9999d)


### 2. Construindo e Treinando

-   Importado o dataset no SageMaker Canvas.

    ![Captura de tela build2](https://github.com/user-attachments/assets/e3111c25-c018-4723-9d38-d14715e7e5a3)


-   Configurado as variáveis de entrada e saída de acordo com os dados.

  ![Captura de tela predit](https://github.com/user-attachments/assets/d7c03acd-0332-4a2f-9bbe-c75b74de9b16)



### 3. Analise

-   As métricas e performance do modelo não foram Satisfatórias. RMSE e MSE não se aproximaram de zero

![Captura de tela analise](https://github.com/user-attachments/assets/30addf09-5d87-4b46-84c2-9016b0aed071)

## RMSE e MSE não se aproximaram de zero

![Captura de tela 2024-08-04 234925](https://github.com/user-attachments/assets/134ccc7e-717f-415b-8e55-185367b4d351)
 

## Na tentativade  ajustes no modelo para obter um desempenho satisfatório, fiz outro Dataset com mais uma coluna ( Preços )

![Captura de tela novo3](https://github.com/user-attachments/assets/96c6e3da-82ad-4f25-ac4e-0a22b8db6563)


![Captura de tela novo4](https://github.com/user-attachments/assets/2e9f3981-69f9-443a-8c7b-817ed90f7bd5)

  ### As métricas e performance do modelo  foram Satisfatórias. Os Valores de RMSE e MSE estão próximos de zero
  
![Captura de tela n6](https://github.com/user-attachments/assets/0565d6c7-f1e0-4125-aa17-f156ab5a128f)



### 4. Previsão

 ## Ao Testar modelo treinado para fazer previsões de estoque no primeiro Dataset Gerado, meu tempo de uso na Plataforma da AWS expirou.

 ![Captura de tela 2024-08-05 234115](https://github.com/user-attachments/assets/5b6290bc-dff7-4546-aff0-d7cbb7f66f7f)

 ## Falha na previsão 
O uso da sua conta da AWS para a instância de transformação 'ml.m5.4xlarge' atingiu seu limite, e você está solicitando 1 instância adicional. Entre em contato com seu administrador para aumentar a cota da sua conta. Se você for um administrador ou um usuário individual, use o console do AWS Service Quotas para solicitar um aumento para a cota 'Número máximo de instâncias'.
Se você continuar a ver esse problema, entre em contato com o suporte da AWS e forneça o seguinte código: <f5759813-ff6f-4574-9dcf-04bff4b3299b> para resolver o problema.
 
### Conclusão:

Fantástico esse Bootcamp Nexa - Machine Learning  na AWS

Me agregou muito conhecimento!!!

