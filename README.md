# PCIe Switch a x8 lanes basado en el chip PI7C9X3G808GP de Diodes

---

## Descripción

Este proyecto consiste en el diseño completo de una tarjeta PCI Express basada en el switch PCIe de la EVB de referencia del fabricante "Diodes Incorporated".
El proyecto incluye:

* Diseño esquemático completo
* Diseño PCB en Allegro
* 1 puerto upstream PCIe
* Múltiples puertos downstream PCIe
* Soporte para tarjetas PCIe x4 utilizando conectores físicos x16

---

## Herramientas utilizadas OrCADx Pro
Capture CIS
PCB Editor / Allegro
Constraint Manager

---

## El diseño actual:

No utiliza Hot Plug
CLKREQ# con pull-up
Uso de PDC_L en puertos downstream
SMBus/I2C no utilizados en downstream PCIe

---

## Contenido del repositorio
/Allegro
    Archivo zip con todo el proyecto para orcad, incluyendo librerias utilizadas.

/Schematics
    Proyecto Capture CIS (.DSN)
    Archivos PCB y librerías (.BRD)

    
/Manufacturing
    Gerbers
    Drill files
    Pick & Place
    BOM

/Docs
    Datasheets
    EVB reference
    PCIe layout guides

---

## Licencia
Este proyecto se comparte únicamente con fines educativos y de desarrollo. Verificar licencias y restricciones del fabricante del switch PCIe antes de uso comercial.
