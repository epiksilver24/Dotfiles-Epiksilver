# Dotfiles de BSPWM

Este repositorio contiene mis dotfiles para el gestor de ventanas BSPWM en Linux. Incluye configuraciones para el panel Polybar, el lanzador Rofi, el terminal Alacritty y algunos otros programas comunes.
## Contenido

    bspwm: configuraciones para BSPWM
    sxhkd: configuraciones para SXHKD (simple X hotkey daemon)
    polybar: configuraciones para Polybar
    rofi: configuraciones para Rofi (un lanzador de aplicaciones)
    alacritty: configuraciones para Alacritty (un terminal rápido)
    vim: configuraciones para Vim (un editor de texto)

## Requisitos

Estos dotfiles están diseñados para funcionar en una instalación de Linux con BSPWM. Además, es necesario tener instalados algunos programas adicionales y fuentes para usar todas las características incluidas en el repositorio:

 -   Polybar: Un panel altamente configurable para barra de tareas y otras notificaciones. Sitio web de Polybar
 -   Rofi: Un lanzador de aplicaciones que puede ser utilizado con BSPWM. Sitio web de Rofi
 -   Alacritty: Un emulador de terminal rápido y moderno. Sitio web de Alacritty
 -   Vim: Un editor de texto. Sitio web de Vim
 -   etBrains Mono: Una fuente de programación diseñada para mejorar la legibilidad del código. [Sitio web de JetBrains Mono](https://www.jetbrains.com/lp/mono/)



## Instalación

    Clona este repositorio en tu máquina local:

  
```
https://github.com/epiksilver24/Dotfiles-Epiksilver.git
```


Copia los archivos de configuración en sus ubicaciones correspondientes:

```
    cd dotfiles-bspwm
    cp -r bspwm/ ~/.config/
    cp -r sxhkd/ ~/.config/
    cp -r polybar/ ~/.config/
    cp -r rofi/ ~/.config/
    cp -r alacritty/ ~/.config/
    cp -r zsh/ ~/.zsh/
    cp -r vim/ ~/.vim/
```

Reinicia BSPWM y otros programas relevantes para cargar las nuevas configuraciones.

## Créditos

Estos dotfiles están inspirados en y basados en muchos otros dotfiles de BSPWM en línea. Agradecimientos especiales a la comunidad de r/unixporn por su inspiración y ayuda.

