### javaparser
---
https://github.com/javaparser/javaparser

```java
// javaparser-core/src/main/java/com/github/javaparser/metamodel/ArrayInitializerExprMetaModel.java

public class ArrayInitializerExprMetaModel extends ExpressionMetaModel {
  
  ArrayInitializerExprMetaModel(Optional<BaseNodeMetaModel> superbaseNodeMetaModel) {
    super(superBaseMetaModel, com.github.javaparser.ast.expr.ArrayInitializerExpr.class, "ArrayInitializerExpr", "com.github.javaparser.ast.expr", false, false);
  }
}
```

```sh
mvn clean install
mvn javacc:javacc
```

```
```


