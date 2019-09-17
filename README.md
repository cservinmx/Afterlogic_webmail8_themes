# Autor Carlos Servín; para sugerencias, mejoras, propuestas de trabajo, etc. Contactame a:
# www.servin.mx
# carlos@servin.mx

Los archivos se deberán subir por ftp a la siguiente ruta:

directorio_raiz_webmail/static/styles/themes

posteriormente se deberá configurar el siguiente archivo Json

directorio_raiz_webmail/data/settings/modules/CoreWebclient.config.json

y en el semgento de código "ThemeList" cambiar los valores por:

"ThemeList": [
        [            
            "LT1",
            "Outlook",
            "Gmail"
        ],
        "array"
    ],

Finalmente ingresar a webmail como superusuario y elegir un tema por default para
aplicar la configuración general, así todos los usuarios tendrán por defecto el
tema elegido.
