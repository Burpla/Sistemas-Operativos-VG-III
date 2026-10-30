# Simulador de planificación de CPU y gestión de memoria

Trabajo realizado en 2025 para la materia **Sistemas Operativos** de la facultad.

Desarrollado en **Python con Tkinter**, permite visualizar paso a paso cómo se ejecutan los procesos y cómo se distribuye la memoria disponible.

## Funcionalidades

- Carga de procesos desde archivos CSV.
- Planificación de CPU mediante **SRTF con desalojo**, priorizando el proceso con menor tiempo restante.
- Gestión de memoria mediante **particiones fijas y Best-Fit**.
- Intercambio de procesos (**swapping**).
- Visualización de estados, colas de procesos, ocupación de memoria y fragmentación interna.
- Resumen final con tiempos de espera, respuesta y retorno por proceso, promedios generales y rendimiento.

## Ejecución

### Windows

Ejecutar `Simulador_VG3.exe`.

### Desde el código fuente

Se requiere Python 3 con Tkinter y la biblioteca Pillow.

Instalar Pillow:

```bash
python -m pip install Pillow
```

Desde la carpeta raíz del proyecto, ejecutar:

```bash
python src/main.py
```

## Cómo utilizarlo

1. Presionar **Cargar CSV** y seleccionar un lote de la carpeta `csv`.
2. Presionar **Tick** para avanzar la simulación una unidad de tiempo.
3. Observar los cambios en los procesos y la memoria.
4. Al finalizar, consultar el resumen de resultados.

## Documentación

- [Manual de uso y explicación de las políticas implementadas](HOWTO.md)
- [Demostración de funcionamiento con lotes](Demostracion%20de%20Funcionamiento%20con%20Lotes.pdf)
