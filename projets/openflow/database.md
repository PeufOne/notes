Database

https://mermaid-js.github.io/mermaid

```mermaid
graph LR;  
    Pause -- touch --> Scan;  
    Scan-->Result;  
    Result-->auto{Auto ?};
    auto-- true -->Scan
    auto-- false -->Pause
    Scan-- timeout -->Pause
```


