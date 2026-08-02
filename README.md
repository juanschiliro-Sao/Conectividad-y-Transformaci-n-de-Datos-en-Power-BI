# Conectividad-y-Transformación-n-de-Datos-en-Power-BI

 Documentación Redacta un breve documento (puede ser un archivo .docx o un README.md) donde expliques:

Qué transformaciones realizaste y en qué orden:
Subí la Base de Datos al Power BI, una vez subido el archivo, procedí a transformar los Datos con Power Query, duplique el archivo de ventas; y lo divide en  categorías: Producto, Vendedor y Clientes. En cada una deje el ID correspondiente y dos columnas con los datos específicos de cada uno.
Una vez creada esas tablas individuales a la tabla de ventas deje los ID y las columnas de datos de facturación y los ID de como Foreign Key de las otras tablas ya mencionadas.
Una vez creadas quite los duplicados de cada tabla.

Por qué elegiste cada tipo de dato.
Los elegí según el contenido de cada tabla, Texto para nombres y marcas, números para datos de números como ventas ID, decimales para costo, venta, etc.

Cómo resolviste los valores nulos y duplicados encontrados.
En la parte de transformación de datos se quitan los duplicados y los nulos.

Qué criterio usaste para separar los datos del cliente de los de la transacción.
Los separe teniendo en cuenta las columnas de datos del cliente, es decir, cree la tabla de "D_Clientes" con las columnas del ID Cliente, Cliente (Nombre) y País del cliente. El ID Cliente es en esta tabla la Primary Key y se usa en la tabla general de Ventas como una Foreign Key.

