FROM maven:3.5
WORKDIR /app
COPY src /src
COPY pom.xml /app/
RUN mvn clean package
ENV CART_ENDPOINT=cart:8080 \
    DB_HOST=mysql
CMD [ "java", "jar", "shipping.jar" ]