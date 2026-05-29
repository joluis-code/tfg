<div align="center">

# Navegación coordinada en sistemas multiagente
### Material complementario — Trabajo de Fin de Grado

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![License](https://img.shields.io/badge/Uso-Académico-green?style=flat-square)

</div>

---

Este repositorio contiene el código Python y las animaciones generadas como material complementario a la memoria del TFG. Incluye las simulaciones de cuatro sistemas multiagente independientes que siguen distintas trayectorias en 2D y 3D, partiendo de posiciones iniciales aleatorias y convergiendo hacia una formación coordinada sobre la curva o curvas objetivo.

Cada simulación genera automáticamente cuatro salidas gráficas: una animación de la evolución del sistema, la gráfica del error de seguimiento de cada agente, el estado final con las trayectorias recorridas y el error de coordinación entre agentes vecinos a lo largo del tiempo.

---

## 📁 Archivos incluidos

### 🐍 Código

| Archivo | Agentes | Dimensión | Curva objetivo |
|---------|:-------:|:---------:|----------------|
| `Código_elipse.py` | 5 | 2D | Elipse |
| `Código_combinada.py` | 21 | 2D | Dos circunferencias (inscrita y circunscrita) y una elipse |
| `Código_Lissajous.py` | 4 | 2D | Curva de Lissajous abierta |
| `Código_infinito.py` | 15 | 3D | Curva cerrada con forma de infinito |

### 🎞️ Animaciones

| Archivo | Descripción |
|---------|-------------|
| `Elipsesimulación.gif` | Elipse 2D |
| `Combinadasimulación.gif` | Curvas combinadas 2D |
| `Lissajoussimulación.gif` | Lissajous — simulación corta |
| `Lissajoussimulaciónlarga.gif` | Lissajous — simulación larga (T = 400 s) |
| `Infinitosimulación.gif` | Infinito 3D |

---

## ⚙️ Instalación

```bash
pip install numpy scipy matplotlib
```

> Requiere **Python ≥ 3.9**. No se necesitan dependencias adicionales.

---

## ▶️ Uso

Cada script es independiente y se ejecuta directamente:

```bash
python Código_elipse.py
python Código_combinada.py
python Código_Lissajous.py
python Código_infinito.py
```

> **Nota:** En `Código_Lissajous.py`, el parámetro `T_END` puede ampliarse a `400.0` para observar cómo los agentes cubren densamente el rectángulo imagen de la curva, tal y como se describe en la memoria.

---

## Autor

| | |
|--|--|
| **Nombre** | *Jose Luis ALonso* |
| **Grado** | *Doble Grado en Física y Matemáticas* |
| **Universidad** | *Universidad Complutense de Madrid* |
| **Año** | 2026 |

---

## 📄 Licencia

Repositorio publicado con fines académicos como material complementario a la memoria del TFG.  
Queda prohibida su reproducción o uso comercial sin autorización expresa del autor.
