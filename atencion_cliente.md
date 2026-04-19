# **Reporte de Atención al Cliente y Soporte: E-Pick**

## **1\. Percepción del Usuario y Datos de Reclamos**

La opinión pública sobre el servicio de soporte de E-Pick se divide drásticamente según el tipo de usuario (remitente/vendedor vs. destinatario/comprador).

### **Métricas Cuantitativas (Fuente: tuQuejaSuma)**

* **Índice de Resolución:** 53% de los reclamos son marcados como solucionados.

* **Tipología de Reclamos Frecuentes:**  
  1. **Falsos positivos de entrega:** Paquetes marcados como "dirección incorrecta" o "destinatario ausente" cuando el usuario se encontraba en el domicilio.  
  2. **Falta de trazabilidad humana:** Imposibilidad de contactar a un representante tras un problema con el código de seguimiento.  
  3. **Demoras operativas:** Envíos que superan el plazo estipulado (ej. E-PICK Flex de 2 a 3 días o Route de 4 días) sin actualización en el panel.

  4. **Extravíos o robos:** Reportes de paquetes escaneados en origen pero no ingresados al sistema central.

### **Análisis Cualitativo (Fuente: Reddit y Reseñas de Google)**

* **Destinatarios:** Manifiestan alta frustración frente a incidencias. La crítica principal (ej. subforo r/Cordoba) es la **ausencia de canales sincrónicos** (no hay teléfono fijo, ni número de WhatsApp para atención humana en tiempo real).  
* **Remitentes (E-commerce):** La percepción mejora significativamente. Los vendedores que utilizan integraciones (Tiendanube, Empretienda) valoran la automatización del proceso, ya que relegan el soporte logístico a la plataforma de E-Pick, disminuyendo su propia carga de atención al cliente.

## **2\. Estructura Operativa del Soporte (Cómo lo hacen)**

Acorde a su modelo *asset-light* y de alta escalabilidad, E-Pick opera su atención al cliente bajo un esquema de **deflexión de tickets** (evitar que el usuario llegue a un humano) y **automatización extrema**:

* **Autogestión y Notificaciones Push:** El sistema se basa en enviar correos electrónicos automatizados en cada hito del recorrido (retiro, en camino, entrega fallida, etc.) tanto al remitente como al destinatario.

* **Soporte Nivel 1 (Filtro):** Utilizan un Bot disponible 24/7 para consultas inmediatas sobre estados de envío.  
* **Soporte Nivel 2 (Asíncrono):** Para los vendedores (usuarios de la plataforma), el reclamo se escala a través de un sistema de tickets interno en su panel de administrador (Ruta: *Centro de ayuda → Enviar consulta*).  
* **Logística Inversa:** Según la documentación técnica de sus integraciones, actualmente E-Pick no cuenta con un proceso automatizado de logística inversa (devoluciones y cambios), lo que obliga al vendedor a gestionarlo manualmente y genera cuellos de botella en la atención al cliente.

