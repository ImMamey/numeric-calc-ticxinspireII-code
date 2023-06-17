<p align="center">
    <h1 align="center"/> Algoritmos para NSPIRE CX II CAS de Cálculo Numerico </h1>
    <h4 align="center"> <a href="resources">Click here for the English version </a></h4>
</p>



## Desarrollador
<table align="center">
<tbody>
<tr>
<td align="center"><a href="https://github.com/ImMamey" rel="nofollow"><img src="https://avatars.githubusercontent.com/u/32584037?v=4" width="150px;" alt="" style="max-width:100%;"><br><sub><b>Mamey</b></sub></a><br><a href="https://github.com/ImMamey/Practica-5-DDNS/commits?author=ImMamey" title="Commits"><g-emoji class="g-emoji" alias="book" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4d6.png">📖</g-emoji></a></td>
</tr>
</tbody>
</table>

---
## Sobre este repositorio


Este repositorio es una collecion de codigos automatizados escritos en TI-Basic para calculadoras TI NSPIRE CX II CAS.

Los códigos aqui presente permiten calcular algunos de los algoritmos mas importantes de cálculo numérico / métodos numericos, paso a paso, y con iteracion.

> Por ejemplo:
<p align="center">
    <img src="resources\images\example.png" title="calculator" width="300">
</p>

---

## Códigos disponibles:
* Interpolación (de segundo y tercer grado)
* Mínimos cuadrados.
* Mínimos exponenciales.
* Mínimos potenciales.
* Regresión lineal de grado 2
* Regresión lineal de grado 3
* Metodo iterativo de Jacobi para matrices
* Convergencia (radio espectral) para Jacobi
* Metodo iterativo de Gauss-Seidel para matrices
* Raices cuadradas por el método iterativo de la secante
* Raices cuadradas por el método iterativo de bisección
* Raices cuadradas por el método iterativo de Newton
* Sistemas de ecuaciones no lineales de Newton

---

## Requisitos
* [Texas Instruments NSpire CX II CAS](https://education.ti.com/en/products/calculators/graphing-calculators/ti-nspire-cx-ii-cx-ii-cas)
<p align="center">
    <img src="resources\images\calc.jpg" title="calculator" width="300">
</p>

### Software y extras requeridos:

* Calculadora con OS versión: 5.4.0.259 (mínimo)
* [TI-Nspire CX CAS Student Software](https://education.ti.com/en/software/details/en/36BE84F974E940C78502AA47492887AB/ti-nspirecxcas_pc_full) version: 6.0.3.374: programa de escritorio para probar los códigos en PC y transferencia de archivos.
* [Pagina web para transferencia de archivos](https://nspireconnect.ti.com/nsc/file-transfer): en el caso de no poseer licencia para usar TI-Nspire CX CAS Student Software (OPCIONAL) 

---
## Installación en la calculadora

1. Descargar el repositorio.
2. En la carpeta `src` estan todos los programas, cada programa termina con `.tns`. Descargar todos los `.tns`
3. Abrir la [pagina web para transferencia de archivos tns](https://nspireconnect.ti.com/nsc/file-transfer) y transferir todos los `.tns` a la calculadora conectada a la PC.
> Guardar preferiblemente los códigos dentro de la carpeta `MyLib` dentro de la calculadora.
4. Dentro de la calculadora seleccionar las siguientes opciones en orden: `Botón Home` → `Botón menu` → `Botón B`/`refresh all libraries`


---

## Contenido de cada archivo tns respecto al tema:



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

## Legal

 El código en este repositorio es estrictamente educacional. No me hago responsable del uso de los códigos aqui presentes.