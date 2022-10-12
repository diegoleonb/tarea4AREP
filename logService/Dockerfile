FROM openjdk:8

WORKDIR /usr/app/bin

COPY /target/classes /usr/app/bin/classes
COPY /target/dependency /usr/app/bin/dependency

CMD ["java","-cp","./classes:./dependency/*","edu.escuelaing.arep.MongoConnection"]