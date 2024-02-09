# FPDFExtension

## Tabla de contenidos
+ [About](#about)
+ [Empezando](#getting_started)
+ [Uso](#usage)
+ [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>
FPDFExtesion es una versión modificada de FPDF con algunas características nuevas.

## Empezando <a name = "getting_started"></a>
### Prerequisitos

Antes de usar debe cumplir algunos prerequisitos

```
Tener instalado FPDF
```

### Installing

Pasos para instalar FPDFExtension en el proyecto.


Clonar el repositorio
```
git clone https://github.com/MendozaNicolas/FPDFExtension.git
```



```
Mover el archivo fpdfe.php a la carpeta de trabajo
```

Y ya esta listo para usar
```
<?php
require('fpdfe.php');

$pdf = new FPDFE();
$pdf->AddPage();
$pdf->SetFont('Arial','B',16);
$pdf->Cell(40,10,'¡Hola, Mundo!');
$pdf->Output();
?>
```
## Uso <a name = "usage"></a>

Add notes about how to use the system.


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->
