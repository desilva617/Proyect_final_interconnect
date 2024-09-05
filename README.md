# Predicción de cancelación de clientes en Telecom Interconnect
## Conclusion
**Resultados**

El modelo Xgboost tiene una velocidad de aprendizaje muy buena (17.8 s) y un valor AUC-ROC excelente tanto en el conjunto de entrenamiento como de prueba, ya que no varía demasiado los valores en ambos conjunto podemos decir que no hay sobreajustamiento. Ademas el valor de presición, recall y f1 también fueron muy buenos, montrándonos que el modelo puede predecir correctamente la pérdida de clientes del 80 % de los clientes que aún no ha visto.

Evidentemente hubo un un desequilibrio de clases, y el ajuste de parametros para los modelos fue sufiente para solucionar el problema. Con class_weight en 'balanced' y scale_pos_weight en 3 debido a la relación entre la cantidad de clase negativa y la clase positiva.

**Alcance futuro**

Telecom puede confiar en implementar el modelo XGBoosto para predecir qué clientes se darán de baja. Por lo que no es una mala idea ofrecer  pequeñas promociones adicionales a la clientela. Telecom haría bien en centrarse en mantener a los nuevos clientes, ya que es probable que los antiguos sigan en la empresa.

**Recomendación**
 
Se debe tomar en cuenta especialmente a los nuevos clientes porque ellos son los que más probable abandonen su contrato. En los dos últimos años se han ido la mayor parte de clientes, por lo que se debe averiguar por medio de encuestas o análisis los últimos cambios realizados por la empresa que al parecer han tenido una repercusión negativa en el mantenimiento de los clientes.
