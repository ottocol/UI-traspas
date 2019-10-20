
#Interfaz de usuario en dispositivos móviles
##iOS, sesión 5: Controladores contenedores
##Tab bar y Navigation Controllers


---

##Puntos a tratar

- Tab bar controllers
- Navigation Controllers
- Tablas maestro/detalle y navigation controllers
- Edición de datos de tabla

---

##Tab bar controllers


![](img/tabbar.png)

---

##Estructura en el *storyboard*


![](img/tabbar_struct.png)


---


##Configurar el *controller*

- Podemos crear nuestra propia clase de *controller*. En caso contrario se usa la del sistema: `UITabBarcontroller` 
- Para cada pantalla se puede elegir el *icono*, el *titulo* (solo si no es un icono estándar), el *badge*,...

---


#Demo


---


##2. Navigation Controller

---


![](img/navigation.png)


---

##Estructura en el *storyboard*

![](img/navigation_struct.png)

---


##Personalizar la barra de navegación

![](img/barra_nav.png)

- El botón para retroceder es automático, se puede personalizar
- El título es la propiedad `title` del controller
- Botón a la derecha: `rightBarButtonItem`


---

#Demo


---


