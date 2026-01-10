# Configuración i3 Window Manager

La ruta de configuración de i3 se encuentra en ~/.**i3/config**

## Configuración de teclas de volumen
Primero usar comando para determinar el sink 

--- pactl list short sinks

Luego determinar el número del sink, generalmente es el que termina en analog-stereo
Finalmente el número de sink debe ser reemplazado en las lineas de configuración de .i3/config 

## Enlaces para configurar temas de i3bar

Es posible personalizar i3Bar o optar por usar polybar.

- Personalización de i3Bar: https://thomashunter.name/i3-configurator/
- https://www.youtube.com/watch?v=lGHj9l2i5mc

## Enlaces para config. de temas para diversas cosas

Repositorio para personalizar diversas herrmaientas:  https://github.com/catppuccin/i3?tab=readme-ov-file

## Enlaces para config polybar
Por defecto i3 usa i3Bar, pero un mejor manejo de la barra superior se usó polybar, previamente se debe instalar y configurar.

- Documentación oficial: https://github.com/polybar/polybar
- Personalización con temas: https://github.com/catppuccin/polybar/tree/main

La ruta del archivo de configuración de polybar esta en **~/.config/polybar/config.ini**

Para los colores se uso un archivo externo ubicado en la misma ruta: colors.ini
