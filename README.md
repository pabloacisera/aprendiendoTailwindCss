# aprendiendoTailwindCss

Se pueden aplicar estilos a traves de clases:

<h1 class="bg-yellow-600 text-cyan-700">Hello world</h1>
<h2 class="bg-slate-500 text-white">aprendiendo</h2>

para aplicar opacidad a bg luego de su valor se agrega / y aparece lista de opciones de opacidad...

o modificando el archivo tailwind.config.cs

 extend: {
      colors: {
        'azul-claro': '#243cff',
      }
    },


Boton con hover:
 <button class="bg-azul-claro text-white p-2 rounded-lg w-24 mx-auto block my-8 hover:bg-gray-900">Suscribite</button>

Div con gradiente:
  <div class="bg-gradient-to-tr from-slate-400 to stroke-lime-900">Gradiente</div>

como aplicar un borde:
<div class="bg-slate-300 border-2 border-b-gray-800 mt-3 pt-3">Border</div>


Podemos aplicar gradiente a texto con <span>..

 <div class="text-4xl text-orange-600">
        <span class="bg-gradient-to-r from-red-500 to-slate-300">Bienvenido</span>
    </div>