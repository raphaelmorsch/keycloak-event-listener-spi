# Mecanismo de Visibilidade (Session Tracking)

Este é um exemplo rudimentar de como ampliar a Visibilidade de Eventos que ocorrem com as Sessões dentro do RH-SSO (keycloak).

O tracking pode ser feito por userId e também por sessionId

### Disclaimer: A solução para um mecanismo ampliado de visibilidade funciona baseada em SPI. Cabe ressaltar que esse é um cenário não suportado pela Red Hat.

### Deve-se avaliar uma solução para despejo dos logs gerados (Kafka, por exemplo) já que provavelmente as informações devem gerar uma quantidade grande de dados (dependendo da visibilidade)

# keycloak-event-listener-spi
A sample event listener SPI for keycloak


Please refer to this blog for step by step explanation on how to create the SPI  

[https://dev.to/adwaitthattey/building-an-event-listener-spi-plugin-for-keycloak-2044](https://dev.to/adwaitthattey/building-an-event-listener-spi-plugin-for-keycloak-2044)
