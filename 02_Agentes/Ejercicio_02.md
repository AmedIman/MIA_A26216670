# Ejercicio 2 — Descripción PEAS de agentes inteligentes

## 1. Asistente virtual de voz

- **Performance:** Respuesta correcta, tiempo de respuesta, satisfacción del usuario.
- **Environment:** Casa, oficina, personas. Es parcialmente observable, estocástico, secuencial, dinámico y continuo.
- **Actuators:** Bocina, controlar dispositivos inteligentes, enviar mensajes.
- **Sensors:** Micrófono, información de aplicaciones, datos de ubicación, hora y calendario.

**Justificación:** Es parcialmente observable porque el agente no puede conocer todas las intenciones del usuario. Es estocástico porque una misa orden puede tener varios resultados. Es secuencial porque las instrucciones anteriores afectan las siguientes, y es dinámico porque el usuario y el entorno pueden cambiar en cualquier momento.

---

## 2. Robot aspirador doméstico

- **Performance:** Superficie limpiada, tiempo, consumo de batería, colisiones, caídas.
- **Environment:** Dentro de una casa, muebles, paredes, escaleras, personas, mascotas, objetos del hogar. Es parcialmente observable, estocástico, secuencial, dinámico y continuo.
- **Actuators:** Motores, cepillos, aspiradora.
- **Sensors:** Cámaras, sensores de todo tipo (proximidad, obstáculos, caída, suciedad ruedas y movimiento, batería, navegación).

**Justificación:** Es parcialmente observable porque los sensores no pueden conocer absolutamente todo de la casa. Es estocástico porque las cosas en la casa pueden estar en cualquier posición, así como las mascotas y las personas. Es secuencial porque la ruta que ya tomó anteriormente afecta la ruta a seguir. Es dinámico porque el entorno puede cambiar mientras el robot limpia.

---

## 3. Sistema de recomendación de streaming

- **Performance:** Satisfacción del usuario, tasa de conversión de recomendaciones.
- **Environment:** Plataforma de streaming, catálogo de películas y series. Es parcialmente observable, estocástico, secuencial, dinámico y discreto.
- **Actuators:** Aplicación, mostrar la información.
- **Sensors:** Base de datos de la aplicación con el historial de reproducción, búsquedas, calificaciones, listas de reproducción, etc.

**Justificación:** Es parcialmente observable porque el sistema no conoce exactamente los gustos o intenciones del usuario. Es secuencial porque las interacciones anteriores modifican las recomendaciones futuras. Es dinámico porque cambian los gustos del usuario y el catálogo de series o películas.

---

## 4. Vehículo autónomo en ciudad

- **Performance:** Minimizar accidentes, respetar las normas de tránsito, llegar al destino correcto, minimizar el tiempo de viaje y el consumo de energía.
- **Environment:** Calles, vehículos, peatones, ciclistas, semáforos, señales de tránsito, topes. Es parcialmente observable, estocástico, secuencial, dinámico y continuo.
- **Actuators:**Volante, acelerador, freno, direccionales, luces, claxon, transmisión, bocina, ventanas.
- **Sensors:** Cámaras, LIDAR, GPS, sensores de velocidad y de motor.

**Justificación:** Es parcialmente observable porque los sensores no pueden captar todo en el camino. Es estocástico porque las acciones de otros conductores, peatones y ciclistas no pueden predecirse. Es secuencial porque cada decisión de conducción afecta las proximas decisiones. Es dinámico porque los elementos del tráfico cambian continuamente.

---

## 5. Agente de trading algorítmico en bolsa

- **Performance:** Maximizar el rendimiento, minimizar pérdidas y costos, controlar el riesgo y mantener los límites.
- **Environment:** Mercados financieros, casas de bolsa. Es parcialmente observable, estocástico, secuencial, dinámico y continuo.
- **Actuators:** Enviar órdenes de compra y venta, cancelar órdenes; modificar precios y cantidades, establecer límites de posición, cerrar posiciones.
- **Sensors:** Historial de precios, volumen, indicadores financieros, datos económicos, información de la cuenta, límites.

**Justificación:** Es parcialmente observable porque ningún agente conoce toda la información de los mercados. Es estocástico porque los precios no pueden predecirse al 100%. Es secuencial porque las operaciones anteriores afectan el capital y, por lo tanto, las siguientes decisiones. Es dinámico porque los precios y las condiciones del mercado cambian constantemente.

---

## 6. Sistema de diagnóstico médico asistido por IA

- **Performance:** Maximizar la precisión del diagnóstico, minimizar falsos positivos y falsos negativos.
- **Environment:** Hospitales, pacientes, médicos, estudios médicos, síntomas. Es parcialmente observable, estocástico, secuencial, dinámico y continuo.
- **Actuators:** Generar diagnósticos, señalar anomalías en radriografías, indicar si hace falta más información o estudios.
- **Sensors:** Síntomas, historial clínico, resultados de laboratorio, signos vitales, radiografías, tomografías, resonancias, alergias.

**Justificación:** Es parcialmente observable porque el sistema no puede saber todos los aspectos del estado de salud del paciente. Es estocástico porque los mismos síntomas pueden corresponder a diferentes enfermedades. Es secuencial porque nuevos estudios pueden modificar el diagnóstico. Es dinámico porque el estado del paciente puede cambiar con el tiempo.

---

## 7. Dron de inspección de infraestructura

- **Performance:** Maximizar la precisión de la inspección, detectar correctamente grietas, corrosión o fugas, minimizar tiempo de vuelo y consumo de batería, evitar colisiones.
- **Environment:** Obras de construcción, tuberías, viento, clima. Es parcialmente observable, estocástico, secuencial, dinámico y continuo.
- **Actuators:** Motores y hélices.
- **Sensors:** Cámaras, sensores, GPS, altímetro.

**Justificación:** Es parcialmente observable porque hay zonas a las que el dron no va a poder acceder. Es estocástico por el viento, cambios de iluminación, obstáculos, etc. Es secuencial porque la trayectoria y posición actual afectan las zonas que va a explorar posteriormente. Es dinámico porque las condiciones pueden cambiar durante el vuelo.

---

## 8. Agente jugador de ajedrez

- **Performance:** Maximizar el score de la posición, minimizar la pérdida de material, lograr jaque mate en el menor número de movimientos, respetar las reglas del ajedrez.
- **Environment:** Tablero de ajedrez, piezas, reglas del juego, jugador humano. Es totalmente observable, determinista, secuencial, estático y discreto.
- **Actuators:** Seleccionar piezas, hacer movimientos, capturar piezas, realizar enroques, coronar peones, ofrecer o aceptar tablas.
- **Sensors:** Posición actual de las piezas en el tablero, movimientos realizados, turno actual, derechos de enroque, posibilidad de captura al paso, prohibición de movimientos.

**Justificación:** Es totalmente observable porque el agente puede conocer el estado completo del tablero y los movimientos anteriores. Es determinista porque todos los movimientos posibles son conocidos. Es secuencial porque cada movimiento modifica el estado del tablero y afecta las decisiones posteriores. Es estático porque el tablero no cambia mientras el agente está pensando en su movimiento y es discreto porque el número de posiciones y movimientos posibles es finito.