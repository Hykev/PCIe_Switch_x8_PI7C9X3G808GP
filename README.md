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
* Capture CIS
* PCB Editor / Allegro
* Constraint Manager

---

## El diseño actual:

* No utiliza Hot Plug
* CLKREQ# con pull-up
* Uso de PDC_L en puertos downstream
* SMBus/I2C no utilizados en downstream PCIe

---

## Contenido del repositorio

/DRL
    Archivos de perforado (NC Drill)

/GERBER
    Archivos Gerber para fabricación

/BOM_PCIe_PCIe.BOM
    BOM exportado en formato texto

/BOM_PCIe_PCIe.BOM.xlsx
    BOM exportado en formato Excel

/PCIE-PCIE.DSN
    Proyecto esquemático de OrCAD Capture CIS

/pcie-pcie_3.brd
    Archivo PCB de Cadence Allegro

/Schematic.pdf
    Exportación PDF del esquemático completo

---

## Licencia
Este proyecto se comparte únicamente con fines educativos y de desarrollo. Verificar licencias y restricciones del fabricante del switch PCIe antes de uso comercial.
