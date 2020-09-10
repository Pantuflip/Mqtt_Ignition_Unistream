En este folder se encuentra el backup de la aplicación de Ignition
Está aplicación estuvo corriendo en un servidor en la nube de Google.

La versión de IGNITION que se está usando es  8.0.15 (b2020072213)

En el backup del HMI dentro de los tags 
TAGS 
  Trans
    EdgeBox
      DeviceBox
        MQTT1
        Temperature3
Se encuentran ejemplo de código para poder publicar datos al broker sin usar la estructura tipica de Ignition.
Este código fue necesario, ya que el PLC Unistream no es capas de leer la estructura que envia Ignition.
"SparkPlug"
