# Checklist de Seguridad AWS
La idea es crear un checklist que sea de fácil consulta y en español para ayudar a todo aquel que necesite asegurar sus cargas, cuentas, servicios en la nube de Amazon AWS.

Son bienvenidos todos los aportes, corrección de errores de cualquier tipo, ideas, consejos, etc.

La lista se estará actualizando y creciendo todo el tiempo mientras vamos teniendo tiempo, se nos va ocurriendo nuevas cosas, vamos conociendo más sobre la plataforma y Amazon agrega nuevos servicios y opciones, vamos a tener videos para cada recomendación y más documentación.

Administración de Identidad y Acceso IAM - Identity and Access Management

Habilita el doble factor de autenticación (2FA) para la cuenta root como mínimo, habilitar 2FA en todas tus cuentas es lo mejor
Evita usar la cuenta de root o sus llaves como cuenta de uso diario
Asigna los permisos mínimos necesarios a cada cuenta que crees, si un usuario va a usar solo EC2 no necesita acceso a S3 por ejemplo
Rota las Llaves de Acceso (Access Keys) periódicamente
Asegúrate de tener una política de passwords robusta
Asigna permisos a los usuarios basado en grupos de usuario (User Groups)
Da acceso a los recursos a través de IAM Roles
Asigna los permisos mínimos necesarios cuando crees políticas IAM (IAM Policies) 
Agrega las políticas IAM (IAM Policies) a Grupos o Roles cuando las crees
Usa condiciones siempre que sea posible a las políticas (Policies) cuando des permiso a algún recurso
Deshazte de credenciales innecesarias, cuentas que están inactivas o ya no se usan
Usa Roles (IAM Roles) para asignar acceso a aplicaciones o instancias EC2
