## Alojar-un-sitio-web-est-tico-de-S3-con-Terraform

- Utiliza Terraform para crear un recurso aws_s3_bucket que represente tu bucket de S3. Especifica el nombre del bucket y cualquier configuración adicional que desees, como la política de acceso público y las opciones de configuración del sitio web.
Subir los archivos estáticos: **index.html y error.html**.

- Utiliza Terraform para cargar los archivos estáticos de tu sitio web al bucket de S3 creado. Puedes usar el recurso aws_s3_bucket_object para cada archivo que desees cargar.
Configurar el sitio web:

- Utiliza Terraform para configurar el bucket de S3 para alojar un sitio web estático. Esto implica configurar la propiedad website del bucket con las opciones apropiadas, como el documento de índice y el documento de error.
Aplicar la configuración:

- Ejecuta terraform init para inicializar Terraform en tu directorio de trabajo, luego ejecuta terraform apply para aplicar la configuración y crear los recursos en AWS.
Desplegar el sitio web:

- Después de aplicar la configuración, tu sitio web estático debería estar alojado en el bucket de S3 y disponible en Internet. Puedes acceder al sitio web utilizando la URL proporcionada por S3.
