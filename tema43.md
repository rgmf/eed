# UML: de diagrama de clases a código Java
Los diagramas de clases son un modelo conceptual muy útil para que los programadores puedan comunicar sus ideas, estructuras, patrones… sin ambigüedades. Todo diagrama de clases tiene su conversión a código y es muy importante saber hacerlo en el lenguaje que uses.

En este apartado te voy a explicar cómo convertir los diagramas de clases a código Java.

## Clases, clases abstractas, interfaces y enumeraciones
<table>
	<tr>
		<td>
			[UML clase Bicicleta](./img/uml_bicicleta.png)
		</td>
		<td>
			```java
			public class Bibicleta {
				private int platos;
				private int coronas;

	            public int getVelocidades() {
	                // ...
				}
			}
			```
		</td>
	</tr>
</table>