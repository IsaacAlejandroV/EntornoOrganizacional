**Área**: Almacenamiento y edición colaborativa de documentos  
**Organización**: NovaSoft Solutions

### 1. Nextcloud Hub + Collabora Online

| **Licencia** | AGPL v3 |
| **Último commit** | Abril 2025 |
| **Contribuidores** | ~1,500 en GitHub |
| **Documentación** | Excelente — https://docs.nextcloud.com |
| **Curva de aprendizaje** | Media |
| **Compatibilidad** | Docker, Linux, S3, SSO/SAML/OAuth2 |

**Pros**: Almacenamiento y edición colaborativa en tiempo real, SSO con Keycloak, calendario, contactos, gran ecosistema de apps.  
**Contras**: Collabora Online requiere un contenedor adicional; más recursos que Seafile.

---

### 2. OnlyOffice Docs

| **Licencia** | AGPL v3 |
| **Último commit** | Marzo 2025 |
| **Contribuidores** | ~400 en GitHub |
| **Documentación** | Buena — https://api.onlyoffice.com |
| **Curva de aprendizaje** | Baja-Media |
| **Compatibilidad** | Docker, Linux, Windows |

**Pros**: Excelente compatibilidad con formatos Microsoft Office, interfaz muy familiar.  
**Contras**: El servidor de almacenamiento es menos maduro que Nextcloud.

---

### 3. Seafile CE

| **Licencia** | Apache 2.0 (cliente) / GPL v2 (servidor) |
| **Último commit** | Marzo 2025 |
| **Contribuidores** | ~300 en GitHub |
| **Documentación** | Buena — https://manual.seafile.com |
| **Curva de aprendizaje** | Baja |
| **Compatibilidad** | Linux, Docker |

**Pros**: Sincronización muy eficiente, buena gestión de versiones de archivos.  
**Contras**: No ofrece edición colaborativa en línea en la edición gratuita.

##  Herramienta Seleccionada: **Nextcloud Hub + Collabora Online**

**Justificación**: Nextcloud es la plataforma más completa y madura. Su integración con Collabora permite edición colaborativa en tiempo real compatible con formatos Office, mientras que su soporte nativo para SSO con Keycloak unifica la autenticación con GitLab y Mattermost.
