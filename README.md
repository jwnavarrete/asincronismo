##JavaScript Exercises by John Navarrete
> Web development exercises:
1. Callback
2. Promise
3. Async

### advantages and disadvantages
##### Callback
	Ventajas: Simple(una funci�n que recibe otra funci�n). Son universales, corren en cualquier navegador.
	Desventajas: Composici�n tediosa, anidando cada vez m�s elementos. Caer en Callback Hell.

##### Promise
	Ventajas: Facilmente enlazables .Then( return? ).Then - F�cil e intuitivo de leer.
	Desventajas: Posible error si no se retorna el siguiente llamado. No corre en todos los navegadores.

##### Async
	Ventajas: Se puede usar try-catch . C�digo m�s ordenado e intuitivo.
	Desventajas: No corre en todos los navegadores (se requiere un transpilador).