### Objetivo

Verificar que existan [vuelos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9)[disponibles ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Vuelo-Disponible-0f56477b-17f4-4a37-ae42-09630fbbf62d)para un cierto [itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee).

### Contexto

El [pasajero](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4) debe tener los datos de origen, al menos un destino y una fecha de ida, además de la cantidad de [pasajeros](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4), es decir, parte del [itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee). 

### Recursos

[Itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee), [vuelo](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9).

### Actores

[Pasajero](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4), [agencia](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Agencia-6adc03c5-323c-474f-8d0f-142686ff34ba), [aerolínea](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Aerolnea-acfa4b6c-42fc-4137-bf9b-967ea8e6daa4).

### Set de Episodios

1. El [pasajero ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4)se presenta con los datos del [itinerario ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee)en la [agencia](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Agencia-6adc03c5-323c-474f-8d0f-142686ff34ba).
2. El [pasajero ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4)brinda los datos del [itinerario ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee)a la [agencia](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Agencia-6adc03c5-323c-474f-8d0f-142686ff34ba).
3. La [agencia ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Agencia-6adc03c5-323c-474f-8d0f-142686ff34ba)[busca la disponibilidad](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Verbo-Buscar-disponibilidad-vuelo-46d6db70-69a1-4df8-9f03-b9c644ae9e61) de [vuelos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9)para el [itinerario ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee)solicitado.
4. La [agencia ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Agencia-6adc03c5-323c-474f-8d0f-142686ff34ba)informa al [pasajero ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4)con los [vuelos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9)[disponibles](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Vuelo-Disponible-0f56477b-17f4-4a37-ae42-09630fbbf62d), detallando horarios y escalas, ofrecidos por las diferentes [aerolíneas](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Aerolnea-acfa4b6c-42fc-4137-bf9b-967ea8e6daa4).

### Restricciones

* La fecha de ida no debe ser posterior a la fecha de regreso.

### Casos alternativos

* Los [vuelos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Vuelo-71851f91-02b2-4cd3-b33b-7fea9bd789c9)para el [itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee) solicitado se encuentran [agotados](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Vuelo-No-disponible-Vuelo-Agotado-d26bcd38-3455-431a-a5ed-f9a2c4acc4c2).
* No existen [aerolíneas ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Aerolnea-acfa4b6c-42fc-4137-bf9b-967ea8e6daa4)que operen para el [itinerario ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee)solicitado.