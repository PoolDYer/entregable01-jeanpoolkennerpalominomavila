# Entregable 01

## nombre
Jean Pool Kenner Palomino Mavila    
## Descripción
**SIFITUR Huamanga** (Sistema Integral de Fiscalización de Hospedajes y Servicios Turísticos en Huamanga) es una plataforma tecnológica institucional diseñada para modernizar, articular y transparentar el proceso integral de empadronamiento, inspección técnica in situ, control de vigencias documentales (licencias municipales, ITSE y constancias de MINCETUR) y seguimiento de subsanaciones en la provincia de Huamanga, en coordinación con la DIRCETUR Ayacucho y la Municipalidad Provincial de Huamanga[cite: 8]. La solución articula un ecosistema multicanal compuesto por una aplicación móvil con soporte *offline-first* que permite a los inspectores levantar actas digitales con firmas manuscritas y capturar evidencias fotográficas con GPS forzado en zonas sin conectividad, una consola web administrativa para la planificación de operativos territoriales y evaluación de descargos, y un portal web ciudadano de acceso público orientado a resolver en menos de 200 ms la verificación de formalidad mediante el escaneo de sellos QR oficiales[cite: 8]. Sustentada en una arquitectura desacoplada de cómputo sin estado (*stateless*), aceleración en memoria Redis, persistencia transaccional con réplicas de lectura, procesamiento asíncrono y almacenamiento redundante de objetos en S3, la plataforma está dimensionada para absorber picos estacionales de hasta 30,000 visitantes únicos durante festividades como Semana Santa e interoperar con plataformas clave del Estado (SUNAT, MINCETUR, OpenStreetMap y pasarelas de notificación), garantizando seguridad perimetral mediante control de acceso por roles (RBAC), auditoría inmutable en bitácoras *append-only* y estricto cumplimiento de la Ley N° 29733 de Protección de Datos Personales.

## Caso de estudio
Sistema Integral de Fiscalización de Hospedajes y Servicios Turísticos en Huamanga (SIFITUR Huamanga)

## Curso
Arquitectura de Software 