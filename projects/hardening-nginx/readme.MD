# Nginx Hardening & Advanced Configuration / Hardening y configuración avanzada de Nginx

---

## Español

### Descripción

Documentación de la implementación y hardening de un servidor **Nginx** en Linux, incluyendo medidas de seguridad y configuración avanzada para entornos de producción.

### Escenario

- **Servidor:** Debian con Nginx instalado  
- Configuración de puertos personalizados y server blocks (sitios virtuales)  
- Control de acceso y restricciones basadas en IP y autenticación  

### Pasos clave

1. Instalación de Nginx y cambio de puerto de escucha  
2. Creación de server blocks para múltiples sitios  
3. Hardening de configuración:  
   - Ocultación de versión (server_tokens off)  
   - Deshabilitación de listado de directorios (autoindex off)  
   - Limitación de tamaño de subida (client_max_body_size)  
   - Cabeceras de seguridad anti-clickjacking (X-Frame-Options)  
4. Control de acceso: IP whitelist y autenticación por contraseña  
5. Reglas avanzadas:  
   - Bloqueo por User-Agent sospechoso  
   - Página 404 personalizada  

---

## English

### Description

Documentation for the implementation and hardening of an **Nginx** server on Linux, including security measures and advanced configuration for production environments.

### Scenario

- **Server:** Debian with Nginx installed  
- Custom listening ports and server blocks (virtual hosts)  
- Access control and restrictions based on IP and authentication  

### Key Steps

1. Install Nginx and change the listening port  
2. Create server blocks for multiple websites  
3. Configuration hardening:  
   - Hide Nginx version (server_tokens off)  
   - Disable directory listing (autoindex off)  
   - Limit upload size (client_max_body_size)  
   - Anti-clickjacking headers (X-Frame-Options)  
4. Access control: IP whitelisting and password authentication  
5. Advanced rules:  
   - Block suspicious User-Agents  
   - Custom 404 error page  
