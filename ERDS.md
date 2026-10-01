# Especificación de Requerimientos de Software (ERS) 
** Proyecto:** App de mensajería instantánea | **Estándar:** IEEE 830-1998
** Autor:** Ulises Villaverde


## 1 Introducción  
El presente documento define los requerimientos para el desarrollo de la aplicación.

## 2. Glosario de Términos 
* **Cifrado punto a punto:** Método de seguridad que evita la lectura de mensajes por terceros.
* **Notificación Push:** Mensaje de alerta enviado al dispositivo de usuario.

## 3. Requerimientos Funcionales  (EL QUÉ)
* **RF01:** El sistema debe permitir registrar usuarios mediante número telefónico.
* **RF02:** El sistema debe permitir enviar mensajes de texto en chats individuales.
* **RF03:** El sistema debe permitir eliminar mensajes previamente enviados para todos los destinatarios.
* **RF04:** El sistema debe permitir iniciar sesión mediante el número telefónico registrado.
* **RF05:** El sistema debe permitir crear y editar un perfil de usuario.
* **RF06:** El sistema debe permitir buscar usuarios registrados.

## 4. Requerimientos No Funcionales (EL CÓMO)
* **RNF01 (Seguridad) :** Los mensajes deben almacenarse encriptados en la base de datos.
* **RNF02 (Rendimiento):** El tiempo de envío de mensajes debe ser menor a 2 segundos.
* **RNF03 (Seguridad):** El sistema debe solicitar autenticación para acceder a una cuenta registrada.
* **RNF04 (Seguridad):** La aplicación debe cerrar automáticamente la sesión después de 5 minutos de inactividad.

## 5.Requerimientos de Dominio
* **RD01:** El servicio web debe configurarse bajo la extensión de dominio '.net'. 
