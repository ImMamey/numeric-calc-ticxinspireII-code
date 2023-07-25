<p align="center">
    <h1 align="center"/> Algorithms for NSPIRE CX II CAS Calculators for Numerical Calculation </h1>
    <h4 align="center"> <a href="/README.md">Click here for the Spanish version </a></h4>
</p>

> # [IMPORTANT]: The codes in this repo are written in spanish.

## Developer
<table align="center">
<tbody>
<tr>
<td align="center"><a href="https://github.com/ImMamey" rel="nofollow"><img src="https://avatars.githubusercontent.com/u/32584037?v=4" width="150px;" alt="" style="max-width:100%;"><br><sub><b>Mamey</b></sub></a><br><a href="https://github.com/ImMamey/Practica-5-DDNS/commits?author=ImMamey" title="Commits"><g-emoji class="g-emoji" alias="book" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4d6.png">📖</g-emoji></a></td>
</tr>
</tbody>
</table>

---
## About this repository


This repository is a collection of automated codes written in TI-Basic for TI NSPIRE CX II CAS calculators.

The codes present here allow to calculate some of the most important numerical computation algorithms / numerical methods, step by step, and with iterations if applicable.

> For example:
<table align="center">
<tr>
    <td align="center"><img src="/resources/images/example.png" width="300px;" alt="" style="max-width:100%;"><br><sub><b>System of linear equations</b></sub></td>
    <td align="center"><img src="/resources/images/example2.png" width="330px;" alt="" style="max-width:100%;"><br><sub><b>Potential minima</b></sub></td>
    <td align="center"><img src="/resources/images/example3.png" width="350px;" alt="" style="max-width:100%;"><br><sub><b>Roots by secant method</b></sub></td>
    <td align="center"><img src="/resources/images/example4.png" width="350px;" alt="" style="max-width:100%;"><br><sub><b>Linear Gauss-Seidel Equations</b></sub></td>
</tr>
</table>

---

## Available codes:
* Interpolation (of second and third degree).
* Least Squares.
* Exponential minima.
* Potential minimums.
* Linear regression of 2nd degree.
* Linear regression of 3rd degree.
* Jacobi's iterative method for matrices.
* Convergence (spectral radius) for Jacobi.
* Gauss-Seidel iterative method for matrices.
* Square roots by the iterative method of the secant.
* Square roots by the iterative method of bisection.
* Square roots by Newton's iterative method.
* Newton's nonlinear systems of equations.

---

## Requirements
* [Texas Instruments NSpire CX II CAS](https://education.ti.com/en/products/calculators/graphing-calculators/ti-nspire-cx-ii-cx-ii-cas)
<p align="center">
    <img src="/resources/images/calc.jpg" title="calculator" width="300">
</p>

### Software and extras:

* Calculator with OS versión: 5.4.0.259 (at minimun)
* [TI-Nspire CX CAS Student Software](https://education.ti.com/en/software/details/en/36BE84F974E940C78502AA47492887AB/ti-nspirecxcas_pc_full) version: 6.0.3.374: Desktop program to test codes on PC and transfer files.
* [File transfer website](https://nspireconnect.ti.com/nsc/file-transfer): in the case of not having a license to use TI-Nspire CX CAS Student Software (OPTIONAL) 

---
## Installation on the calculator

1. Download the repository.
2. In the "`tns`" folder are all the `.tns` files, these are the codes that must be passed to the calculator (or to the student program).
3. Open the [web page for tns file transfer](https://nspireconnect.ti.com/nsc/file-transfer) and transfer all the `.tns` to the calculator.
> Preferably save the codes inside the `MyLib` folder inside the calculator.
4. In the calculator select the following options in order: `Home Button` → `Menu Button` → `B Button`/`refresh all libraries`


---

## Content of each tns file regarding the topic:



<table style="width:100%">
    <tr>
       <th> Topic </th>
       <th> TNS </th> 
       <th> Functions</th>
    </tr>
    <tr>
        <th rowspan="3">Roots of Nonlinear Equations</th>
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
        <th rowspan="2"> Systems of linear equations: Jacobi and Gauss-Seidel</th>
        <th> jacobi.tns  </th>
        <th> jacobi(a,b,x0,tol) <br> jacobi_conv(a,b,x0,tol)</th>
    </tr>
    <tr>
        <th> seidel.tns </th>
        <th> seidel(a,b,x0,tol) <br> seidel_conv(a,b,x0,tol)</th>
    </tr>
    <tr>
        <th> Systems of nonlinear equations: Newton</th>
        <th>sist_ecnl_newton.tns</th>
        <th>newton_sistecnl2i()</th>
    </tr>
    <tr>
        <th>Interpolation and curve fitting (least squares)</th>
        <th>interpol_minimos.tns</th>
        <th>
        interpol(x,y,n) <br> minimos2(x,y,n) <br> minimos_expone(x,y) <br> minimos_poten(x,y) 
        </th>
    </tr>
    <tr>
        <th>Numerical Integration</th>
        <th> integracion.tns</th>
        <th> intg_trap() <br> intg_longarco() <br> intg_trap2(a,b,tol,fx2)</th>
    </tr>
</table>

---

## Legal
#### Summary:
 1. The code in this repository is strictly educational.
 2. I am not responsible for the use (or possible damages) for the use of the codes present here.
 3. You are free to distribute the codes here present.

For more information read the file [`LICENSE`](resources/legal/LICENSE)