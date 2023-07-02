```mermaid
graph LR
    Controller --> Service --> Dao
```

```
controller：控制层，接收前端发送的请求，对请求进行处理，并响应数据。
service：业务逻辑层，处理具体的业务逻辑。
dao：数据访问层(Data Access Object)（持久层），负责数据访问操作，包括数据的增、删、改、查。
```
