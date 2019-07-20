# hackathon_xp_tdc_2019
Projeto desenvolvido no Hackathon da XP investimento durante o TDC-SP 2019
# Projeto Hackathon XP - TDC sp 2019

Projeto desenvolvido no Hackathon da XP investimento durantes o TDC-SP 2019

# Desafio 
[Desafio do Hachkathon](https://github.com/whrocha/hackathon_xp_tdc_2019/blob/master/Imagem%20do%20iOS.jpg)

# Chat Bot
Foi feita uma integracao com o servico [ChatFuel](https://chatfuel.com/) e o mensenger do Facebook.
[link do chat](https://web.facebook.com/messages/t/aprendendoainvestirmelhor)

# Arquitetura Proposta
A arquitetura proposta visa um cenario onde sera feito real consuta em real time na aplicacao, por isso a utilizacao do Kineses, e tambem pensando na contrucao do data lake, os raw data sao salvos no S3.

Tambem e feita uma analise de sentimento nos textos do chatbot, onde esses dados enriquecidos sao carregados no Dynamo, possibilitando assim uma integracao com o CRM da XP investimentos, esses dados serao
importantes para posteriores acoes de markenting.)


[Arquitetura](https://github.com/whrocha/hackathon_xp_tdc_2019/blob/master/Streaming%20Data%20Architecture%20Chat%20Bot%20V2.png)

Tambem pode ser consultada [aqui](https://cloudcraft.co/view/10e7d7cd-09e5-40cf-979c-19c5da57bb54?key=tPPFZuo-ScvPy7gsUZNXDw)

