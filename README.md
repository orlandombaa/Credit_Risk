# Credit_Risk

## Descripción del problema
**RISK MODEL:** El problema se centra en la necesidad de la empresa *X* de poder hacer una clasificación correcta de clientes (buen cliente y mal cliente) que le permite mínimizar los riesgos en la colocación de créditos.

**PRIMERA PARTE** se centra en la creación de un modelo que permita minimizar riesgos en la colocación de créditos. Dado la naturaleza de los datos de entrenamiento (los datos ya tienen una etiqueta binaria de clientes pasados donde se ha documentado si fueron "buenos o malos clientes") esta etapa se abordará con un modelo de clasificación binaria. Existe una amplia variedad de modelos que podríamos usar para abordar este tipo de problemas (Naive bayes, SVM, Random Forest, Redes neuronales entre otros). Sin embargo, dado que los datos que usaremos son tabulares y el problema es concretamente una clasificación binaria optaremos por explorar los siguientes modelos: 
 
- XGboost 
- Regresión logística 

**SEGUNDA PARTE** se centra simplemente en una recomendación de como poder ir más allá de este primer modelo y genera una solución que permita asignar tasas de interés a cada cliente.


**IMPORTANTE:** Dado que ya se esta planteando que exista distintas tasas de interés optaremos
