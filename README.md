# chamadasassincronasJS
Trabalhando com chamadas assíncronas JavaScript 

Questões:<br>
<strong>1. Qual problema percebeu ao realizar tais alterações;</strong><br>
O JavaScript executava a mensagem "Dados obtidos do servidor" enquanto os dados ainda estvam sendo carregados de "https://jsonplaceholder.typicode.com/photos".  
<strong>2. Explique porque o problema ocorreu e o qual a relação com chamadas assíncronas;</strong><br>
Tal problema ocorre devido o JavaScript executar as chamadas assíncronas em segundo plano, logo, ele prosegue para próxima instrução.
<br><strong>3. Altere o código para resolver o problema.</strong><br>
Para resolver o problema foi implementado a função requestdepois, com async.
No corpo da função, eu chamo "await request()", que diz que aquela demanda deverá ser atendiddas, e depois executa a próxima instrução.  

