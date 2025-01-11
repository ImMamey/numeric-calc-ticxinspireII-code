<p align="center">
    <h1 align="center">Algoritmos para calculadoras NSPIRE CX II CAS de Cálculo Numerico</h1>
</p>

<p align="center">
    <img src="https://img.shields.io/github/stars/ImMamey/numeric-calc-ticxinspireII-code?color=white" alt="Stars"/>
    <img src="https://img.shields.io/github/commit-activity/t/ImMamey/numeric-calc-ticxinspireII-code?color=white" alt="Commits"/>
    <img src="https://img.shields.io/github/v/release/ImMamey/numeric-calc-ticxinspireII-code?color=white" alt="Version"/>
    <img src="https://img.shields.io/github/issues/ImMamey/numeric-calc-ticxinspireII-code?color=white" alt="Issues"/>
    <img src="https://img.shields.io/badge/Ko--fi-F16061?style=flat-square&logo=ko-fi&logoColor=white" alt="Ko-Fi"/>
</p>

>[!NOTE]
> [Click here for the English version](/resources/READMEN.md)

## Desarrollador
<p align="center">
  <a href="https://github.com/ImMamey" rel="nofollow">
    <img src="https://avatars.githubusercontent.com/u/32584037?v=4" width="150px;" alt="Mamey" style="border-radius:50%;">
  </a>
</p>
<p align="center">
  <a href="https://github.com/ImMamey" rel="nofollow"><b>Mamey</b></a><br>
  <a href="https://github.com/ImMamey/numeric-calc-ticxinspireII-code/commits?author=ImMamey" title="Commits">📖 Commits</a>
</p>

---
## Tabla de contenidos
- [Sobre este repositorio](#sobre-este-repositorio)
- [Códigos disponibles](#códigos-disponibles)
- [Requisitos](#requisitos)
  - [Software y extras](#software-y-extras)
- [Instalación en la calculadora](#installación-en-la-calculadora)
- [Algoritmos disponibles por archivo](#contenido-de-cada-archivo-tns-respecto-al-tema)
- [Contribuciones](#contribuciones)
- [Apoyo](#aopoyo)
- [Licencia](#licencia)

## Sobre este repositorio


Este repositorio es una collecion de codigos automatizados escritos en TI-Basic para calculadoras TI NSPIRE CX II CAS.

Los códigos aqui presentes permiten calcular algunos de los algoritmos mas importantes de cálculo numérico / métodos numericos, paso a paso, y con iteraciones en caso de ser aplicable.

<table align="center" border="0">
<tr>
    <td align="center"><img src="resources\images\example.png" width="300px;" alt="" style="max-width:100%;"><br><sub><b>Sistema de ecuaciones lineales</b></sub></td>
    <td align="center"><img src="resources\images\example2.png" width="330px;" alt="" style="max-width:100%;"><br><sub><b>Minimos potenciales</b></sub></td>
    <td align="center"><img src="resources\images\example3.png" width="350px;" alt="" style="max-width:100%;"><br><sub><b>Raices por metodo secante</b></sub></td>
    <td align="center"><img src="resources\images\example4.png" width="350px;" alt="" style="max-width:100%;"><br><sub><b>Ecuaciones lineales Gauss-Seidel</b></sub></td>
</tr>
</table>


## Códigos disponibles:
* Interpolación[^1].
* Mínimos cuadrados.
* Mínimos exponenciales.
* Mínimos potenciales.
* Regresión lineal de grado 2.
* Regresión lineal de grado 3.
* Metodo iterativo de Jacobi para matrices.
* Convergencia para Jacobi[^2].
* Metodo iterativo de Gauss-Seidel para matrices.
* Raices cuadradas por el método iterativo de la secante.
* Raices cuadradas por el método iterativo de bisección.
* Raices cuadradas por el método iterativo de Newton.
* Sistemas de ecuaciones no lineales de Newton.

[^1]: De segundo y tercer grado.
[^2]: Radio espectrall.

---

## Requisitos
* [Texas Instruments NSpire CX II CAS](https://education.ti.com/en/products/calculators/graphing-calculators/ti-nspire-cx-ii-cx-ii-cas)
<p align="center">
    <img src="resources\images\calc.png" title="calculator" width="300">
</p>

### Software y extras:
* **Calculadora**: OS versión 5.4.0.259 (mínimo)
* **Software de Estudiante TI-Nspire CX CAS**: [Descargar aquí](https://education.ti.com/en/software/details/en/36BE84F974E940C78502AA47492887AB/ti-nspirecxcas_pc_full) (versión 6.0.3.374). Este programa de escritorio permite probar los códigos en PC y transferir archivos.
* **Transferencia de Archivos**: [Página web para transferencia de archivos](https://nspireconnect.ti.com/nsc/file-transfer) (opcional, en caso de no poseer licencia para usar el software de estudiante TI-Nspire CX CAS).

## Installación en la calculadora

1. **Descargar el repositorio**.
2. **Ubicar los archivos**: En la carpeta `tns` están todos los archivos `.tns`, estos son los códigos que se deben transferir a la calculadora (o al programa de estudiantes).
3. **Transferir archivos**: Abrir la [página web para transferencia de archivos tns](https://nspireconnect.ti.com/nsc/file-transfer) y transferir todos los archivos `.tns` a la calculadora.
   
> [!TIP]
> Guardar preferiblemente los códigos dentro de la carpeta `MyLib` dentro de la calculadora.

4. **Actualizar bibliotecas**: Dentro de la calculadora, seleccionar las siguientes opciones en orden: `Botón Home` → `Botón menu` → `Botón B` (refresh all libraries).

---

## Algoritmos disponibles por archivo:



<table style="width:100%">
    <tr>
       <th> Tema </th>
       <th> TNS con códigos </th> 
       <th> Funciones</th>
    </tr>
    <tr>
        <th rowspan="3">Raices de Ecuaciones no lineales</th>
        <th> raice_biseccion.tns </th>
        <th> secante()<br> secante_pap()</th>
    </tr>
    <tr>
        <th>raices_newton.tns</th>
        <th>newton() <br> newton_pap() </th>
    </tr>
    <tr>
        <th>raices_secante.tns</th>
        <th>secante() <br> secante_pap()</th>
    </tr>
    <tr>
        <th rowspan="2"> Sistemas de ecuaciones lineales: Jacobi y Gauss-Seidel</th>
        <th> jacobi.tns  </th>
        <th> jacobi(a,b,x0,tol) <br> jacobi_conv(a,b,x0,tol)</th>
    </tr>
    <tr>
        <th> seidel.tns </th>
        <th> seidel(a,b,x0,tol) <br> seidel_conv(a,b,x0,tol)</th>
    </tr>
    <tr>
        <th> Sistemas de ecuaciones no lineales: Newton</th>
        <th>sist_ecnl_newton.tns</th>
        <th>newton_sistecnl2i()</th>
    </tr>
    <tr>
        <th>Interpolacion y ajuste de curvas (minimos cuadrados)</th>
        <th>interpol_minimos.tns</th>
        <th>
        interpol(x,y,n) <br> minimos2(x,y,n) <br> minimos_expone(x,y) <br> minimos_poten(x,y) 
        </th>
    </tr>
    <tr>
        <th>Integración Numerica</th>
        <th> integracion.tns</th>
        <th> intg_trap() <br> intg_longarco() <br> intg_trap2(a,b,tol,fx2)</th>
    </tr>
</table>

---
## Contribuciones

Este código no está en mantenimiento activo.

Sin embargo, si encuentras algún error, por favor genera un issue en el repositorio para que pueda ser revisado.

## Apoyo

El contenido de este repositorio es **gratis y open-source**. 

Aunque ya no se realizan actualizaciones activas, sigue siendo un recurso educativo útil para tanto estudiantes y profesores. Puedes apoyar dando una ⭐ al repositorio o compartiéndolo con otros.

## Licencia
#### Resumen:
 1. El código en este repositorio es estrictamente educacional.
 2. No me hago responsable del uso (ni posibles daños por el uso) de los códigos aqui presentes.
 3. Eres libre de distribuir los codigos aqui presentes.

 Para mas informacion leer el archivo [`LICENSE`](resources/legal/LICENSE)