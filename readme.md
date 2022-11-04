### Datathon de Machine Learning


###### Proyecto 02 Bootcamp de Henry

En este trabajo se vera la limpieza general de un dataset para luego ser entrenado y lograr predecir un target. El objetivo final sera predecir si se considera  caro o barato en base a sus caracteristica del inmueble . Los valores que da como resultado sera:  '1' si el valor del precio es 'caro' y '0' si el valor del precio es 'barato'


#### Modelos

En el archivo *modelo1.ipynb* se vera que se usa columnas especificas que se piensa que son de mayor relevancia para su predicción. Se usara el modelo de *LogisticRegression() *brindado por la libreria **sklearn**.

Como metrica a evaluar para los modelos se  utilizará la métrica de Exhaustividad (Recall) para las propiedades caras, a partir de la matriz de confusión (Confusion Matrix)

Adicionalmente, se incluye la Accuracy como métrica de control.