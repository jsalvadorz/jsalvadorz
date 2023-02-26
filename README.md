## Hola, soy J. Andre \o/👋
<img align="right" width="280" src="https://github.com/jsalvadorz/loading-images/raw/main/IMG_20210418_094653.jpg">

Matemático de profesión de la `Universidad Nacional de Ingeniería` de Perú. <br>
Especializándome en Ing. de Sistemas en la `Universidad Privada del Norte`. <br>
📌 Viviendo en `Lima`, pero en viajes conociendo el Perú.

### 👨‍🎓 Cumpliendo retos
```python
rangosDificultad = ["pollito", "maomenos", "otracosita", "hard", "pro", "masterdaster"]

class Reto:
    def __init__(self, nombre, dificultad, rangos = rangosDificultad):
        self.__nombre = nombre
        self.__dificultad = dificultad
        
        if self.__dificultad in rangos[3:]:
            print(f"¡Esooooo tilín! Nivel {self.__dificultad} ¡Sin miedo al éxito! 🔥")
        elif self.__dificultad in rangos[1:3]:
            print("Bueeeeno, a veces toca relajarse 😆")
        elif self.__dificultad == rangos[0]:
            print("¡Hay Dios!😱 mucho relajo, ¡No te pases!", 
                  "\n¡Alerta! No se aceptan retos fáciles 😡")
        else:
            raise Exception("Upps! Como que te equivocaste de reto, ¿No?")
        
    @property
    def nombre(self):
        return self.__nombre
    
    @nombre.setter
    def nombre(self, nValor):
        self.__nombre = nValor
        
    @property
    def dificultad (self):
        return self.__dificultad

    @dificultad.setter
    def dificultad (self, dValor, rangos = rangosDificultad):
        self.__dificultad = dValor
        if self.__dificultad in rangos[3:]:
            print(f"Actualizado a nivel {self.__dificultad}, volvió mi fe en ti 💪")
```

**Ejecutando:**
```python
miRetoActual = Reto("Aprender álgebra boolena", "pollito")
```
<blockquote>
¡Hay Dios!😱 mucho relajo, ¡No te pases!<br> 
¡Alerta! No se aceptan retos fáciles 😡
</blockquote>

```python
miRetoActual.nombre = "Aprender Big Data"
miRetoActual.dificultad = "hard"
print(f"Mi nuevo reto: {miRetoActual.nombre} nivel {miRetoActual.dificultad}")
```
<blockquote>
Actualizado a nivel hard, volvió mi fe en ti 💪<br>
Mi nuevo reto: Aprender Big Data nivel hard
</blockquote>

---
### 🖥 Tecnologías que manejo
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![JAVA](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQLServer](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white)
[![GitLab](https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white&link=https://gitlab.com/jsalvadorz)](https://gitlab.com/jsalvadorz)
