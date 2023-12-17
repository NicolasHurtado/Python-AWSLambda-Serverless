# PYTHON + AWS LAMBDA + SERVERLESS FRAMEWORK

## Requisitos previos

Antes de comenzar, asegúrate de tener los siguientes requisitos:

- Node.js, npm y Docker instalados en tu sistema
- Una cuenta de AWS con credenciales de acceso (access key y secret key)

# Instalación
- npm install -g serverless
- npm install --save-dev serverless-python-requirements

## Configuración de AWS

Para configurar tus credenciales de AWS, ejecuta el siguiente comando en tu terminal:

Asegúrate de reemplazar "<tu_access_key>" y "<tu_secret_key>" con tus credenciales de acceso reales de AWS.

serverless config credentials --provider aws --key <ACCESS_KEY> --secret <SECRET_KEY> --profile aws-countries


# Desplegar el servicio
serverless deploy

# Verificar información del servicio desplegado
serverless info


***Nicolas Hurtado C***