#### Setting

    {
        sequenceDiagram : true
    }

#### Syntax

    ```seq
    .........
    ```

    # or

    ```sequence
    .........
    ```

#### Example

```seq
A->B: Message
B->C: Message
C->A: Message
```

```sequence
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```
# Proyecto1
Bryan Miguel Arias Canchihuaman
Mi primer Proyecto ---> Proyecto1

```mermaid
sequenceDiagram
    Bryan ->> Backend: Estructura MVC
    Backend--x Bryan: Estructura Correcta
    Note right of Backend: Reto Completado Exitosamente.

