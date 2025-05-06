# Chekpoint2-Kotlin
Ygor Arean
Rm: 88170

Explicações

Retrofit2: Para chamadas HTTP à API.  
Gson: Conversão de JSON para objetos Kotlin.  
Coroutines: Gerenciamento de operações assíncronas.  
Android View System: Interface com Toolbar, TextView e Button.


Consulta o preço atual do Bitcoin (BTC) via API.  
Formata o preço em reais (R$).  
Exibe a data da cotação no formato dd/MM/yyyy HH:mm:ss.  
Botão "Refresh" para atualização manual.  
Tratamento de erros de rede e respostas da API.


Modelo de dados da cotação.  
Atributos:  
high: Preço máximo.  
low: Preço mínimo.  
vol: Volume negociado.  
last: Último preço.  
buy: Preço de compra.  
sell: Preço de venda.  
date: Timestamp da cotação.


Estrutura

-model
-TickerResponse.kt
-Ticker.kt
-service
-MercadoBitcoinService.kt
-MercadoBitcoinServiceFactory.kt
-MainActivity.kt

Imagem antes da atualização da moeda
<img width="158" alt="image" src="https://github.com/user-attachments/assets/9e92a3be-fe5d-4097-b302-b3b7dbd11721" />

Imagem depois da atualização da cotação
<img width="169" alt="image" src="https://github.com/user-attachments/assets/57bcb51a-64ea-440b-885f-0d390ebcb87e" />
