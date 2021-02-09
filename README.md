# Spotify-popularity
Repositorio para proyecto final de Aprendizaje Máquina sobre predicción de popularidad de una canción dependiendo de ciertas características musicales de cada una de éstas. 

**Integrantes**
* Óscar Alvarado Morán
* Dante Bermúdez Marbán
* Martín García Avendaño

# Contenido del proyecto
* `README.md`: este archivo
* `Popularidad_Spotify.pdf`: presentación usada el día de la exposición
* `FinalML_AlvaradoBermudezGarcia.pdf`: **reporte** final del proyecto 
* `enviroment.yml`: archivo para replicar entorno de conda
* `spotify/*.csv`: datos del proyecto
* `notebooks/Anteproyecto_spotify.ipynb`: notebook usado para el anteproyecto (primera exploración)
* `notebooks/spotify.ipynb`: **notebook** principal del proyecto

# Replicar proyecto
Para replicar el proyecto se recomienda utilizar **conda**.

1. Clonar este repositorio
> `git clone https://github.com/DanteBM/Spotify-popularity.git`
2. Dentro del repositorio, replicar el entorno `spotify-popularity` con ayuda del archivo `enviroment.yml`
> `conda env create -f enviroment.yml`
3. Activar entorno creado
> `conda activate spotify-popularity`

Y listo, ya se puede usar jupyter notebook con los paquetes necesarios para replicar el proyecto.
