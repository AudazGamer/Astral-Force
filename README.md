# Astral Force

Astral Force es un script desarrollado en Skript para Minecraft que implementa un sistema de maná y habilidades elementales, ofreciendo a los jugadores una experiencia única. Los jugadores pueden elegir una clase elemental, utilizar habilidades especiales según su elemento y gestionar su maná para realizar poderosos ataques y habilidades. El sistema también incluye regeneración de maná, tiempos de recarga (cooldowns) y una interfaz visual para mostrar en tiempo real el nivel de maná de cada jugador, mejorando la interacción y el control durante el juego.

## 🚀 Características principales
- **Sistema de Maná:** Los jugadores tienen un nivel de maná que se regenera con el tiempo y se consume al usar habilidades.

- **Clases Elementales:** Los jugadores pueden elegir entre varias clases elementales, cada una con habilidades innatas y habilidades especiales.

- **Habilidades Únicas:** Cada clase elemental tiene habilidades únicas que pueden ser activadas con un costo de maná.

- **Regeneración de Maná:** El maná se regenera automáticamente con el tiempo, y los jugadores pueden consumir ciertos alimentos para acelerar la regeneración.

- **Interfaz Visual:** Una bossbar que muestra el nivel de maná actual del jugador, con indicadores visuales para niveles bajos, máximos y sobrecarga.

- **Cooldowns:** Las habilidades tienen un tiempo de reutilización para evitar el spam de habilidades.

## 🛠 Instalación
- **Requisitos:** Asegúrate de tener instalado un servidor de Minecraft ```1.21``` o superior con Skript.
- **Dependencias:** Skript, SkBee.
- **Descarga:** Descarga el archivo AstralForce.sk y colócalo en la carpeta de ```plugins/skript/scripts``` de tu servidor.
- **Configuración:** Edita el campo 'options' para ajustar los parámetros según tus preferencias (niveles de maná, tiempos de regeneración, etc.).

## ⚙️ Configuración
El script incluye varias opciones configurables en la sección options:
```
prefix: (Prefijo para los mensajes del sistema)
mana.maxlevel: (Nivel máximo de maná que un jugador puede regenerar)
mana.minlevel: (Nivel mínimo de maná)
mana.regenlevel: (Cantidad de maná que se regenera cada cierto tiempo)
mana.maxlimit: (Límite máximo de maná)
mana.usehability: (Costo de maná por uso de habilidad)
mana.regentime: (Tiempo en segundos entre cada regeneración de maná)
mana.cooldown: (Tiempo de reutilización de las habilidades)
mana.command: (Tiempo de reutilización para comandos de habilidades)
mana.updatebar: (Tiempo en segundos entre cada actualización de la barra de maná)
```

## 🛡️ Comandos administrativos
| Comando | Descripción |
|---------|-------------|
| `/mana info` | Muestra la información actual del maná del jugador. |
| `/mana set <jugador> <nivel>` | Establece el nivel de maná de un jugador. |
| `/mana add <jugador> <nivel>` | Añade maná a un jugador. |
| `/mana reset <jugador>` | Restablece el maná de un jugador al nivel mínimo. |
| `/element info` | Muestra la clase elemental actual del jugador. |
| `/abilities` | Muestra las habilidades disponibles de la clase. |

## 🌍 Clases elementales

| Clase | Descripción |
|-------|-------------|
| `fire / fuego` | Clase de fuego con habilidades ofensivas. |
| `water / agua` | Clase de agua con habilidades de control. |
| `earth / tierra` | Clase de tierra con habilidades defensivas. |
| `air / aire` | Clase de aire con habilidades de movilidad. |
| `light / luz` | Clase de luz con habilidades curativas. |
| `dark / oscuridad` | Clase de oscuridad con habilidades de daño. |
| `spacial / espacial` | Clase especial con habilidades de soporte. |
| `none / ninguna` | Sin clase activa. |

## 💻 Contribuciones
Si deseas contribuir a este proyecto, puedes hacerlo a través de GitHub. ¡Todas las contribuciones son bienvenidas!

## 📜 Licencia
Este proyecto está bajo la licencia MIT. Para más detalles, consulta el [archivo de licencia](./LICENSE).
