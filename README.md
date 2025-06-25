# Instrucciones para crear y activar un entorno virtual en macOS/Linux

1. Abre una terminal y navega a la carpeta raíz del proyecto:

   cd "/Users/Jime/Desktop/Diagnostico por IA"

2. Crea un entorno virtual llamado "venv":

   python3 -m venv venv

3. Activa el entorno virtual:

   source venv/bin/activate

4. Instala las dependencias:

   pip install -r chest_xray/requirements.txt

5. (Opcional) Para iniciar Jupyter Notebook:

   jupyter notebook

# Si usas Windows, la activación es:
#   .\venv\Scripts\activate
