
- Los campos electricos nunca son uniformes en la vida real
- El potencial 0 no existe
- Se puede fijar un punto arbitrariamente como cero
- El punto tiene que ser alejado de las corrientes circulantes que lo toman como referencia
- La resistividad depnde principalmente de la distancia entre la banda de valencia y la de conduccion y de la red cristalina (por eso depende de la temperatura)
- Factor de potencia
	- Los UPS generan armonicos de 3er orden que joden a la primer etapa de subestacion y calienta los transformadores
- Equipos que varien el consumo a corriente constante
- Efecto skin
- Tierra
	- No posee potencial 0
	- Posee resistividad elevada y no es lineal
- Medir resistitividad del suelo -> Telurimetro
	- 4 electrodos
	- salen electrodos al suelo distanciados conn una regla
	- el equipo me da Re y A es la dirancia entre los electrodos
	-  $\rho_E=2 \pi A R_E$
	- Hay terrenos cae que la resistividad con la distancia y otros que suben
	- Hay otros que hacen valles y despues suben
- Problemas de “malas puestas a tierra” (no relacionado con la resistencia de puesta a tierra)
	- Problemas vienen por mal diseño
	- Rayos
		- Circula corriente por cable equilibrante
		- Circula potencial por cable de datos
		- Hay normas para mitigar estos problemas 
			- IEC99.1
			- ANSI IEEE 80
			- ANSI IEEE C62
- 2 funciones de la tierra como conductor en alta energia
	- Limitar la elevacion de pontecial en caso de impacto de rayos o fallas
	- Permitir el funcionamiento de los dispositivos de seguridad
- Objetivos de las normas
	- Limitar las tensiones del paso y contacto a valores no letales

# Distribucion de energia electrica a baja tension

- a 50/60 Hz Letal 0.1A
- a 25Hz letal 0.25A
- 1 mA cosquilleo
- 1 a 6 mA corrientes let-go, desagradables pero no impiden soltar cosas
- 9 a 25mA no permiten soltar objetos pero no dejan rastros si la exposicion se interrumpe
- 9 a 60 paralsiis menores
- 60 a 100mA fibrilacion ventricular
	-  $k = I_B^2. t_S$
		- ts = tiempo de exposicion
		- Ib = Corriente eficaz que circula por el cuerpo
		- k = constante que depende de las personas (etnias)
	- $k_{50}=0.116$
- Resistencia interna aprox 300 ohm
- Sobre la piel de 500 a 3k
- Entre mano y pie 1100
- Entre ambas manos 2300
- GPR: Ground potential rise
	- Maximo potencial queuna subestacion puede elevarlse respecto de un punto alejado de la misma (corriente de falla contra tierra por la resistencia de tierra de la malla)

# Sistema de distribucion de Energia en Baja tension

TN TT e IT

fue muy rapido
ver PPT

# Masa de señal flotante

Isolated ground no es tierra independientes, como dicen la traducciones de algunas documentaciones en Argentina

Es la referencia de 0V para la electronica (dentro de un instrumento)
