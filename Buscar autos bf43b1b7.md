### Objetivo

Verificar que existan [autos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a)para rentar en un determinado [itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinerario-77d6777d-c052-43d0-a2e9-adc68b1593ee).

### Contexto

El [cliente ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4)debe tener los datos de la ciudad destino, la fecha de inicio del alquiler, la fecha de devolución, es decir parte del [itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinerario-77d6777d-c052-43d0-a2e9-adc68b1593ee).

### Recursos

[Itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee), [auto](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a), [seguro](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Seguro-para-el-auto-4db8135a-4713-4ad3-a296-2ce2440d8eba).

### Actores

[Cliente](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4), [empresa arrendadora de autos](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Empresa-arrendadora-de-autos-e0cac858-9bdf-4640-97fd-7dd92834c375).

### Set de Episodios

1. El[ ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4)[cliente ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4)ingresa en la sección de buscar [auto](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a).
2. El[ ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-1aca8769-d624-47f7-9373-9682438afab4)[cliente ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Pasajero-Husped-Cliente-1aca8769-d624-47f7-9373-9682438afab4)ingresa los datos del[ itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee) y el tipo de [auto ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a)que desea arrendar.
3. Se busca el tipo de [auto ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a)seleccionado para el[ itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinirario-77d6777d-c052-43d0-a2e9-adc68b1593ee) solicitado.
4. Se muestran los [autos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a)[disponibles ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Libre-cedb2e90-b534-480a-a947-7ab9aecce814)con sus costos para el [itinerario ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinerario-77d6777d-c052-43d0-a2e9-adc68b1593ee)especificado.
5. Se muestran los diferentes [seguros ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Seguro-para-el-auto-4db8135a-4713-4ad3-a296-2ce2440d8eba)que cubren los [autos](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a), con sus precios.

### Restricciones

* La fecha de inicio de alquiler no puede ser superior a la de devolución del [auto](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a).

### Casos alternativos

* El tipo de [auto ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a)seleccionado se encuentra [alquilado](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Alquilado-eb1ff829-a07c-4b6c-899a-cdbe37699ca8).
* Los [autos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a)para el [itinerario](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Objeto-Itinerario-77d6777d-c052-43d0-a2e9-adc68b1593ee) solicitado se encuentran [alquilados](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Estado-Alquilado-eb1ff829-a07c-4b6c-899a-cdbe37699ca8).
* No existen [empresas arrendadoras](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Sujeto-Empresa-arrendadora-de-autos-e0cac858-9bdf-4640-97fd-7dd92834c375) de [autos ](https://app.nuclino.com/Curso-LEL/Agencia-de-Viajes/Servicio-Auto-bf39c08c-4d7e-4af8-a986-76e5fbd5390a)en la ciudad destino.