**Área**: Integración continua y entrega continua  
**Organización**: NovaSoft Solutions

### 1. Jenkins

| **Licencia** | MIT |
| **Último commit** | Abril 2025 |
| **Contribuidores** | ~1,800 en GitHub |
| **Documentación** | Excelente — https://www.jenkins.io/doc |
| **Curva de aprendizaje** | Alta |
| **Compatibilidad** | Java, Docker, Kubernetes, Linux, Windows |

**Pros**: El más veterano y con mayor ecosistema de plugins (1,800+), muy flexible.  
**Contras**: Configuración compleja (Groovy/Jenkinsfile), alto consumo de recursos, interfaz desactualizada.

### 2. Drone CI

| **Licencia** | Apache 2.0 |
| **Último commit** | Febrero 2025 |
| **Contribuidores** | ~350 en GitHub |
| **Documentación** | Buena — https://docs.drone.io |
| **Curva de aprendizaje** | Media |
| **Compatibilidad** | Docker-native, Linux |

**Pros**: Diseño Docker-native muy elegante, pipelines simples en YAML.  
**Contras**: Desarrollo ralentizado desde 2023, menos actualizaciones recientes.


### 3. Woodpecker CI

| **Licencia** | Apache 2.0 |
| **Último commit** | Abril 2025 |
| **Contribuidores** | ~250 en GitHub |
| **Documentación** | Buena — https://woodpecker-ci.org/docs |
| **Curva de aprendizaje** | Media-Baja |
| **Compatibilidad** | Docker-native, Linux, GitLab nativo |

**Pros**: Fork activo de Drone con desarrollo continuo, integración nativa con GitLab CE, pipelines YAML ligeros, bajo consumo de recursos.  
**Contras**: Comunidad más pequeña que Jenkins.

##  Herramienta Seleccionada: **Woodpecker CI**

**Justificación**: Woodpecker CI hereda la elegancia Docker-native de Drone con una comunidad más activa. Su integración nativa con GitLab CE como proveedor de autenticación y disparador de pipelines, junto con su bajo consumo de recursos, lo hace ideal para el entorno de NovaSoft.
