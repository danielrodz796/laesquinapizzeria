Saludos, mi nombre es Daniel Lopez. 
Me estoy especializándome en desarrollo de aplicaciones web. 
Espero que esta practica funcione bien.
# 🍕 La Esquina Pizzería - Sistema de Gestión de Pedidos

¡Bienvenido al repositorio de **La Esquina Pizzería**! Este proyecto es una aplicación web diseñada para automatizar la toma de pedidos, gestionar el menú en tiempo real y coordinar las entregas a domicilio de nuestra pizzería de barrio.

---

## 🚀 Características Principales

* **Menú Digital Interactivo:** Permite a los clientes armar pizzas personalizadas o elegir las especialidades de la casa.
* **Carrito de Compras:** Cálculo automático de precios, impuestos y costo de envío según la distancia.
* **Panel de Cocina:** Interfaz en tiempo real para que los pizzeros vean los pedidos pendientes y los marquen como "En horno" o "Listo para envío".
* **Historial de Pedidos:** Registro local de ventas y estadísticas mensuales.

---

## 🛠️ Requisitos Previos

Antes de instalar este proyecto, asegúrate de tener instalado en tu computadora:

* [Node.js](https://nodejs.org) (Versión 18.0 o superior)
* [Git](https://git-scm.com)

---

## 📦 Instalación y Configuración

Sigue estos pasos para ejecutar el sistema en tu entorno local:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com
   ```

2. **Navegar al directorio del proyecto:**
   ```bash
   cd la-esquina-pizzeria
   ```

3. **Instalar las dependencias necesarias:**
   ```bash
   npm install
   ```

4. **Configurar las variables de entorno:**
   Crea un archivo `.env` en la raíz del proyecto y añade tus credenciales (puedes guiarte del archivo `.env.example`).

5. **Iniciar la aplicación en modo de desarrollo:**
   ```bash
   npm run dev
   ```
   Abre [http://localhost:3000](http://localhost:3000) en tu navegador para ver el sistema en acción.

---

## 🍕 Ejemplo de Uso (Sintaxis del Menú)

El sistema procesa los ingredientes del menú mediante archivos JSON. Así es como se estructura una pizza en nuestra base de datos:

```json
{
  "id": "pizz-01",
  "nombre": "La Esquina Especial",
  "ingredientes": ["Salsa de tomate", "Muzzarella", "Jamón", "Morrones", "Aceitunas negras"],
  "precio": 12.50
}
```

---

## 🤝 Contribuciones

Si quieres ayudarnos a mejorar el sistema de la pizzería:
1. Haz un **Fork** del proyecto.
2. Crea una rama con tu nueva función (`git checkout -b feature/NuevaMejora`).
3. Sube tus cambios (`git commit -m 'Añade nueva mejora'`).
4. Haz un **Push** a la rama (`git push origin feature/NuevaMejora`).
5. Abre un **Pull Request**.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

📬 **Contacto:** Si tienes dudas, puedes escribirle al equipo de desarrollo en `soporte@laesquinapizzeria.com`.
