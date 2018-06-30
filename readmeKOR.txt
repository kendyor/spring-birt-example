Errores_al_correr_app
#compilar con java 7
#el server aplicacion debe estar con el mismo jdk que se compilo
#los reportes tienen embebido la contraseña de la bd para cambiarlo se tiene
que hacer por el designer
# Lo abri con netbeans, el proyecto maven. Con el eclipse no lo detectaba
# Otro error, memoria permitida por el servidor de aplicaciones
-----------------------------------------------------
#la bd con la que trabaja es sakila de BD, que ya lo trae Mysql

La version del driver usado está en el pom.xml
mysql-connector-java-5.1.39.jar
---------------------------------------------------
#el pom.xml tenia un tag doble modelversion que daba error