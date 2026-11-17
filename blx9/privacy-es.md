# Política de privacidad

Localizar+ · Última actualización: 17 de noviembre de 2026

## 1. Acerca de esta política

Localizar+ (la «App») es una app para iOS que permite compartir manualmente una posición cada vez con las personas que autorizas. Esta política explica qué datos trata la App, dónde se almacenan y qué opciones tienes. La App la ofrece el desarrollador de Localizar+ («nosotros»). Contacto: https://github.com/xxlcmb9/doc/issues.

## 2. Datos que tratamos

- Número de compartición: un número aleatorio de 9 dígitos generado en tu dispositivo. No se requiere correo, teléfono, contraseña ni cuenta social, y no pedimos tu nombre, contactos ni fotos.
- Ubicación que confirmas: latitud, longitud, altitud y marcas de tiempo, enviadas solo al pulsar compartir y aceptar la confirmación.
- Lista de permitidos y lista de bloqueados: los números que autorizas o bloqueas, guardados en tu perfil.
- Mensajes que nos envías: si escribes al soporte desde la página de soporte.

## 3. Cómo funciona la compartición

- Nada se publica de forma automática, en segundo plano ni por temporizador. Cada registro requiere tu confirmación expresa y puede cancelarse.
- Cada registro envía una única posición que sustituye a la anterior. La App no guarda historial.
- El registro caduca en la App una hora después de publicarse y deja de mostrarse a otros usuarios. La caducidad es solo una regla de visualización: no elimina el archivo del almacenamiento en la nube. El archivo se elimina al retirar la compartición o borrar tu identidad.
- Mostrar tu propia posición en el mapa local es un ajuste opcional independiente y no comparte nada.

## 4. Dónde se almacenan los datos

Los registros compartidos, las listas y el índice de números se almacenan en Tencent Cloud Object Storage (COS), región ap-nanjing (China continental), con credenciales temporales emitidas por el endpoint de autenticación de la App. Tu número y tus listas también se guardan en el dispositivo. No mantenemos una base de datos analítica separada de ubicaciones. Tras el borrado, las copias de seguridad del proveedor pueden conservarse durante un periodo limitado.

## 5. Servicios de terceros

- Tencent Cloud COS: alojamiento de los registros y las listas.
- Google AdMob y Google User Messaging Platform: anuncios y diálogos de consentimiento; Google puede recibir identificadores del dispositivo, dirección IP e interacciones con anuncios.
- Apple: App Store, compras dentro de la app y pagos. Nunca recibimos los datos de tu tarjeta.
- open-elevation.com: solo cuando eliges un punto en el mapa para consultar la altitud se envía esa coordenada, y puedes cancelar antes.

No vendemos datos personales.

## 6. Anuncios y seguimiento

Los anuncios financian la versión gratuita. En iOS 14.5 o posterior la App solicita el permiso de Seguimiento de Apps (ATT) cuando es necesario; si lo rechazas verás anuncios, pero no personalizados. Puedes cambiar tu elección en Ajustes → Privacidad y seguridad → Seguimiento y en las opciones de consentimiento de la App.

## 7. Seguridad y sus límites

El tráfico usa HTTPS/TLS y credenciales temporales con caducidad. Antes de cada consulta la App comprueba la lista de bloqueados y la de permitidos en ambos lados; el bloqueo prevalece. Este control lo aplica la App y no está aislado en el servidor, por lo que no impide que quien obtenga credenciales válidas lea objetos del bucket, ni que un destinatario haga capturas o copias. Comparte solo lo que puedas permitirte divulgar.

## 8. Tus opciones

- Retirar la compartición en cualquier momento (elimina el registro compartido).
- Bloquear o desbloquear personas; desbloquear no restaura la lista de permitidos.
- Ocultar tu propia posición en el mapa local.
- Borrar tu identidad en la App: se eliminan ubicación, perfil y entrada del índice y después los datos locales. La compra de por vida no se ve afectada.
- Revocar el acceso a la ubicación en Ajustes de iOS; el mapa, la brújula y la altitud dejarán de funcionar, pero el resto de la App seguirá disponible.
- Contactarnos en el enlace de soporte para solicitar acceso, rectificación o supresión de los datos asociados a tu número.

## 9. Menores

La App no está dirigida a menores de 13 años ni por debajo de la edad mínima de tu país. No recopilamos sus datos a sabiendas. Si crees que un menor ha compartido datos, escríbenos y los eliminaremos.

## 10. Cambios y contacto

Podemos actualizar esta política; la fecha superior cambiará y la nueva versión se publicará en esta página. Dudas: https://github.com/xxlcmb9/doc/issues.

Soporte: https://github.com/xxlcmb9/doc/issues
