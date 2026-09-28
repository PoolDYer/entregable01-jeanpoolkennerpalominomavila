# Requisitos funcionales

## Catálogo de Requisitos Funcionales
| ID | Requisito funcional |
| :--- | :--- |
| **RF01** | El sistema debe permitir la autenticación de usuarios mediante credenciales seguras, generando tokens JWT protegidos criptográficamente para el acceso a las APIs[cite: 8]. |
| **RF02** | El sistema debe permitir la administración integral de usuarios, asignación de perfiles y privilegios mediante control de acceso basado en roles (RBAC)[cite: 8]. |
| **RF03** | El sistema debe permitir retener la sesión localmente de forma cifrada en la aplicación móvil para habilitar la autenticación y operación en modo desconectado (offline)[cite: 8]. |
| **RF04** | El sistema debe registrar en una bitácora inmutable de solo anexado toda operación de creación, actualización o anulación de actas con usuario, marca temporal e IP[cite: 8]. |
| **RF05** | El sistema debe permitir registrar, actualizar y consultar centralizadamente a prestadores turísticos (hospedajes, restaurantes, agencias y guías) vinculados a su RUC[cite: 8]. |
| **RF06** | El sistema debe controlar las vigencias de licencias municipales, certificados ITSE y registros turísticos, generando alertas preventivas ante vencimientos a menos de 30 días[cite: 8]. |
| **RF07** | El sistema debe calcular de manera algorítmica el nivel de criticidad o riesgo (Bajo, Medio, Alto, Crítico) de cada establecimiento evaluando sus antecedentes e infracciones[cite: 8]. |
| **RF08** | El sistema debe permitir programar operativos tácticos, segmentar polígonos territoriales y sincronizar hojas de ruta digitales hacia los terminales móviles de los inspectores asignados[cite: 8]. |
| **RF09** | El sistema debe permitir el diligenciamiento completo de actas de fiscalización móvil en ausencia de conectividad y conciliarlas transaccionalmente al detectar red[cite: 8]. |
| **RF10** | El sistema debe capturar fotografías in situ exclusivamente desde la cámara del terminal móvil, estampando de forma indeleble coordenadas GPS, fecha y hora oficial[cite: 8]. |
| **RF11** | El sistema debe generar actas digitales en formato PDF inalterable con captura de firma manuscrita sobre pantalla táctil y sellado de integridad mediante hash criptográfico[cite: 8]. |
| **RF12** | El sistema debe gestionar el cómputo de plazos perentorios de subsanación y permitir la carga de pruebas y descargos por parte de los prestadores turísticos[cite: 8]. |
| **RF13** | El sistema debe proveer un portal web ciudadano responsivo y público para la consulta de prestadores autorizados y la resolución inmediata de códigos QR sin requerir inicio de sesión[cite: 8]. |
| **RF14** | El sistema debe generar mapas de calor GIS y tableros con métricas de informalidad distrital y porcentaje de cobertura inspectiva[cite: 8]. |

## Matriz de Trazabilidad (Historias de Usuario vs Requisitos Funcionales)
| Historia de usuario | Requisitos funcionales relacionados |
| :--- | :--- |
| **HU01** Autenticación y sesión segura[cite: 8] | RF01, RF02[cite: 8] |
| **HU02** Gestión de usuarios y control RBAC[cite: 8] | RF02, RF04[cite: 8] |
| **HU03** Restablecimiento de credenciales[cite: 8] | RF01, RF02[cite: 8] |
| **HU04** Consulta pública ciudadana y lector QR[cite: 8] | RF13[cite: 8] |
| **HU05** Fiscalización móvil sin conexión[cite: 8] | RF01, RF03, RF09[cite: 8] |
| **HU06** Fotos con GPS y firmas en actas digitales[cite: 8] | RF10, RF11[cite: 8] |
| **HU07** Programación de operativos y hojas de ruta[cite: 8] | RF07, RF08[cite: 8] |
| **HU08** Evaluación de descargos y plazos de ley[cite: 8] | RF06, RF12[cite: 8] |
| **HU09** Envío de subsanaciones por administrados[cite: 8] | RF05, RF12[cite: 8] |
| **HU10** Tableros analíticos y mapas de calor GIS[cite: 8] | RF14[cite: 8] |
| **HU11** Auditoría e inmutabilidad de registros[cite: 8] | RF04[cite: 8] |