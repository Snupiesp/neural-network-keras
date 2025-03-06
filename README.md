# Red Neuronal con Keras y MNIST

Este repositorio contiene una implementación de una red neuronal para la clasificación de dígitos escritos a mano utilizando la base de datos MNIST. La red neuronal está implementada en Keras y TensorFlow.

## Estructura del Proyecto

```
📂 neural_network_keras
│── 📂 src
│   ├── neural_network_keras.py  # Código de la red neuronal
│── main.py  # Archivo principal que ejecuta la red neuronal
│── requirements.txt  # Dependencias del proyecto
│── .gitignore  # Archivos y carpetas ignoradas por Git
│── README.md  # Documentación del proyecto
```

## Instalación

1. Clona este repositorio:
   ```sh
   git clone https://github.com/usuario/proyecto_neural_network.git
   ```

2. Entra al directorio del proyecto:
   ```sh
   cd proyecto_neural_network
   ```

3. Crea y activa un entorno virtual:
   ```sh
   python -m venv venv
   ```
   - En Windows:
     ```sh
     venv\Scripts\activate
     ```
   - En macOS/Linux:
     ```sh
     source venv/bin/activate
     ```

4. Instala las dependencias:
   ```sh
   pip install -r requirements.txt
   ```

## Uso

Para ejecutar la red neuronal, ejecuta el siguiente comando:
```sh
python main.py
```

## Dependencias

Las principales dependencias del proyecto se encuentran en el archivo `requirements.txt`. Algunas de ellas incluyen:
- `numpy`
- `tensorflow`
- `keras`
- `matplotlib`

## .gitignore

El archivo `.gitignore` se configura para evitar subir archivos innecesarios como:

venv/





