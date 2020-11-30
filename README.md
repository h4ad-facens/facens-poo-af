# Projeto AF

Nome: Vinícius Lourenço Claro Cardoso
RA: 180618

## Introdução

O projeto foi estruturado utilizando `entities` que representam os dados do Cliente, Veículo e Reserva,
`payloads` que são os dados para a criação e atualização das entidades e por fim os
`repositories` que lidam com o estado da aplicação ( que está em memória ).

Além disso, por costume, eu deixei todo o projeto em inglês, então Cliente será `Client`,
Veículo será `Vehicle` e Reserva será `Reservation`.

Para testar, basta rodar esse projeto e acessar o url [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html),
ali conterá todas as rotas da aplicação no qual você poderá ir testando a adição e remoção
dos clientes, veículos e reservas.
