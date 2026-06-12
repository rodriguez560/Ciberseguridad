# 🛡️ Resumen: Ciberseguridad - Fundamentos y Ataques Comunes

Este documento es un resumen estructurado del informe elaborado en la **Universidad Autónoma del Beni "José Ballivián"** para la asignatura de Tecnologías Emergentes, enfocado en los principios esenciales de seguridad informática y mitigación de amenazas.

## 📌 Introducción

En la era digital actual, la información se ha convertido en el activo más valioso. La ciberseguridad es la disciplina que combina herramientas, procesos y comportamientos para proteger sistemas, redes y datos contra el acceso no autorizado. La rápida transformación digital y la administración en línea de infraestructuras han expandido la superficie de ataque, haciendo indispensable una arquitectura de defensa sólida.

## 🏛️ Fundamentos Teóricos

### La Tríada CIA

Cualquier arquitectura de seguridad se basa en este estándar internacional:

- **Confidencialidad:** Garantiza que la información solo sea accesible por procesos o personal autorizado (Ej. Cifrado, MFA).
- **Integridad:** Asegura que los datos se mantengan exactos y libres de alteraciones maliciosas (Ej. Hashes, firmas digitales).
- **Disponibilidad:** Asegura que los usuarios legítimos tengan acceso ininterrumpido a los recursos tecnológicos (Ej. Backups, balanceadores de carga).

### Principios de Diseño en la Defensa

- **Defensa en Capas (Defense in Depth):** Implementación de múltiples controles superpuestos. Si uno falla, otros neutralizan la amenaza.
- **Principio de Menor Privilegio:** Restringir los derechos de acceso estrictamente a los recursos necesarios para ejecutar una tarea.
- **Confianza Cero (Zero Trust):** Filosofía de "nunca confiar, siempre verificar". Exige validación continua de usuarios y dispositivos, asumiendo que el perímetro siempre puede estar comprometido.

## ⚠️ Vectores de Ataque Comunes

Los agentes de amenazas utilizan tácticas en constante evolución para vulnerar sistemas:

1. **Ingeniería Social (Phishing):** Engaño psicológico mediante correos o enlaces falsos para robar credenciales.
2. **Malware:** Código diseñado para infiltrarse o dañar (incluye Troyanos, que abren backdoors, y Spyware, que captura pulsaciones de teclado).
3. **Ransomware:** Secuestro y cifrado total de los archivos del sistema exigiendo un pago monetario para su liberación.
4. **Ataques DoS / DDoS:** Saturación deliberada de los recursos y ancho de banda de un servidor (frecuentemente usando redes Botnet) para inhabilitar servicios.
5. **Fuerza Bruta:** Intentos automatizados masivos de combinaciones para descifrar contraseñas.
6. **Inyección SQL (SQLi):** Inserción de código SQL malicioso en campos de entrada no validados, permitiendo extraer o alterar bases de datos relacionales.
7. **Man-in-the-Middle (MitM):** Intercepción invisible de la comunicación entre dos partes para capturar o manipular datos en tránsito.

## 🛡️ Soluciones y Mitigación Estratégica

Para contrarrestar estas amenazas, es imperativo establecer controles técnicos a nivel de red, aplicación y nube:

- **Autenticación Multifactor (MFA):** La barrera más efectiva contra ataques de fuerza bruta y phishing.
- **Gestión de Vulnerabilidades:** Actualización y parcheo constante de sistemas operativos, frameworks y dependencias.
- **Segmentación de Red:** Dividir la infraestructura en subredes aisladas para evitar el movimiento lateral de atacantes.
- **Respaldos Inmutables (WORM):** Backups periódicos aislados de la red principal para garantizar la recuperación ante un desastre de Ransomware.
- **Firewalls Web (WAF):** Filtrado de tráfico HTTP para bloquear inyecciones de código y ataques dirigidos a las aplicaciones.

## 🎓 Buenas Prácticas Personales

- Usar gestores de contraseñas y claves complejas.
- Evitar transacciones y accesos sensibles en redes Wi-Fi públicas.
- Mantener respaldos redundantes (ej. disco externo físico + nube).

---

_Documento de referencia basado en la Carrera de Ingeniería de Sistemas._
