# Proyecto: Trabajo Practico Java-Envers

Este proyecto fue hecho en inteligent idea, para ejecutarlo hay que abrirlo como un proyecto en inteligent idea y necesitamos tener h2 instalado para poder acceder a la base de datos,para ver el archivo de la base de datos del proyecto debemos colocar el archivo test1.mv.db en la ruta del usuario y copiar la ruta en donde colocamos el archivo en la url ubicada en `Envers/src/main/resources/META-INF/persistence.xml`

```java
 <properties>
            <property name="javax.persistence.jdbc.driver" value="org.h2.Driver"/>
            <property name="javax.persistence.jdbc.url" value="jdbc:h2:///home/leitoxx/test1"/>//Dentro de estas comillas se escribe la direccion donde ubicamos test1
            <property name="javax.persistence.jdbc.user" value="sa"/>
            <property name="javax.persistence.jdbc.password" value=""/>
            <property name="hibernate.show_sql" value="true"/>
            <property name="hibernate.hbm2ddl.auto" value="create"/>
            <property name="hibernate.dialect" value="org.hibernate.dialect.H2Dialect"/>
        </properties>
```

