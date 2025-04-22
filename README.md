# Challange-Data-Science
Challange Data Science 
# 📊 Análisis de Rentabilidad - Alura Store Latam

**Objetivo**: Determinar qué tienda vender, basado en ingresos, satisfacción de clientes y costos operativos.

## 📌 Resultados Clave

### 🔢 Datos Generales
| Métrica               | Tienda 1       | Tienda 2       | Tienda 3       | Tienda 4       |
|-----------------------|---------------|---------------|---------------|---------------|
| Ingresos Totales      | $1,150,880,400 | $1,116,343,500 | $1,098,019,600 | $1,038,375,700 |
| Calificación Promedio | ★★★★☆ (4.10)  | ★★★☆☆ (3.95)  | ★★★★☆ (4.25)  | ★★★☆☆ (3.80)  |
| Costo Envío Promedio  | $18,000       | $15,000       | $25,000       | $12,000       |

### 📈 Gráficos Destacados
1. **Ingresos por Tienda**:  
   ![Ingresos](https://i.imgur.com/XYZ1234.png)
2. **Distribución Geográfica**:  
   ![Mapa](https://i.imgur.com/XYZ1234.png)

## 🧠 Análisis y Recomendación

### 🏆 Fortalezas por Tienda
- **Tienda 1**: Mayor volumen de ventas (+10% vs Tienda 4).
- **Tienda 3**: Mejor satisfacción cliente (4.25/5).
- **Tienda 2**: Costos logísticos equilibrados.

### 🚨 Problemas Identificados
- **Tienda 4**: 
  - 12% menos ingresos que el promedio.
  - Bajo desempeño en electrónicos (categoría clave).
  - Alta concentración en zonas rurales.

### ✅ Recomendación Final
**Vender Tienda 4** debido a:
1. Menor rentabilidad (-$112M vs Tienda 1).
2. Insatisfacción cliente (3.8/5).
3. Bajo potencial de crecimiento geográfico.

## 🛠 Cómo Reproducir el Análisis
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/alura-store-latam.git

   jupyter notebook AluraStoreLatam_Analysis.ipynb
### Requisitos
pandas==1.4.0
matplotlib==3.5.0
seaborn==0.11.0

### Estructura del proyecto
alura-store-latam/
├── data/                    # Datos CSV originales
├── images/                  # Gráficos exportados
├── AluraStoreLatam_Analysis.ipynb  # Notebook con el análisis
└── README.md                # Este archivo

git add README.md
git commit -m "Agrega README con análisis completo"
git push origin main
   
