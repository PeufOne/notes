Database


```mermaid
graph LR;  
    Pause -- touch --> Scan;  
    Scan-->Result;  
    Result-->auto{Auto ?};
    auto-- true -->Scan
    auto-- false -->Pause
    Scan-- timeout -->Pause
```


