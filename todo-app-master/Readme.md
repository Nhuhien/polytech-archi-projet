## Exigences

1. Java - 1.8.x

2. Maven - 3.x.x

3. MongoDB - 3.x.x

## Étapes à suivre pour l'installation


**1. Construire et exécuter l'application backend en utilisant maven **

```bash
cd spring-boot-backend
mvn package
java -jar target/todoapp-1.0.0.jar
```

Alternativement, vous pouvez exécuter l'application sans l'empaqueter en utilisant -

```bash
mvn spring-boot:run
```

Le serveur principal démarrera à <http: // localhost: 8080>.

** 2. Exécutez l'application frontend en utilisant npm **
```bash
cd angular-frontend
npm install
```

```bash
npm start
```

Le serveur frontal s'exécutera sur <http: // localhost: 4200>
