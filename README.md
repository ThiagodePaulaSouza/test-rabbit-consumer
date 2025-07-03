# test-rabbit-consumer
testando libs pra consumir grande quantidade de mensagem por segundo.

a base do processo é ter um producer que envia cerca de 200 mensagens por segundo (imagem?)
e então ter um consumer que vá consumindo e já executando o processo enquanto processa.

## importante
- Mensagem não pode ser perdida
- não ter replicação de dados no resultado (db)

---
fazer projeto manual onde eu vou tentar fazer o testes nele usando os meus conhecimentos antes de usar uma lib especializada justamente pra entender até onde eu consigo ir sem libs

dps usar masstransit, Wolverine, NServiceBus, Rebus etc..
