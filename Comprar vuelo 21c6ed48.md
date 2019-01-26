### Objetivo

Adquirir el [servicio ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Servicio-d10cf9fa-4a54-493e-8262-5ba02b9a295b)de [vuelo](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9).

### Contexto

El [vuelo ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9)se encuentra [disponible](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Vuelo-Disponible-0f56477b-17f4-4a37-ae42-09630fbbf62d).

### Recursos

[Itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee), [vuelo](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9).

### Actores

[Pasajero](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4), [aerolínea](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Aerolnea-acfa4b6c-42fc-4137-bf9b-967ea8e6daa4).

### Set de Episodios

1. El [pasajero ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4)inicia sesión.
2. El [pasajero ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4)selecciona un [vuelo ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9)[disponible ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Vuelo-Disponible-0f56477b-17f4-4a37-ae42-09630fbbf62d)para el [itinerario ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinerario-77d6777d-c052-43d0-a2e9-adc68b1593ee)que desea realizar.
3. El [pasajero ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4)ingresa sus [datos personales](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Datos-personales-c520636c-ba8b-41f1-b95e-7dd599681bbe) y los del resto de los [pasajeros ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4)que viajan con el.
4. El [pasajero ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4)ingresa un [medio de pago](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Medio-de-Pago-b781b392-4758-4d41-9d47-404b303494c3) válido.
5. Se genera la [reserva ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Reserva-f6cb1208-721f-4cea-895b-40a0e9825210)con pago pendiente.
6. Se genera el [PNR](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Cdigo-de-Reserva-PNR-Localizador-b8faa241-bc2e-45e4-8843-f78dfb760c5f).
7. Se emite el [ticket electrónico](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Ticket-Electrnico-Voucher-445362ba-6ee6-4f3e-9cb3-57c4a54af64f) a nombre del [pasajero](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4).

### Restricciones

* El [medio de pago](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Medio-de-Pago-b781b392-4758-4d41-9d47-404b303494c3) debe ser válido (ver casos alternativos)

### Casos alternativos

* La [tarjeta de crédito](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Medio-de-Pago-Tarjeta-de-Crdito-8b834a4a-6454-4231-bb87-712d59cbfdf8) es falsa.
* La [tarjeta de débito ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Medio-de-Pago-Tarjeta-de-Dbito-aeca5b25-e40b-4a33-9343-2f3b8c78c62c)es falsa.
* Límite insuficiente de la [tarjeta de crédito](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Medio-de-Pago-Tarjeta-de-Crdito-8b834a4a-6454-4231-bb87-712d59cbfdf8).
* Saldo insuficiente de la [tarjeta de débito](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Medio-de-Pago-Tarjeta-de-Dbito-aeca5b25-e40b-4a33-9343-2f3b8c78c62c).