# 🎮 Simulación de Entidades en Minecraft (POO en Java)

Este proyecto simula un sistema básico de entidades del mundo de **Minecraft** utilizando los principios de **Programación Orientada a Objetos (POO)** en Java.

---

## 🧠 Objetivo

Aplicar los conceptos de **interfaces, clases abstractas, herencia y polimorfismo**, simulando entidades como jugadores, zombis y aldeanos en un entorno simple.

---

## 🧱 Estructura del Proyecto

```bash
MinecraftEntidades/
├── Main.java                 # Clase principal para ejecutar la simulación
├── EntidadMinecraft.java    # Interfaz que define el comportamiento común
├── EntidadBase.java         # Clase abstracta base para todas las entidades
├── Jugador.java             # Clase concreta que representa a un jugador
├── Zombi.java               # Clase concreta que representa a un zombi
├── Aldeano.java             # Clase concreta que representa a un aldeano
🚀 ¿Cómo ejecutar?
Abre IntelliJ IDEA.

Importa este proyecto como proyecto Java.

Marca la carpeta donde están los .java como Sources Root.

Abre Main.java.

Haz clic derecho → Run 'Main.main()'.

🔍 Funcionalidades
✔️ EntidadMinecraft (Interfaz)
aparecer()

interactuar()

obtenerTipo()

✔️ EntidadBase (Clase abstracta)
Atributos comunes: nombre, salud

Implementa parcialmente la interfaz

Deja interactuar() como método abstracto

✔️ Clases hijas:
🧍‍♂️ Jugador
Tiene inventario (List<String>)

Interactúa mostrando sus objetos

🧟 Zombi
Tiene nivel de agresividad

Interactúa atacando

🧑‍🌾 Aldeano
Tiene un oficio (ej: herrero, bibliotecario)

Interactúa comerciando

📷 Ejemplo de Salida
markdown
Copiar
Editar
Steve ha aparecido con 20 de salud.
Steve revisa su inventario: [Espada de diamante, Manzana dorada]
Tipo: Jugador
------------------------------
Zombi#1 ha aparecido con 15 de salud.
Zombi#1 ataca con agresividad nivel 7!
Tipo: Zombi
------------------------------
Aldeano#1 ha aparecido con 10 de salud.
Aldeano#1 dice: ¡Hmm! Soy bibliotecario, ¿quieres comerciar?
Tipo: Aldeano
------------------------------
