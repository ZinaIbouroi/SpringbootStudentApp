FROM openjdk:7
RUN pwd
COPY /var/lib/jenkins/workspace/springBootStudentAppsStepTwo/target/ /usr/src/myapp
WORKDIR /usr/src/myapp
CMD ["java", "SpringbootThymeleafWebAppApplication"]