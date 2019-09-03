### jgiven
---
https://github.com/TNG/JGiven

http://jgiven.org/

```java
// jgiven-core/src/test/java/com/tngtech/jgiven/GivenTestComposedStep.java

public class GivenTestComposedStep extends Stage<GivenTestComposeStep> {

  @ProvideScenarioState
  int value3;
  
  public void some_integer_value_in_the_substep( int someIntValue ) {
    this.value3 = someIntValue;
  }
  
}
```

```
```

```
```


