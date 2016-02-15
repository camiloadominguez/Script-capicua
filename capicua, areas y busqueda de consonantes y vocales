/*Ejercicio 1
Area del cuadrado
*/
var lado = 5;
var areaCuadrado =" ";
areaCuadrado = lado*lado;
console.log(areaCuadrado);

//area del circulo

var radio = 7;
var areaCirculo = " ";
areaCirculo = Math.PI*Math.pow(radio,2);
console.log(areaCirculo);

//area del triangulo

var base = 4;
var altura = 3;
areaTriangulo = (base*altura)/2;
console.log(areaTriangulo);

/*ejercicio 2

contar el numero de vocales 

*/
var vocales = [["a",0],["e",0],["i",0],["o",0],["u",0]];
var palabra = "mUrCieLago";
palabra = palabra.toLowerCase();	

for(var i = 0; i < palabra.length; i++)
	{
	for(var j=0;j<5;j++)	
		{
		if(palabra.charAt(i)===vocales[j][0])
			{
			vocales[j][1]=vocales[j][1]+1;
			}
		else
			{
			console.log("no se encontro la vocal");	
			}
		}

	}
for(var resultado = 0; resultado<5;resultado++)
	{
	console.log("de la vocal "+vocales[resultado][0]+" se encontraron "+vocales[resultado][1]+" resultados");
	}

/* ejercicio 3

contar el numero de consonantes

*/
var vocales = [["b",0],["c",0],["d",0],["f",0],["g",0],["h",0],["j",0],["k",0],["l",0],["m",0],["n",0],["ñ",0],["p",0],["q",0],["r",0],["s",0],["t",0],["v",0],["w",0],["x",0],["y",0],["z",0]];
var palabra = "parAnGUTIrimiCUAro";
palabra = palabra.toLowerCase();	

for(var i = 0; i < palabra.length; i++)
	{
	for(var j=0;j<vocales.length;j++)	
		{
		if(palabra.charAt(i)===vocales[j][0])
			{
			vocales[j][1]=vocales[j][1]+1;
			}
		else
			{
			console.log("no se encontro la vocal");	
			}
		}

	}
for(var resultado = 0; resultado<vocales.length;resultado++)
	{
	console.log("de la vocal "+vocales[resultado][0]+" se encontraron "+vocales[resultado][1]+" resultados");
	}

/* ejercicio 4

Capicua
*/

var numero = "12344321"
var capicua = (numero.length/2);
var astring = capicua.toString();
var resultado = astring.charAt(0);
var array = [];
var array2 = [];
if(numero.length%2==0)
	{
	for(var i = 0; i<resultado ;i++ )
		{
		array.push(numero.charAt(i));
		}
	for(var j = numero.length-1; j>=resultado ; j-- )
		{
		array2.push(numero.charAt(j));
		}	
	for(var k=0 ;k<array.length;k++)
		{
		if(array[k]==array2[k])
			{
			if(k==array.length-1)
				{
				console.log("correcto el numero es capicua");
				}
			}
		else
			{
			console.log("El numero no es capicua");
			break;
			}

		}
	}
else if (numero.length%2==1)
	{
	for(var i = 0; i<resultado ;i++ )
		{
		array.push(numero.charAt(i));
		}
	for(var j = numero.length-1; j>=resultado ; j-- )
		{
		array2.push(numero.charAt(j));
		}	
	for(var k=0 ;k<array.length;k++)
		{
		if(array[k]==array2[k])
			{
			if(k==array.length-1)
				{
				console.log("correcto el numero es capicua");
				}
			}
		else
			{
			console.log("El numero no es capicua");
			break;
			}

		}
	}
