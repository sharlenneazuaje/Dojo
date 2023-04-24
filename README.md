# Integrantes
- Sharlenne Azuaje
- Wendy Chiquipa
- Elias Rocca
- Agustín Oliveto

# Proyecto: Dojo Número Uno
![Tinkercad](./img/DojoNúmeroUno-DojoH.png)

# Descripción
Este proyecto tiene como objetivo actualizar los semáforos de la ciudad para un mejor y óptimo funcionamiento.

# Función Principal

Funcion 1: La funcion prende el led por un determinado tiempo y lo apaga
~~~ C (lenguaje en el que esta escrito)
void EncenderLedPorTiempo(int led, int tiempo)
{
  EncenderLed(led);
  delay(tiempo);
  ApagarLed(led);
  delay(1000); 
}
~~~
Funcion 2: La funcion enciende el led rojo y al mismo tiempo hace sonar el buzzer dos veces por segundo mientras el led está encendido, luego el led se apaga
~~~ C (lenguaje en el que esta escrito)
void EncenderLedRojoYBuzzerDosVecesPorSegundo(int led, int buzzer)
{
  EncenderLed(led);
  
  for(int i = 0; i < 5; i++)
  {
    SonarBuzzerDosVecesPorSegundo(buzzer);
  }
  
  ApagarLed(led);
  delay(1000);
}
~~~

## :robot: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/dSfbUc2Lc69-dojo-numero-uno-dojo-h/editel?sharecode=Z_gw_-dxREFckGpO99LlNH7r6ErDzkeIa0GSYhMdU7U)


