# Book-Store
Suppressed: java.lang.ClassNotFoundException: org.hibernate.dialect.MySQL57Dialect
		at java.base/jdk.internal.loader.BuiltinClassLoader.loadClass(BuiltinClassLoader.java:641) ~[na:na]
		at java.base/jdk.internal.loader.ClassLoaders$AppClassLoader.loadClass(ClassLoaders.java:188) ~[na:na]
		at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:526) ~[na:na]
		at org.hibernate.boot.registry.classloading.internal.AggregatedClassLoader.findClass(AggregatedClassLoader.java:206) ~[hibernate-core-6.6.5.Final.jar:6.6.5.Final]
		... 54 common frames omitted

[2m2025-01-31T08:52:54.654+05:30[0;39m [31mERROR[0;39m [35m4744[0;39m [2m--- [Bookstore] [  restartedMain] [0;39m[36mj.LocalContainerEntityManagerFactoryBean[0;39m [2m:[0;39m Failed to initialize JPA EntityManagerFactory: Unable to create requested service [org.hibernate.engine.jdbc.env.spi.JdbcEnvironment] due to: Unable to resolve name [org.hibernate.dialect.MySQL57Dialect] as strategy [org.hibernate.dialect.Dialect]
[2m2025-01-31T08:52:54.655+05:30[0;39m [33m WARN[0;39m [35m4744[0;39m [2m--- [Bookstore] [  restartedMain] [0;39m[36mConfigServletWebServerApplicationContext[0;39m [2m:[0;39m Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: Unable to create requested service [org.hibernate.engine.jdbc.env.spi.JdbcEnvironment] due to: Unable to resolve name [org.hibernate.dialect.MySQL57Dialect] as strategy [org.hibernate.dialect.Dialect]
[2m2025-01-31T08:52:54.657+05:30[0;39m [32m INFO[0;39m [35m4744[0;39m [2m--- [Bookstore] [  restartedMain] [0;39m[36mcom.zaxxer.hikari.HikariDataSource      [0;39m [2m:[0;39m book - Shutdown initiated...
[2m2025-01-31T08:52:54.663+05:30[0;39m [32m INFO[0;39m [35m4744[0;39m [2m--- [Bookstore] [  restartedMain] [0;39m[36mcom.zaxxer.hikari.HikariDataSource      [0;39m [2m:[0;39m book - Shutdown completed.
[2m2025-01-31T08:52:54.669+05:30[0;39m [32m INFO[0;39m [35m4744[0;39m [2m--- [Bookstore] [  restartedMain] [0;39m[36mo.apache.catalina.core.StandardService  [0;39m [2m:[0;39m Stopping service [Tomcat]
[2m2025-01-31T08:52:54.686+05:30[0;39m [32m INFO[0;39m [35m4744[0;39m [2m--- [Bookstore] [  restartedMain] [0;39m[36m.s.b.a.l.ConditionEvaluationReportLogger[0;39m [2m:[0;39m 

Error starting ApplicationContext. To display the condition evaluation report re-run your application with 'debug' enabled.
[2m2025-01-31T08:52:54.722+05:30[0;39m [31mERROR[0;39m [35m4744[0;39m [2m--- [Bookstore] [  restartedMain] [0;39m[36mo.s.boot.SpringApplication              [0;39m [2m:[0;39m Application run failed
