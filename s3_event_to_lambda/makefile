# Configuración de Event S3 de Creación de Objeto e invocación de una Función Lambda que hace un envío de mail via SNS
# En la Función Lambda se crea una URL Preasignada de S3 para enviarse por correo y nos brinde un enlace de descarga
aws cloudformation create-stack --stack-name nut-envio-mail-dev --template-body file://template.yml --capabilities CAPABILITY_NAMED_IAM --profile isbryanfm

aws cloudformation update-stack --stack-name nut-envio-mail-dev --template-body file://template.yml --capabilities CAPABILITY_NAMED_IAM --profile isbryanfm

aws cloudformation delete-stack --stack-name nut-envio-mail-dev --profile isbryanfm


## Crear previamente el parametro MAIL con el valor del correo para la suscripción SNS en el servicio AWS Systems Manager 
## Parameter Store