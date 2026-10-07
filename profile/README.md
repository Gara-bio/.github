<div align="center">

<img src="https://raw.githubusercontent.com/Gara-bio/.github/main/profile/gara-logo.png" alt="Gara" width="120" />

# Gara

**De la secuencia a la estructura 3D, en un solo lugar.**

Predicción y visualización de proteínas para investigadores, con supercomputación detrás.

[🌐 gara.bio](https://gara.bio) · [✉️ info@gara.bio](mailto:info@gara.bio) · 📍 Santiago de Compostela

</div>

---

## 🧬 Qué es Gara

Gara es una plataforma web para **predecir, visualizar y analizar estructuras de proteínas**. Pegas una secuencia FASTA y Gara se encarga del resto: busca si la estructura ya existe, y si no, la predice en el supercomputador **CESGA Finis Terrae III** (GPU A100) y te la muestra en 3D en el navegador.

## ✨ Qué puedes hacer

- 🔬 **Predecir estructuras** con varios motores: **AlphaFold2**, **ESMFold**, **Boltz** y **OpenFold3**, incluidos complejos con proteínas, ADN/ARN, ligandos e iones.
- 🧊 **Visualizar en 3D** con Mol\*, con coloreado por confianza (pLDDT) y mapas de error alineado (PAE).
- 🧪 **Analizar**: contactos, interfaces entre cadenas, cavidades candidatas, potencial electrostático y alineamiento múltiple de secuencias.
- 🧫 **Explorar variantes** con datos de patogenicidad de AlphaMissense y mutación *in silico* de residuos.
- 🤝 **Trabajar en equipo** con espacios de trabajo y grupos de investigación compartidos.

## ⚙️ Cómo funciona

```
Secuencia FASTA → ¿ya existe? → sí: resultado inmediato
                              → no: predicción en CESGA (Slurm + A100) → visor 3D
```

Integramos fuentes públicas como **UniProt**, **AlphaFold DB** y **RCSB PDB** para que no repitas cálculos que ya existen.

## 📍 Hecho en Galicia

Nacemos en Santiago de Compostela con una idea sencilla: que usar la computación de alto rendimiento para estudiar proteínas no requiera ser experto en clústeres.

## 📬 Contacto

¿Quieres probar Gara o colaborar? Escríbenos a **[info@gara.bio](mailto:info@gara.bio)** o visita **[gara.bio](https://gara.bio)**.
