
# Grafo de los preliminares del corpus CECLE/CLICLE

Los datos para elaborar la red proceden de la Biblioteca de Ediciones de Clásicos Latinos en el Renacimiento, del proyecto BECLaR. http://www.incunabula.uned.es. Han sido extraídos de forma automática de la web del proyecto, por lo que pueden no reflejar el contenido real de la base de datos.

Representa la coocurrencia en las ediciones de las personas implicadas en los paratextos, junto con los autores latinos (29) de cada obra. Se ha hecho una selección de los campos: autor (prólogo, epístola, etc.), autoridad responsable, dedicatario, otorgador, comisionado.

El tamaño de los nodos corresponde con el grado (_degree_) en la red; el color, con la clasificación del algoritmo _bridging centrality_, que destaca los nodos que sirven de puente entre clústers. Las aristas están ponderadas: a mayor grosor, mayor es la coocurrencia entre nodos.

Los datos se han estructurado y formalizado usando R; la visualización usa el plugin de Gephi, Sigma Exporter, desarrollado por el Oxford Internet Institute y Jisc.

[Grafo de paratextos](https://editio.github.io/grafos/paratextos/)