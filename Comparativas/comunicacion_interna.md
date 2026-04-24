# Comparativa: Comunicación Interna

**Área**: Comunicación interna  
**Organización**: NovaSoft   
**Restricción clave**: Self-hosted obligatorio, privacidad de datos

---

## Herramientas Evaluadas

### 1. Mattermost CE

| Criterio | Detalle |
|----------|---------|
| **Licencia** | MIT (CE) / Comercial (EE) |
| **Último commit** | Abril 2025 |
| **Contribuidores** | ~1,200 en GitHub |
| **Documentación** | Excelente — https://docs.mattermost.com |
| **Curva de aprendizaje** | Media |
| **Compatibilidad** | Docker, Kubernetes, Linux, SSO/LDAP |

**Pros**: Integración nativa con GitLab (webhooks, bots), apps nativas multiplataforma, LDAP en versión gratuita, comunidad muy activa.  
**Contras**: La edición gratuita tiene límites en algunos plugins avanzados.

---

### 2. Rocket.Chat

| Criterio | Detalle |
|----------|---------|
| **Licencia** | MIT |
| **Último commit** | Abril 2025 |
| **Contribuidores** | ~900 en GitHub |
| **Documentación** | Buena — https://docs.rocket.chat |
| **Curva de aprendizaje** | Media-Alta |
| **Compatibilidad** | Docker, Kubernetes, MongoDB requerido |

**Pros**: Muchas integraciones, videoconferencia integrada, muy personalizable.  
**Contras**: Requiere MongoDB, mayor consumo de recursos, configuración más compleja.

---

### 3. Matrix / Element

| Criterio | Detalle |
|----------|---------|
| **Licencia** | Apache 2.0 (Synapse) / Apache 2.0 (Element) |
| **Último commit** | Abril 2025 |
| **Contribuidores** | ~600 en GitHub |
| **Documentación** | Buena — https://matrix.org/docs |
| **Curva de aprendizaje** | Alta |
| **Compatibilidad** | Linux, Docker, protocolo federado |

**Pros**: Federación entre servidores, cifrado E2E nativo, protocolo abierto estándar.  
**Contras**: Curva de aprendizaje alta, mayor complejidad operativa, rendimiento variable.

---

## Opción -> **Mattermost CE**

Mattermost ofrece el mejor balance entre funcionalidad, facilidad de despliegue e integración con el resto del ecosistema (especialmente GitLab). Su licencia MIT, comunidad activa y soporte nativo para Docker y SSO la convierten en la opción ideal para NovaSoft.
