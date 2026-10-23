# Escenario de usuario para recuperar la contraseña en HENDERSON
Objetivo: recuperar el acceso a la cuenta y establecer una nueva contraseña.

La recuperación de la contraseña de la cuenta está disponible desde la página de acceso: https://henderson.ru/hlogin/

1. El usuario pulsa el botón «Войти» (Iniciar sesión) en la página principal.

2. El sistema muestra las opciones de acceso por correo electrónico o por número de teléfono, así como el botón «Забыли пароль?» (¿Olvidaste tu contraseña?).

3. El usuario pulsa «Забыли пароль?».

4. El sistema muestra una ventana modal con dos opciones para recuperar la contraseña: por correo electrónico o por teléfono.


## Recuperación por teléfono

1. El usuario selecciona la opción «по телефону» (Por teléfono).

2. El sistema muestra un campo para introducir el número de teléfono.

3. El usuario introduce su número de teléfono y pulsa «Отправить» (Enviar).

4. El sistema muestra el campo «Проверочный код» (Código de verificación) y envía un código por SMS o Viber.

5. El usuario introduce el código de seis dígitos y pulsa «Отправить».

6. El sistema muestra el área personal, donde el usuario establece una nueva contraseña.


## Reenvío del código

Para solicitar otro código, el usuario pulsa «Код не пришел, повторить отправку» (No he recibido el código, reenviar).


## Preguntas pendientes de verificación

¿El sistema acepta el primer código después de solicitar uno nuevo?

¿Cómo responde el sistema si se introduce un código demasiado corto, un valor con letras o caracteres especiales, o si se deja el campo vacío?


## Recuperación por correo electrónico

1. El usuario selecciona la opción «по email» (Por correo electrónico).

2. El sistema muestra un campo para introducir el correo electrónico.

3. El usuario introduce su dirección de correo electrónico. El sistema valida el formato y el usuario pulsa «Отправить» (Enviar).

4. El sistema muestra el mensaje «На Ваш адрес мы направили письмо со ссылкой. Перейдите по ней, чтобы подтвердить корректность адреса» (Hemos enviado un correo con un enlace a tu dirección. Sigue el enlace para confirmar la dirección).

Después de unos segundos, aparece el botón «Письмо не пришло, повторить отправку» (No he recibido el correo, reenviar).

5. El sistema envía un correo con un enlace para acceder al área personal.


## Preguntas pendientes de verificación

¿Cómo responde el sistema si se introduce una dirección de correo electrónico no registrada?

¿Cómo responde el sistema si la dirección no contiene «@» o no incluye un dominio?

¿Qué límites de longitud se aplican a la dirección de correo electrónico?

Alcance: esta rama describe el proceso hasta el envío del correo. No se documentó la continuación mediante el enlace recibido.
