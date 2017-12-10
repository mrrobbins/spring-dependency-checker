# Spring Dependency Checker

Build the dependency tree for Spring Boot and Spring Cloud using Maven

```
mvn dependency:tree -DoutputFile=deps.txt
```

```
mvn dependency:tree -DoutputType=dot -DoutputFile=deps.dot

brew install graphviz

dot -Tpdf deps.dot -o deps.pdf -Gratio=0.25
```