< modelo >
  < div  id = " aplicativo " >
    < img  alt = " Vue logo "  src = " ./assets/logo.png " >
    < HelloWorld  msg = " Bem-vindo ao seu aplicativo Vue.js " />
    < calculadora ></ calculadora >
  </ div >
</ modelo >

< roteiro >
importe  HelloWorld  de  ' ./components/ HelloWorld .vue '
import  Calculator  from  ' ./components/ Calculator .vue '
exportação  padrão {
  nome :  ' Aplicativo ' ,
  componentes : {
    Olá Mundo
    Calculadora
  }
}
</ script >

< estilo >
#aplicativo {
  família de fontes : Avenir, Helvetica , Arial , sans-serif ;
  -webkit-font-smoothing : suavizado ;
  -moz-osx-font-smoothing : tons de cinza ;
  text-align : center ;
  cor : #2c3e50 ;
  margem superior : 60 px ;
}
  corpo {
    fundo : #31475e  !importante ;
  }
