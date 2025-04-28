# algoritmos-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [Algoritmos Assignment 2 Solved](https://www.ankitcodinghub.com/product/algoritmos-grado-en-ingenieria-informatica-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117862&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Algoritmos Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Ordenación por selección y ordenación shell: El problema consiste en ordenar ascendentemente un vector de n números enteros. Como algoritmos de ordenación se utilizarán la ordenación por selección y la ordenación shell:

procedimiento Ordenacion por Seleccion (var v[1..n])

para i := 1 hasta n-1 hacer minj := i ; minx := v[i] ; para j := i+1 hasta n hacer si v[j] &lt; minx entonces

minj := j ; minx := v[j]

fin si

fin para;

v[minj] := v[i] ; v[i] := minx

fin para

fin procedimiento

procedimiento Ordenación shell (var v[1..n])

incremento := n; repetir

incremento := incremento div 2; para i := incremento+1 hasta n hacer

tmp := v[i]; j := i;

seguir := cierto;

mientras j-incremento &gt; 0 y seguir hacer

si tmp &lt; v[j-incremento] entonces

v[j] := v[j-incremento]; j := j-incremento

sino seguir := falso fin si

fin mientras; v[j] := tmp

fin para

hasta incremento = 1

fin procedimiento

1. Implemente los algoritmos de ordenación por selección y shell.

void ord_sel (int v [], int n); void ord_shell (int v [], int n);

2. Valide el correcto funcionamiento de la implementación.

&gt; ./test

Inicializacion aleatoria

3, -3, 0, 17, -5, 2, 11, 13, 6, 1, 7, 14, 1, -2, 5, -14, -2

ordenado? 0

Ordenacion por Seleccion

-14, -5, -3, -2, -2, 0, 1, 1, 2, 3, 5, 6, 7, 11, 13, 14, 17 ordenado? 1

1

Inicializacion descendente

10, 9, 8, 7, 6, 5, 4, 3, 2, 1

ordenado? 0

Ordenacion por Seleccion

1, 2, 3, 4, 5, 6, 7, 8, 9, 10 ordenado? 1

3. Determine los tiempos de ejecución para distintos tamaños del vector y para tres diferentes situaciones iniciales: (a) el vector ya está ordenado en orden ascendente, (b) el vector ya está ordenado pero en orden descendente, y (c) el vector está inicialmente desordenado (véase la figura 1).

void ascendente(int v [], int n) {

int i; for (i=0; i &lt; n; i++)

v[i] = i;

}

Figura 1: Inicialización ascendente

4. Calcule empíricamente las complejidades de los algoritmos para cada una de las diferentes situaciones iniciales del vector (i.e., 6 tablas) (figura 2).

5. Entregue los ficheros con el código C y el fichero .txt con el informe por medio de la tarea Entrega Práctica 2 en la página de Algoritmos en https://campusvirtual.udc.gal. Se recuerda que el límite para completar la tarea es el sábado 23 de octubre a las 23:59, y una vez subidos los archivos no se podrán cambiar. Todos los compañeros que forman un equipo tienen que entregar el trabajo.

Ordenación por selección con inicialización descendente

n t(n) t(n)/n^1.8 t(n)/n^2 t(n)/n^2.2

(*) 500 247.03 0.003425 0.000988 0.000285

1000 953.00 0.003794 0.000953 0.000239

2000 3818.00 0.004365 0.000955 0.000209

4000 15471.00 0.005079 0.000967 0.000184

8000 69474.00 0.006550 0.001086 0.000180

16000 257089.00 0.006961 0.001004 0.000145

32000 1023540.00 0.007959 0.001000 0.000126

Figura 2: Parte de la posible salida por pantalla de la ejecución del programa principal

2
