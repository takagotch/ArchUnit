### archunit
---
https://github.com/TNG/ArchUnit


```java
public class MyArchitectureTest {
  @Test
  public void some_architecture_rule() {
    JavaClasses importedClasses = new ClassFileImporter().importPackages("com.myapp");
    
    ArchRule rule = classes()...
    
    rule.check(importedClasses);
  }
}
```

```
```

```
```


