# Consulta de CEP com ViaCEP

### 1. Qual API você usou
Usei a API ViaCEP. A documentação pode ser encontrada em https://viacep.com.br/.

### 2. O que ela devolve
Ela devolve informações de endereço referentes ao CEP informado, como logradouro, bairro, cidade, estado e DDD.

### 3. O endereço que você chamou
URL testada: `https://viacep.com.br/ws/01001000/json/`

### 4. Como rodar
Basta abrir o arquivo `index.html` diretamente em qualquer navegador de internet. Não é necessário utilizar um servidor web.

### 5. Um print da tela funcionando
<img width="1484" height="584" alt="image" src="https://github.com/user-attachments/assets/64b77ccb-cd8d-4c33-b3e0-3c83bd1e3bfc" />


### 6. Uma dificuldade que você teve
Tive uma dificuldade em tratar o caso em que o CEP informado tem 8 dígitos, mas não existe na base de dados. Resolvi verificando se a resposta da API continha a propriedade `erro` antes de exibir os dados na tela.
