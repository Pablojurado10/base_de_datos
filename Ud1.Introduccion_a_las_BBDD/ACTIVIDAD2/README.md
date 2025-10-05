# Actividad 2. Análisis de un Sistema de Información  

---

## Objetivo  
Analizar un sistema de reservas de pistas de pádel para comprender cómo se gestionan los datos, los usuarios y los procesos en la práctica.  

---

## 1. Usuarios  
Los principales usuarios que interactúan con el sistema son:  

- **Clientes/Jugadores**:  
  - Registrarse en la aplicación o página web.  
  - Consultar la disponibilidad de pistas.  
  - Reservar y pagar una pista.  
  - Cancelar o modificar reservas.  

- **Administradores/Gestores del club**:  
  - Gestionar horarios de apertura y disponibilidad.   
  - Revisar pagos y facturación.  
  

---

## 2. Datos  
El sistema recoge y gestiona la siguiente información:  

- **De los usuarios**: nombre, apellidos, correo electrónico, teléfono, método de pago.  
- **De las reservas**: fecha, hora, pista, duración, estado (reservada, cancelada, pendiente).  
- **De las pistas**: número de pista, ubicación (interior/exterior), estado (disponible, ocupada).  
- **De los pagos**: importe, método de pago, facturas.  

---

## 3. Procesos  
Los principales procesos del sistema son:  

1. **Registro de usuario**: el cliente crea una cuenta en la aplicación.  
2. **Consulta de disponibilidad**: el cliente ve qué pistas están libres en una fecha y hora.  
3. **Reserva de pista**: el cliente selecciona una pista, la reserva y efectúa el pago.  
4. **Confirmación**: el sistema actualiza la base de datos y envía confirmación (correo o notificación).  
5. **Gestión interna**: los administradores pueden ver las reservas, ingresos y estadísticas de uso.  
6. **Cancelación**: si el usuario anula, el sistema libera la pista.  

---

## 4. Tecnología  
El sistema suele basarse en una combinación de:  

- **interfaz de usuario:** Aplicación web y móvil (desarrollada en React, Angular o Flutter).  
- **lógica del sistema:** API REST en Java, Node.js o Python.  
- **Base de datos:** Relacional (MySQL) para usuarios, reservas y pagos.  
- **Infraestructura:** Servidores en la nube (AWS).  
- **Pasarela de pago:**  PayPal , VISA o Efectivo.  

---

## 5. Propósito  
El sistema de reservas de pistas de pádel tiene como finalidad:  

- Facilitar a los clientes la **reserva rápida y cómoda** desde el móvil o el ordenador.  
- Optimizar la gestión del club, evitando llamadas telefónicas y reservas manuales.  
- Mejorar la **organización y control de ingresos**.  
- Aumentar la satisfacción del usuario al ofrecer disponibilidad en tiempo real.  




