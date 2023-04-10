# Puntas de prueba

Tipos de entradas en un osciloscopios
- $1M\Omega$ // C (15pF)
- $50 M\Omega$
Voy a tener por lo menos 2 tipos de puntas de pruebas

- Cables punta de prueba tipicamente tienen capacidad distribuida de 100pF/m
- A frecuencias bajas, no se consideran relevantes las reflexiones. Por eso no se usa teoria de lineas en esos casos
- La limitacion en frecuencia de las puntas x1 es que presentan muy baja impedancia a altas frecuencias y cargan mucho al osciloscopio.
- Las puntas x10 atenuan 10 veces la señal de entrada y logro cargar al circuito de  una manera diferente. Con un RC en serie con el resto del circuito
- $C_{coax}=120pF$ 
- $C_{OSC}=15pF$
- $C_{VAR}$ en la puntaes un rango de ajuste dado un rango de capacidad de entrada del osciloscopio
- Las puntas x10 tienen una alta resistencia del cable, para aminorar las señales reflejadas
	- Se usan cuando quiero medir mas de 10MHz
	- Existen para aprovechar el ancho de banda del osciloscopio
- Puntas x10 en osciloscopios de 50 $\Omega$ de entrada
	- Aca se usan para atenuar la señal
	- Hay puntas atenuadoras x100
		- usan R=900$\Omega$ de resistencia de cable
- Las puntas x1 en osciloscopios de 50 $\Omega$ de entrada
	- la atenuacion es variable con la frecuencia
	- Si me manejo con 9M y rango acotado
	- la atenuacion incrementa con la frecuencia
## Accesorios de las puntas

- Destornillador para ajustar $C_{VAR}$
- Aritos de colores para identificar canales
- Cablecito de tierra con punta cocodrilo
	- No tiene inductancia despreciable en altas frecuencias
	- Esa inductancia hace medir mal en altas frecuencias
- El resorte con el alambre se usa para la tierra al medir altas frecuencias
- Cable largo
	- Alta tension: 150v-300v
	- Las puntas de prueba comunes no soportan alta tension
	- Aleja la tierra de la punta -> se usa para frecuencias bajas y tensiones mas altas
	- vsmo mesi



**Puntas activas**
- Presentan $10k\Omega$ en 1 o 2 GHz

## Puntas de corrientes
Tiene un transformador y se ve una tension proporcional a la corriente que circula por el otro lado
Pone un tanque LR en serie con la carga
Funciona solo con alterna o incluso tampoco funciona con algo de poca frecuenca (5/6Hz)
Normalmente tienen un sensor de efecto Hall que sirve para detectar flujo magnetico y devuelve una tension proporsional ese flujo. Con esa tension hago circular una corriente en el secundario (que circule al reves de manera de anular el flujo magnetico) y de esa manera puedo medir corrientes continuas.
Si sature el nucleo de la punta, necesito desmagnetizar la punta porque el nucleo entro en histeresis y mide mal.
La unidad A.s me indica la corriente maxima que puedo medir sin saturar la punta.
La sensibilidad se expresa en mV de tension a la salida por cada mA de corriente a la entrada

**Osciloscopios 50ohm**
Normalmente los osciloscopios con entrada de 50ohm soporta 5V max.
Cuanto mas alta frecuencia soporta el osciloscopio, menor tension de entrada.

En alta frecuencia, aumenta al cuadrado las perdidas por efecto joule y el cable de la punta para medir tension va bajando su maxima tension antes de la ruptura dielectrica.

- Puntas activas pueden ser mas caras que un osciloscopio
- Puntas activas diferenciales son caras
- 