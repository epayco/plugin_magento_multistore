# Plugin Integración ePayco para Magento 2 multi tienda(2.x)

Este plugin permite integrar ePayco como medio de pago para sus diferentes tiendas en Magento 2.

**Si usted tiene alguna pregunta o problema, no dude en ponerse en contacto con nuestro soporte técnico: desarrollo@payco.co.**

## Versiones
* [ePayco plugin Magento multi tienda v2.5.0](https://github.com/epayco/plugin_magento_multistore/releases/tag/2.5.0).


## Iniciando

En estas instrucciones usted encontrará las indicaciones para instalar el módulo y activarlo en su instalación de Magento 2.

### Prerrequisitos

Necesita tener instalado Magento 2 con todas sus dependencias y una cuenta en ePayco.


### Installing


1- Clonar el repositorio en su máquina.

```
git clone https://github.com/epayco/plugin_magento_multistore.git
```
2- Renombrar la carpeta creada como "PagoEpayco" y copiar el contenido de su instalacion en magento en la ruta: ruta/de/su/instalacion/app/code/Pago/
```
cd magento2
cp . -R /ruta/de/su/instalacion/app/code/Pago/
```
3- Dirigirse a la ruta de instalación de su magento 2 y ejecutar los siguientes comandos
```
php bin/magento module:enable PagoEpayco_Payco
php bin/magento setup:upgrade
php bin/magento setup:di:compile
```
4- Si desea puede ejecutar el siguiente comando para verificar que el modulo esté habilitado
```
php bin/magento module:status
```

## Finalización

Ya puede ingresar al área de administración de Magento2 e ingresar a Tiendas->configuracion->Metodos de pago
y encontrará el panel de ePayco para configurarlo.


