# ObjectsReconstruction
TA2 - Machine Learning - "3D Reconstruction of Incomplete Archaeological Objects Using a Generative Adversarial Network"

# Integrantes
Daniel Carlos Guillén Rojas - U201920113
Sebastián Alonso Gonzales Sotomayor - U201923816
Antonio Salinas Roca - U201924931

# Introducción
Las redes adversarias generadoras o GAN (por sus siglas en inglés),  son modelos generativos los cuales nos permiten generar datos idénticos y a veces indistinguibles de la data de entrenamiento. Un modelo GAN logra esto implementando dos redes, una red generadora, y una red clasificadora, las cuales son entrenadas en alternancia, con la red clasificadora evaluando el output generado por la red generadora y esta última ajustando su función de pérdida. El resultado de tener estas dos redes en competencia una con otra es un modelo capaz de replicar con alto detalle y precisión la data de entrenamiento, ejemplos de esto son modelos capaces de generar imágenes que aparentan ser fotos de personas reales cuando en realidad son totalmente generadas por el modelo. 
Haciendo uso de esta tecnología, en el paper 3D Reconstruction of Incomplete Archaeological Objects Using a Generative Adversarial Network, Renato Hermosa e Ivan Sipiran (2018) aplican las GAN para crear un modelo capaz de generar fragmentos faltantes de objetos 3D representados como voxels. Bajo este contexto en el presente proyecto busca profundizar el trabajo realizado por Hermoza y Sipirán y aplicarlo junto con tecnología de impresión 3D.
