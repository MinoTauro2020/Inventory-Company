# Inventory-Company

# Checklist: Evaluación de Tecnología de una Empresa

## 1. Infraestructura Tecnológica General
- [ ] **Inventario de Hardware**
  - Ordenadores de sobremesa
  - Portátiles
  - Tablets o móviles de la empresa
  - Impresoras y escáneres
  - Otros periféricos (monitores, teclados, ratones, etc.)
- [ ] **Software Usado**
  - Sistemas operativos (Windows, macOS, Linux, etc.)
  - Programas de productividad (Microsoft Office, Google Workspace, etc.)
  - Software específico del sector (CAD, ERP, CRM, etc.)
  - Licencias activas (número, tipo, caducidad)
  - Sistemas heredados (legacy) aún en uso
- [ ] **Máquinas Industriales**
  - Tipo (CNC, robots, etc.)
  - Conexión a la red (IoT, por cable, etc.)
  - Programas para controlarlas o monitorizarlas
- [ ] **Dispositivos IoT**
  - Cantidad y tipo (sensores, cámaras, etc.)
  - Protocolos usados (MQTT, Zigbee, etc.)
  - Seguridad aplicada

## 2. Servidores, Hosting y Servicios Externos
- [ ] **Servidores Físicos**
  - Dónde están (en la oficina o datacenter externo)
  - Cantidad y características (CPU, RAM, almacenamiento)
  - Sistema operativo
  - Para qué sirven (base de datos, aplicaciones, archivos, etc.)
- [ ] **Servidores Virtuales**
  - Proveedor (AWS, Azure, Google Cloud, etc.)
  - Configuración y uso
  - Virtualización local (VMware, Hyper-V, etc.)
- [ ] **Hosting**
  - Webs (proveedor, dominio, CMS como WordPress)
  - Correo electrónico (proveedor, IMAP/POP3)
  - Almacenamiento en la nube (Dropbox, OneDrive, etc.)
- [ ] **Backups (Copias de Seguridad)**
  - Frecuencia (diario, semanal, etc.)
  - Ubicación (local, nube, discos externos)
  - Sistemas cubiertos (servidores, puestos, webs)
  - Método (incremental, diferencial, completo)
  - Pruebas de restauración (última vez realizada)
- [ ] **Servicios y Archivos Externos**
  - Servidor FTP/SFTP: ¿Tienen uno activo? (proveedor, uso: intercambio de archivos, acceso externo)
  - Acceso SSH: ¿Configurado en servidores? (usuarios autorizados, claves o contraseñas)
  - Almacenamiento externo adicional: (p.ej., Google Drive, FTP externo, servidores de terceros)
  - API o servicios web externos: (p.ej., integración con proveedores, clientes)
  - Otros servicios: (p.ej., WebDAV, rsync, sistemas de transferencia gestionada)
- [ ] **Bases de Datos**
  - Tipo (MySQL, PostgreSQL, SQL Server, etc.)
  - Ubicación (local, nube)
  - Tamaño y crecimiento estimado
  - Acceso y permisos configurados

## 3. Redes y Conectividad
- [ ] **Routers**
  - Marca y modelo
  - Configuración (IP fija/dinámica, NAT, etc.)
  - Conexión al ISP (proveedor de internet)
  - Ancho de banda contratado
- [ ] **Switches**
  - Cantidad y capacidad (puertos, velocidad: 1Gbps/10Gbps)
  - Tipo (gestionados o no gestionados)
  - Cómo conectan los dispositivos
- [ ] **Firewalls**
  - Marca y modelo
  - Reglas de seguridad
  - VPN (si la usan)
  - Registro de logs (activado o no)
- [ ] **WiFi**
  - Puntos de acceso (cuántos, cobertura, marca)
  - Seguridad (WPA2, WPA3, contraseña segura)
  - Redes separadas (invitados, empleados, dispositivos IoT)
- [ ] **Conexión entre Activos**
  - Mapa de red (cómo se conectan servidores, puestos, máquinas industriales)
  - Topología (en estrella, bus, anillo, etc.)
  - Cableado (Ethernet Cat5e/Cat6, fibra óptica)
  - Latencia y rendimiento de la red

## 4. Gestión de Usuarios y Seguridad
- [ ] **Active Directory (AD)**
  - ¿Lo tienen o no?
  - Dominio configurado
  - Gestión de usuarios (roles, permisos)
  - Integración con otros sistemas
- [ ] **Tipos de Autenticación de Usuarios**
  - Single Sign-On (SSO) implementado
  - Autenticación Multifactor (MFA): métodos usados (OTP, biometría, app de autenticación, etc.)
  - Políticas de contraseñas (longitud mínima, complejidad, renovación)
  - Integración con sistemas externos (SAML, OAuth, etc.)
- [ ] **Políticas de Seguridad**
  - Antivirus instalado (marca, versión)
  - Actualizaciones automáticas (sistemas y aplicaciones)
  - Backups (frecuencia y ubicación)
  - Auditorías de seguridad (última realizada, periodicidad)
  - Sistemas de detección de intrusos (IDS/IPS)

## 5. Puestos de Trabajo y Empleados
- [ ] **Configuración de Puestos**
  - Hardware por empleado
  - Software según el puesto
  - Acceso a la red (cable o WiFi)
- [ ] **Empleados que se Conectan**
  - Cantidad de usuarios/empleados conectados
  - Acceso a servidores internos
  - Acceso a recursos en la nube
  - Conexión remota (VPN, escritorio remoto)
  - Dispositivos personales permitidos (BYOD)
- [ ] **Comunicación Interna**
  - Correo electrónico
  - Mensajería (Teams, Slack, etc.)
  - Telefonía (VoIP, líneas tradicionales)
- [ ] **Herramientas de Desarrollo**
  - Entornos usados (Git, Docker, IDEs, etc.)
  - Repositorios (GitHub, GitLab, Bitbucket)
  - CI/CD implementado (Jenkins, GitLab CI, etc.)

## 6. Otros Detalles a Mirar
- [ ] **Monitorización y Mantenimiento**
  - Herramientas de monitorización (Nagios, Zabbix, etc.)
  - Registro de problemas o soporte técnico
  - SLA con proveedores (tiempo de respuesta, disponibilidad)
- [ ] **Documentación**
  - Manuales de configuración
  - Diagramas de red
  - Inventario al día
- [ ] **Escalabilidad**
  - Capacidad para añadir más dispositivos o usuarios
  - Planes para actualizar la tecnología
- [ ] **Cumplimiento Normativo**
  - RGPD u otras normativas aplicables
  - Registro de incidencias de seguridad
- [ ] **Gestión de Energía**
  - SAIs (sistemas de alimentación ininterrumpida)
  - Consumo energético de la infraestructura
