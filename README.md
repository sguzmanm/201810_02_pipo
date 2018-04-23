# 201810_02_pipo

## Integrantes

+ Juan Sebastián Díaz Serrano - 201532686
+ Carlos Mario Sarmiento Pinilla - 201512466
+ Sergio Eduardo Cárdenas Landazábal - 201613444
+ Sergio Guzmán Mayorga - 201614859
+ Julián Alberto Manrique Puerto - 201615449

## EXPERIMENTO I INTERMEDIO:
+ Para esta entrega se usó la máquina virtual con ip 172.24.42.33 del estudiante Sergio Guzmán.
+ El programa P se encuentra en la carpeta de entidad virtual y al haberse construido con maven se le de hacer clean and build antes de correrlo.
+ LINK DE LA ENTREGA: https://youtu.be/zIY5MJsavyg
### Para esta entrega se hizo la siguiente repartición de roles:
+ Entidad física (preparación): Juan Sebastián Díaz y Carlos Mario Sarmiento. Como tal no hubo commits de esta parte.
+ Entidad física (código de arduino): Sergio Cárdenas y Julián Manrique. Como todo se trabajó desde la máquina local de Sergio, él fue el responsable de hacer commits de esta parte.
+ Entidad virtual (Node-red y Programa P): Sergio Guzmán. Él se encargó de hacer commits relacionados con la creación de flujos y el programa P.
Se hace la especificación de esta repartición para justificar la no uniformidad de los commits realizados y de cierta manera informar que todo el grupo trabajó de forma equitativa.
## EXPERIMENTO I FINAL: 
+ El diagrama de despliegue de esta entrega se encuentra en la documentacin.
+ El software del Bridge, del programa P1 y P2 se encuentra en la carpeta de la entidad virtual bajo la subcarpeta de Mensajera.
+ El REST Mock se encuentra en la carpeta de entidad virtual. Tiene 3 operaciones particulares: GET (Retorna 200), POST (Escribe mensajes en un archivo) y PUT (Activa el modo de escritura sobre el archivo).
+ En la carpeta de persistencia se encuentran los servicios REST hechos en FLASK junto con sus colecciones. 
+ Link de la entrega: https://www.youtube.com/watch?v=yYp-H7bFBOI&feature=youtu.be
+ Para este aparte particular se va a tener una matriz de esfuerzos en la carpeta docs para simbolizar cual fue el aporte de cada integrante del grupo. A su vez el documento final está en dicha carpeta.

## EXPERIMENTO II INTERMEDIO: 
+ El link de la parte de la entidad física se encuentra acá: https://youtu.be/YIpmc0j0udE 
+ El alcance de la entidad física se encuentra en la carpeta entidadFisica, mientras que el aseguramiento de servicios se encuentra en entidadVirtual/servicios
+ Se tomó como decisión de diseño que la operacin de actualizar claves, agregar usuarios y loggearse fueran hechas con el API de Auth0. En la base de datos de mongo se persiste la información relevante del usuario (correo, username, id de auth0, rol, scope).
+ Se modificó el flujo de node red para simular el cambio de claves en el arduino. Este flujo es llamado por el programa RestClavesCerradura/cerradura/cerradura.servicios
