<center>

# UT1-A1 Documentación y sistema de control de versiones


</center>

***Nombre:*** Saúl Expósito (user1) y Efrén Pérez (user2).  
***Curso:*** 2º de Ciclo Superior de Desarrollo de Aplicaciones Web.

### ÍNDICE

+ [Introducción](#id1)
+ [Objetivos](#id2)
+ [Material empleado](#id3)
+ [Desarrollo](#id4)
+ [Conclusiones](#id5)


#### ***Introducción***. <a name="id1"></a>

En esta práctica, hemos explorado, aunque sería más bien recordado, cómo usar Git y GitHub en un entorno colaborativo, imitando el flujo de trabajo que se da en equipos de desarrollo. Durante la práctica manejamos diversas herramientas como forks, branches o pull requests, así como tratar con la resolución de conflictos.

#### ***Objetivos***. <a name="id2"></a>

Aprender a colaborar en proyectos de desarrollo utilizando Git y GitHub.

1.- Crear y saber utilizar ramas para que cada colaborador pueda trabajar de forma independiente sin afectar la rama principal.
2.- Crear y gestionar pull requests e issues.
3.- Resolver conflictos al fusionar ramas.
4.- Crear versiones del proyecto y gestionarlas con etiquetas.

#### ***Material empleado***. <a name="id3"></a>

**1.- Hardware.**
- Empleamos ordenadores de sobremesa con acceso a Internet.

**2.- Software.**
- Sistema Operativo: Linux Mint.
- Terminal o consola Bash.
- Navegador web (Mozilla Firefox).
- Git en terminal y GitHub en navegador.

**3.- Configuraciones.**
- Configuración de usuario y correo de forma global con git (git config).
- Utilización de remotos (como "upstream").
- Gestionar permisos mediante claves SSH.

#### ***Desarrollo***. <a name="id4"></a>

**1. Creación del repositorio inicial**

Saúl creó un repositorio público en su cuenta de GitHub con el nombre git-work, añadiendo un fichero README.md y una licencia MIT.
![primera imagen](img/Nuevas/1.png)

**2. Subida de archivos al repositorio**

Saúl clonó el repositorio y añadió los siguientes ficheros al proyecto:

- index.html
- bootstrap.min.css
- cover.css

Después, hizo el commit y los subió a origin/main.

![segunda imagen](img/Nuevas/2.png)
![tercera imagen](img/Nuevas/3.png)

**3. Fork del repositorio por parte de Efrén**

Efrén realizó un fork del repositorio git-work en su cuenta personal.

![cuarta imagen](img/Nuevas/4.png)

**4. Clonado del fork**

Efrén clonó su fork localmente para trabajar en él.

![quinta imagen](img/Nuevas/5.png)

**5. Creación de issue por parte de user1**

Saúl creó la siguiente issue:

![sexta imagen](img/Nuevas/6.png)

**6. Modificación por parte de Efrén**

Efrén creó una rama llamada custom-text, modificó el contenido de index.html para personalizarlo como si fuera una página de presentación para una startup, e hizo un commit con los cambios.

![septimaprimera imagen](img/Nuevas/7-1.png)
![septimasegunda imagen](img/Nuevas/7-2.png)

**7. Pull Request de Efrén a Saúl**

Efrén abrió un Pull Request desde su rama custom-text a la rama main del repositorio original de Saúl.

![octava imagen](img/Nuevas/8.png)

**8. Prueba del PR y modificaciones adicionales**

Saúl añadió el repositorio original como remoto upstream en su local, probó el PR en su máquina y realizó pequeños ajustes sobre el mismo PR, subiendo los cambios directamente a la rama de Efrén.

![novena imagen](img/Nuevas/9.png)
![decima imagen](img/Nuevas/10.png)

**9. Conversación colaborativa en el PR y aprobación**

Ambos usuarios intercambiaron comentarios dentro del PR y cada uno añadió un cambio adicional en el mismo. Finalmente, aprobó el PR, lo fusionó con la rama principal y cerró la issue original.

![undecima imagen](img/Nuevas/11.png)

**10. Sincronización del fork**

Efrén actualizó su rama principal main con los cambios del repositorio original usando el remoto upstream, y de la misma, sincronizó su fork.

![decimosegunda imagen](img/Nuevas/12.png)

**12. Segunda issue: Mejora visual**

Saúl creó una nueva issue titulada "Improve UX with cool colors"

![decimotercera imagen](img/Nuevas/13.png)

**13. Efrén cambió contenido de cover.css**

Efrén cambió algunas líneas en cover.css, creando previamente una rama nueva, cool-colors.

![decimosextaprimera imagen](img/Nuevas/16-1.png)
![decimosextasegunda imagen](img/Nuevas/16-2.png)

**14. Nueva Pull Request de Efrén a Saúl**

Efrén abrió un Pull Request desde su rama cool-colors a la rama main del repositorio original de Saúl.

![decimoseptima imagen](img/Nuevas/17.png)

**15. Resolución de conflictos**

Saúl había previamente realizado modificaciones en cover.css sin haber realizado un git push, por ende, tras la PR de Efrén, tuvo que solventar los conflictos generados.

![decimooctavanovena imagen](img/Nuevas/18-19.png)

**16. Resoluciones y etiquetación final**

Tras resolver los conflictos, Saúl hizo un commit de sus cambios subiéndolos a su main. Finalmente etiquetó la versión del proyecto como la versión 0.1.0, creando una release apuntando hacia la etiqueta. Está etiquetación puede ser observable desde la pçagina principal del repositorio git-work de Saúl.

#### ***Conclusiones***. <a name="id5"></a>

Esta práctica nos ha permitido aprender de forma práctica cómo colaborar en un entorno real de desarrollo con Git y GitHub. Hemos comprendido la importancia del uso de ramas para el trabajo individual, la utilidad de los pull requests para proponer cambios y la gestión de issues para organizar el trabajo. Aunque en definitiva, esta práctica nos ha acercado a las metodologías de trabajo reales en equipos de desarrollo, fomentando tanto la colaboración como la responsabilidad individual en el control de versiones.
