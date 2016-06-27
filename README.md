# stubby4j-playground

A very easy to use HTTP API mock server. Details in project [stubby4j](https://github.com/azagniotov/stubby4j)


## Usage
1. Prepare mock responses into ```config.yaml```

2. Run the server ```java -jar stubby4j-3.3.0.jar -w --data config.yaml```

3. Query the mock server ```curl -v http://localhost:8882/hello-world``` and have fun!
