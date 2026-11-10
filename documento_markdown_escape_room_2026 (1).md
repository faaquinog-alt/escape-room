Escape Room 2026 - Solucionario Placa Base Gigabyte Z690 AORUS PRO

FASE 1: Identificación del Factor de Forma

1. ¿Cuál es su factor de forma o tamaño exacto?
Es una placa base con factor de forma ATX, sus medidas son de 30.5 cm por 24.4 cm.

Código para avanzar: ATX


FASE 2: El Zócalo de la CPU

1. ¿Cómo se denomina exactamente el modelo de socket o zócalo de esta placa base?
El socket se llama LGA1700. Sirve para procesadores Intel de 12ª, 13ª y 14ª generación.

2. ¿Los pines de conexión están en este zócalo de la placa o en la parte inferior de la CPU?
Los pines están colocados en el propio zócalo de la placa base (por eso se llama tecnología LGA). En la parte de abajo del procesador solo vienen las superficies de contacto planas.

Código para avanzar: LGA1700


FASE 3: Los Puertos de Vídeo Traseros

1. ¿Qué puertos de vídeo integrados incluye esta placa base en su parte trasera?
Viene únicamente con 1 puerto DisplayPort en el panel trasero (soporta versión 1.2 y una resolución de hasta 4096x2304 a 60Hz). No trae puerto HDMI.

Código para avanzar: DisplayPort


FASE 4: El Diagnóstico del Panel Frontal

1. ¿En qué pines exactos del bloque F_PANEL debe ir conectado el interruptor de encendido (PWR_BTN / Power Switch)?
Se conecta en los pines 6 y 8, que vienen marcados como PW o PW_SW en el conector F_PANEL.

2. Si por error se conectara en los pines de Reset o en los LEDs del disco duro, ¿por qué no muestra ninguna señal de vida?
El botón de encendido funciona haciendo un puente rápido entre dos pines para mandar la orden de arranque a la fuente de alimentación. Si lo enchufas en los pines de LED, ahí hay corriente fija para alimentar bombillas y no se cierra ningún circuito de arranque. Si lo pones en los pines de Reset, el sistema solo responde si el PC ya estuviera encendido para reiniciar, pero sin estar encendido previamente la fuente nunca recibe la señal para arrancar.

Código para avanzar: Página 21


FASE 5: El Laberinto de la Memoria RAM

1. Si solo se van a instalar dos módulos de RAM, ¿en qué ranuras específicas deben colocarse obligatoriamente para activar el Dual Channel?
Se tienen que poner en las ranuras A2 y B2 (que según la versión de la placa se llaman DDR5_A2 y DDR5_B2, o DDR4_A2 y DDR4_B2). Son la segunda y la cuarta ranura empezando a contar desde el lado del procesador.

Código para avanzar: DDR5_A2 y DDR5_B2


FASE 6: El Enigma de la UEFI y la Actualización de la BIOS

1. ¿Cómo se llama exactamente el puerto USB trasero de color especial donde se debe conectar el pendrive para usar Q-Flash Plus?
Es el puerto USB 3.2 Gen 2 Tipo A de color rojo que viene etiquetado en la parte trasera como Q-Flash Plus Port.

2. ¿Qué nombre exacto debe tener obligatoriamente el archivo de la BIOS dentro del pendrive?
El archivo de la BIOS se tiene que renombrar obligatoriamente como GIGABYTE.bin para que el botón físico lo reconozca.

Código para avanzar: GIGABYTE.bin