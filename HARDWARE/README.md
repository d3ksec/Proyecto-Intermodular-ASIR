# Fundamentos de Hardware

## Descripción
Análisis y diseño de la infraestructura física necesaria para dar soporte
a la productora audiovisual Satori Visuals, compuesta por 5 personas
organizadas en 4 departamentos.

---

## Estructura de la empresa
| Departamento | Personas |
|---|---|
| Producción | 1 |
| Post-producción | 2 |
| Marketing | 1 |
| IT | 1 |

---

## Equipos por departamento

### Post-producción (×2)
Workstation de alto rendimiento para edición de vídeo 4K, etalonaje
y exportación. GPU con soporte CUDA para acelerar el renderizado.
- CPU: AMD Ryzen 7 7700X
- RAM: 64GB DDR5
- GPU: NVIDIA RTX 4070
- Almacenamiento: SSD NVMe 2TB + HDD 8TB
- Refrigeración: be quiet! Pure Loop 2 240mm
- Monitores: LG 27UK850-W 4K IPS + LG 27MK600M FHD IPS

### Marketing (×1)
Equipo de gama media para diseño gráfico, edición ligera de imágenes
y gestión de redes sociales.
- CPU: AMD Ryzen 5 7600X
- RAM: 32GB DDR5
- GPU: NVIDIA RTX 3060 12GB
- Almacenamiento: SSD NVMe 1TB
- Refrigeración: be quiet! Dark Rock 4
- Monitores: LG 27UK850-W 4K IPS + LG 27MK600M FHD IPS

### Producción (×1)
Equipo portátil para trabajar en rodajes y gestionar archivos de cámara.
- MacBook Air M2

### IT (×1)
Portátil profesional para administración de la infraestructura en remoto
y desde la oficina. Corre Ubuntu 22.04 LTS.
- ASUS ProArt Studiobook 16
- CPU: AMD Ryzen 7 7745HX
- RAM: 32GB DDR5
- Monitor: LG 27MK600M FHD IPS

---

## Almacenamiento centralizado — NAS
Synology DS923+ con 4 discos Seagate IronWolf 16TB en RAID 5.
- **48TB de almacenamiento útil**
- **Tolerancia a fallo de 1 disco**
- Acceso desde todos los departamentos vía SMB

Estructura de carpetas del NAS:
