# Load, Preprocess and Visualize class
En este proyecto se creo una clase llamada pipeline que es capaz de cargar un data frame, preprocesarlo y luego vizualizarlo.

load_data(self, numerical_df, categorical_df): Se encarga de cargar dos data frames previamente preparados, uno de variables categoricas y otro de variables numericas

preprocess_data(self, cat_encoder, num_scaler): Te deja elegir con que escalador quieres preprocesar tu dataframe (StandarScaler,MinMaxScaler,RobustScaler,Normalizer) para las variables numericas y (OneHotEncoder,SimilarityEncoder) para las variables categoricas

visualize_data(self,data_graph_type): Grafica los datos dependiendo el tipo que quieras, numericos o categoricos.
