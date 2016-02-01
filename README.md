#HERRAMIENTAS  
**1.- Bitnami MEAN**  
**2.- Sublime Text 3**  [Más info](https://github.com/MARIAEL/INSTALAR-PAQUETES-EN-SUBLIME-TEXT-3)   
       * Bs3  
       * Package Ctrl  
       * Emmet  

**3.- Yeoman**   [Más info](https://github.com/MARIAEL/EC2/blob/master/Yeoman.md)   
       * yo (utiliza generadores como angular, que es un framework creado por Google para usar javascript)    
       * bower (sirve para instalar paquetes)  
       * grunt (arranca el servidor y automáticamente sube los cambios)  

**4.- Github desktop**   [Más info](https://github.com/MARIAEL/GITHUB-DESKTOP)  


#PROCEDIMIENTO  

1.- Creamos la carpeta para el nuevo proyecto web en el entorno gráfico  
C:\bitnami\meanstrack-3.2.1-0\apps\nuevacarpeta  

2.- Arrastramos la nueva carpeta a Github Desktop.  

3.- Vamos al terminal Bitnami y nos situamos en la nueva carpeta (cd apps / cd nuevacarpeta)  
y escribimos  
```bash
yo angular
```  
De este modo nos crea la estructura que necesitamos para la nueva web.  

[MÁS INFO ](https://github.com/MARIAEL/YEOMAN#pasos-para-hacer-una-nueva-web)  

4.- Creamos las páginas necesarias, para ello paramos el servidor (Ctr + d) y ponemos   
```bash
yo angular:route nuevapagina
``` 

[MÁS INFO](https://github.com/MARIAEL/YEOMAN#pasos-para-hacer-una-nueva-web)
