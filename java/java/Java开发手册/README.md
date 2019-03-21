

```java
public class ResultDto<T extends Serializable> implements Serializable {
    private int code;
    private String msg;
    private T data;
}
```

