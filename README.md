##JavaScript Exercises by John Navarrete
> Web development exercises:
1. Callback
2. Promise
3. Async

### advantages and disadvantages
##### Callback
	Ventajas: Simple(una función que recibe otra función). Son universales, corren en cualquier navegador.
	Desventajas: Composición tediosa, anidando cada vez más elementos. Caer en Callback Hell.

##### Promise
	Ventajas: Facilmente enlazables .Then( return? ).Then - Fácil e intuitivo de leer.
	Desventajas: Posible error si no se retorna el siguiente llamado. No corre en todos los navegadores.

##### Async
	Ventajas: Se puede usar try-catch . Código más ordenado e intuitivo.
	Desventajas: No corre en todos los navegadores (se requiere un transpilador).