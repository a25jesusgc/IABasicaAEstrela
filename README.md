# Descrición

Emprega este arquivo para describir os cambios do teu proxecto.

Utiliza o formato en markdown coas marcas básicas que aparcen no seguinte exemplo:

# Título principal
## Subtítulo

Texto normal con **negriña** e *cursiva*.

- Lista 1
- Lista 2

[Ligazón](https://exemplo.com)


```csharp
using UnityEngine;

public class OlaMundo : MonoBehaviour
{
    void Start()
    {
        Debug.Log("Ola, mundo desde C#!");
    }
}

```


# Exercicio IA Basica A*
## Modificación da escena AStarPath

Para poder visualizar os custos dos nodos, modifiquei a escena primeiro facendo o labirintomáis pequeno, reducindo no inspector os seus valores public *width* e *depth*. Despois, alterei os valores do *Transform* da cámara para poder visualizar mellor o labirinto, acercando a cámara e rotándoa para ver os *Text* ao dereito.