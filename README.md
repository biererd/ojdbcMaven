# ojdbcMaven

Installing Oracle JDBC Driver in Maven Local Repository:

    mvn install:install-file -Dfile=path/to/your/ojdbc11.jar -DgroupId=com.oracle -DartifactId=ojdbc8 -Dversion=21.11.0.0 -Dpackaging=jar
