## Proyecto Claims Severity Prediction

Repositorio dedicado al proyecto de severidad de reclamaciones para la materia de Introducción a la Inteligencia Artificial

## Miembros del grupo
* YOHEL OSVALDO PEREZ GARCIA, CC.1035921408, Ingeniería de Sistemas
* TATIANA ELIZABETH SÁNCHEZ SANIN, CC. 1125348235, Ingeniería de Sistemas
* DANIELA ANDREA PAVAS BEDOYA, CC. 1192741700, Ingeniería de Sistemas

## Datos
Los datos del proyecto vienen de la competición [Allstate State Claims Severity](https://www.kaggle.com/competitions/allstate-claims-severity/data). Los pasos para hacerlos disponibles en google collab son los siguientes:  

Ejecutar las siguientes lineas de comando
```
  !pip install kaggle
  
  from google.colab import files 
  files.upload()
```
Entregar el token .json que provee la página de Kaggle y continuar ejecutando las siguientes lineas para descargar los datasets

```
  ! mkdir ~/.kaggle
  ! cp kaggle.json ~/.kaggle/
  ! chmod 600 ~/.kaggle/kaggle.json
  !kaggle competitions download -c allstate-claims-severity
  !unzip allstate-claims-severity.zip
```


## Videos

[Video entrega 1]()  
[Video entrega 2]()
