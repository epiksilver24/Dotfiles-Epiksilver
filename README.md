# Dotfiles de BSPWM

Este repositorio contiene mis dotfiles para el gestor de ventanas BSPWM en Linux. Incluye configuraciones para el panel Polybar, el lanzador Rofi, el terminal Alacritty y algunos otros programas comunes.

[![2023-04-13-23-38-00-screenshot.png](https://i.postimg.cc/0Q4yfc85/2023-04-13-23-38-00-screenshot.png)](https://postimg.cc/mzQ4Z3zK)

[![2023-04-13-23-37-45-screenshot.png](https://i.postimg.cc/cLcYmyPs/2023-04-13-23-37-45-screenshot.png)](https://postimg.cc/nXCCF5H5)

## Contenido

    bspwm: configuraciones para BSPWM
    sxhkd: configuraciones para SXHKD (simple X hotkey daemon)
    polybar: configuraciones para Polybar
    rofi: configuraciones para Rofi (un lanzador de aplicaciones)
    alacritty: configuraciones para Alacritty (un terminal rápido)
    neovim: configuraciones para Neovim (un editor de texto)
    ranger: configuraciones para (un file Manager)
    

## Requisitos

Estos dotfiles están diseñados para funcionar en una instalación de Linux con BSPWM. Además, es necesario tener instalados algunos programas adicionales y fuentes para usar todas las características incluidas en el repositorio:

 -   Polybar: Un panel altamente configurable para barra de tareas y otras notificaciones. Sitio web de Polybar
 -   Rofi: Un lanzador de aplicaciones que puede ser utilizado con BSPWM. Sitio web de Rofi
 -   Alacritty: Un emulador de terminal rápido y moderno. Sitio web de Alacritty
 -   Neoim: Un editor de texto. Sitio web de Vim
 -   Nitrogen: Un programa para establecer el fondo de escritorio 
 -   JetBrains Mono: Una fuente de programación diseñada para mejorar la legibilidad del código. [Sitio web de JetBrains Mono](https://www.jetbrains.com/lp/mono/)
 -   Iosevka: Una fuente de programación monoespaciada, diseñada para ser clara, nítida y fácil de leer. [Sitio web de Iosevka](https://typeof.net/Iosevka/)
 -   Material Icons: Una fuente de iconos diseñada por Google. 
 -   Feather: Una fuente de iconos con un diseño limpio y ligero. [Sitio web de Featheri](https://feathericons.com/)
 -   Icomoon: Una fuente de iconos y herramienta de generación de iconos personalizados. [Sitio web de Icomoon](https://icomoon.io/)

```
pacman -S polybar bspwm rofi alaritty neovim nitrogen ttf-material-icons 
```

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
    cp -r vim/plugged/ ~/.vim/
    cp -r nvim/ ~/.config/
    cp -r ranger/ ~/.confg/
```

Reinicia BSPWM y otros programas relevantes para cargar las nuevas configuraciones.

## Créditos

Estos dotfiles están inspirados en y basados en muchos otros dotfiles de BSPWM en línea. Agradecimientos especiales a la comunidad de r/unixporn por su inspiración y ayuda.

