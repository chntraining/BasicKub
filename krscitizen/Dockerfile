FROM eclipse-temurin:latest						
RUN pwd						
RUN ls -al						
RUN dir						
COPY  target/krscitizen.jar /krscitizen/krscitizen.jar					
WORKDIR /krscitizen
RUN pwd
RUN ls -al
CMD ["java", "-jar", "krscitizen.jar"]