# Pagina-2

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reportes</title>
    <link rel="stylesheet" href="estilos2.css">
    <link rel="stylesheet" href="styles.css">

   
    
</head>
<body>
    <nav class="nav">

        <div class="nav_conteiner">
            <h1 class="nav_logo">AACAYSA</h1>

            <div class="nav_menu">
                <ul>
                    <li><a href="index.html">Inicio</a></li>
                    <li><a href="Contacto.html">Contacto</a></li>
                </ul>
        </div>   
            </div>
   
    </nav>    




<!--Barra de busqueda-->

        <div class="buscar">
            <input type="text" id="buscador" placeholder="Buscar" required>
            <a href="" class="btn">
            <i class="icon-buscar"></i>

            </a>

        </div>


<!--Fecha-->
        <form action="" class="Fechas">
            <input type="date">
            <p>Fecha inicial</p>

            <input type="date">
            <p>Fecha final</p>

        </form>

<!--Checkbox-->
 
        
        <div class="wrap">     
            <form action="" class="formulario">
                <div class="checkbox">
                    <nav class="bloques">
                            <ul class="temp">
                            <li class="list_inside list--click">
                                <div class="list_button--click">
        
                                    <a href="#" class="nav_bloques">Datos de pedimento</a>
                                    <img src="barra.svg" alt="" class="list_arrow">
                                </div>
                                <ul class="list_show">
                                    
                                    <li class="articulos">
                                        <a href="nav_bloques_link--inside"></a>
                                        <input type="checkbox" name="Tipo de pedimento" id="Tipo de pedimento">
                                        <label for="Tipo de pedimento">Tipo de pedimento</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Aduana" id="Aduana">
                                        <label for="Aduana">Aduana</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Patente" id="Patente">
                                        <label for="Patente">Patente</label>
                                    </li>
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Numero de pedimento" id="Numero de pedimento">
                                        <label for="Numero de pedimento">Numero de pedimento</label>
                                    </li>
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Tipo de operacion" id="Tipo de operacion">
                                        <label for="Tipo de operacion">Tipo de operacion</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Clave del pedimento" id="Clave del pedimento">
                                        <label for="Clave del pedimento">Clave del pedimento</label>
                                    </li>
                                    
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Regimen" id="Regimen">
                                        <label for="Regimen">Regimen</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Fecha de pago" id="Fecha de pago">
                                        <label for="Fecha de pago">Fecha de pago</label>
                                    </li>
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Destino" id="Destino">
                                        <label for="Destino">Destino</label>
                                    </li>
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Tipo de cambio" id="Tipo de cambio">
                                        <label for="Tipo de cambio">Tipo de cambio</label>
                                    </li>
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Peso bruto" id="Peso bruto">
                                        <label for="Peso bruto">Peso bruto</label>
                                    </li>
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Aduana E/S" id="Aduana E/S">
                                        <label for="Aduana E/S">Aduana E/S</label>
                                    </li>

                                </ul> 

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Medios de transporte</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">
                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="Transporte Ent/Sal" id="Transporte Ent/Sal">
                                        <label for="Transporte Ent/Sal">Transporte Ent/Sal</label>
                                    </li>
                
                                    <li class="articulos">
                                        <input type="checkbox" name="Transporte arribo" id="Transporte arribo">
                                        <label for="Transporte arribo">Transporte arribo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Transporte salida" id="Transporte salida">
                                        <label for="Transporte salida">Transporte salida</label>
                                    </li>

                                </ul>
                                
                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos del Importador/Exportador</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">
                                
                                    <li class="articulos">
                                        <input type="checkbox" name="Importador/Exportador" id="Importador/Exportador">
                                        <label for="Importador/Exportador">Importador/Exportador</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="RFC" id="RFC">
                                        <label for="RFC">RFC</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Valor dolares" id="Valor dolares">
                                        <label for="Valor dolares">Valor dolares</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Valor aduana" id="Valor aduana">
                                        <label for="Valor aduana">Valor aduana</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Precio pagado" id="Precio pagado">
                                        <label for="Precio pagado">Precio pagado</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Incrementables</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Valor del seguro" id="Valor del seguro">
                                        <label for="Valor del seguro">Valor del seguro</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Seguros" id="Seguros">
                                        <label for="Seguros">Seguros</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Fletes" id="Fletes">
                                        <label for="Fletes">Fletes</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Embalajes" id="Embalajes">
                                        <label for="Embalajes">Embalajes</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Otros incrementables" id="Otros incrementables">
                                        <label for="Otros incrementables">Otros incrementables</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Incrementables" id="Incrementables">
                                        <label for="Incrementables">Incrementables</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Acuse de recibo" id="Acuse de recibo">
                                        <label for="Acuse de recibo">Acuse de recibo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Aduana despacho" id="Aduana despacho">
                                        <label for="Aduana despacho">Aduana despacho</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Marcas y numero" id="Marcas y numero">
                                        <label for="Marcas y numero">Marcas y numero</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Total de bultos" id="Total de bultos">
                                        <label for="Total de bultos">Total de bultos</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Total vehiculos" id="Total vehiculos">
                                        <label for="Total vehiculos">Total vehiculos</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Total efectivo" id="Total efectivo">
                                        <label for="Total efectivo">Total efectivo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Total otros" id="Total otros">
                                        <label for="Total otros">Total otros</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Total" id="Total">
                                        <label for="Total">Total</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Use de cupo" id="Use de cupo">
                                        <label for="Use de cupo">Use de cupo</label>
                                    </li>

                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="Clave prevalidor" id="Clave prevalidor">
                                        <label for="Clave prevalidor">Clave prevalidor</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Banco que paga" id="Banco que paga">
                                        <label for="Banco que paga">Banco que paga</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Decrementables</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Decrementables seguros" id="Decrementables seguros">
                                        <label for="Decrementables seguros">Decrementables seguros</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Decrementables fletes" id="Decrementables fletes">
                                        <label for="Decrementables fletes">Decrementables fletes</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Decrementables carga" id="Decrementables carga">
                                        <label for="Decrementables carga">Decrementables carga</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Decrementables decarga" id="Decrementables decarga">
                                        <label for="Decrementables decarga">Decrementables decarga</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Decrementables otros" id="Decrementables otros">
                                        <label for="Decrementables otros">Decrementables otros</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Decrementables" id="Decrementables">
                                        <label for="Decrementables">Decrementables</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Proveedor/Comprador</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Proveedor/Comprador" id="Proveedor/Comprador">
                                        <label for="Proveedor/Comprador">Proveedor/Comprador</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Id fiscal" id="Id Id fiscal">
                                        <label for="Id fiscal">Id fiscal</label>
                                    </li>
                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="Vinc." id="Vinc.">
                                        <label for="Vinc.">Vinc.</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de factura</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Num. factura" id="Num. factura">
                                        <label for="Num. factura">Num. factura</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Fecha fact." id="Fecha fact.">
                                        <label for="Fecha fact.">Fecha fact.</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Incoterm" id="Incoterm">
                                        <label for="Incoterm">Incoterm</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Moneda fact." id="Moneda fact.">
                                        <label for="Moneda fact.">Moneda fact.</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Valor Mon. Fact." id="Valor Mon. Fact.">
                                        <label for="Valor Mon. Fact.">Valor Mon. Fact.</label>
                                    </li>

                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="Factor Mon. Fact." id="Factor Mon. Fact.">
                                        <label for="Factor Mon. Fact.">Factor Mon. Fact.</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Val. Dolares Fact." id="Val. Dolares Fact.">
                                        <label for="Val. Dolares Fact.">Val. Dolares Fact.</label>
                                    </li>

                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="Pais V/C" id="Pais V/C">
                                        <label for="Pais V/C">Pais V/C</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Identificadores (Nivel pedimento)</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="E-Document" id="E-Document">
                                        <label for="E-Document">E-Document</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de contenedor</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Nombre del transportista-Identificación transporte-Candados" id="Nombre del transportista-Identificación transporte-Candados">
                                        <label for="Nombre del transportista-Identificación transporte-Candados">Nombre del transportista-Identificación transporte-Candados</label>
                                    </li>
                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="Guia master" id="Guia master">
                                        <label for="Guia master">Guia master</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Guia house" id="Guia house">
                                        <label for="Guia house">Guia house</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Identificadores (Nivel pedimento)</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Ident C1 C2 C3" id="Ident C1 C2 C3">
                                        <label for="Ident C1 C2 C3">Ident C1 C2 C3</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">


                                    <li class="articulos">
                                        <input type="checkbox" name="RFC sociedad" id="RFC sociedad">
                                        <label for="RFC sociedad">RFC sociedad</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de contenedor</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tipo contenedor" id="Tipo contenedor">
                                        <label for="Tipo contenedor">Tipo contenedor</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Numero contenedor" id="Numero contenedor">
                                        <label for="Numero contenedor">Numero contenedor</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="DTA efetivo" id="DTA efetivo">
                                        <label for="DTA efetivo"">DTA efetivo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Cuadro de liquidacion</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Prevalidador efectivo" id="Prevalidador efectivo">
                                        <label for="Prevalidador efectivo">Prevalidador efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Cuadro de liquidacion</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="IVA prevalidacion" id="IVA prevalidacion">
                                        <label for="IVA prevalidacion">IVA prevalidacion</label>
                                    </li>


                                    <li class="articulos">
                                        <input type="checkbox" name="Recargo efectivo" id="Recargo efectivo">
                                        <label for="Recargo efectivo">Recargo efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Cuadro de liquidacion</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Multas efectivo" id="Multas efectivo">
                                        <label for="Multas efectivo">Multas efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                 </ul>

                                 <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Cuadro de liquidacion</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="ECI efectivo" id="ECI efectivo">
                                        <label for="ECI efectivo">ECI efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasa de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Cuadro de liquidacion</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Contribuciones pedimento diferentes a efectivo" id="Contribuciones pedimento diferentes a efectivo">
                                        <label for="Contribuciones pedimento diferentes a efectivo">Contribuciones pedimento diferentes a efectivo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="DTA pendiente de pago" id="DTA pendiente de pago">
                                        <label for="DTA pendiente de pago">DTA pendiente de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="DTA exento de pago" id="DTA exento de pago">
                                        <label for="DTA exento de pago">DTA exento de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="DTA compensacion" id="DTA compensacion">
                                        <label for="DTA compensacion">DTA compensacion</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="DTA pago ya efectuado" id="DTA pago ya efectuado">
                                        <label for="DTA pago ya efectuado">DTA pago ya efectuado</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="A pagar a favor de SAT" id="A pagar a favor de SAT">
                                        <label for="A pagar a favor de SAT">A pagar a favor de SAT</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="CNT efectivo" id="CNT efectivo">
                                        <label for="CNT efectivo">CNT efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Observaciones</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Observaciones" id="Observaciones">
                                        <label for="Observaciones">Observaciones</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de modulacion</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Primer reconocimiento" id="Primer reconocimiento">
                                        <label for="Primer reconocimiento">Primer reconocimiento</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Segundo reconocimiento" id="Segundo reconocimiento">
                                        <label for="Segundo reconocimiento">Segundo reconocimiento</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Hora de pago" id="Hora de pago">
                                        <label for="Hora de pago">Hora de pagoo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Firma o acuse del banco" id="Firma o acuse del banco">
                                        <label for="Firma o acuse del banco">Firma o acuse del banco</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Numero de operacion" id="Numero de operacion">
                                        <label for="Numero de operacion">Numero de operacion</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Banco efectivo" id="Banco efectivo">
                                        <label for="Banco efectivo">Banco efectivo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Banco total" id="Banco total">
                                        <label for="Banco total">Banco total</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Pago rectificación" id="Pago rectificación">
                                        <label for="Pago rectificación">Pago rectificación</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos de pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Domicilio Importador/Exportador" id="Domicilio Importador/Exportador">
                                        <label for="Domicilio Importador/Exportador">Domicilio Importador/Exportador</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel pedimento</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Crédito en IVA 21" id="Crédito en IVA 21">
                                        <label for="Crédito en IVA 21">Crédito en IVA 21</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Garantía en IVA 22" id="Garantía en IVA 22">
                                        <label for="Garantía en IVA 22">Garantía en IVA 22</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Credito en IEPS 21" id="Crédito en IEPS 21">
                                        <label for="Credito en IEPS 21">Credito en IEPS 21</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Garantía en IEPS 22" id="Garantía en IEPS 22">
                                        <label for="Garantía en IEPS 22">Garantía en IEPS 22</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Numero de partida" id="Numero de partida">
                                        <label for="Numero de partida">Numero de partida</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Fraccion" id="Fraccion">
                                        <label for="Fraccion">Fraccion</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Vinculacion" id="Vinculacion">
                                        <label for="Vinculacion">Vinculacion</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Valoracion" id="Valoracion">
                                        <label for="Valoracion">Valoracion</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="UMC" id="UMC">
                                        <label for="UMC">UMC</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Cantidad UMC" id="Cantidad UMC">
                                        <label for="Cantidad UMC">Cantidad UMC</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="UMT" id="UMT">
                                        <label for="UMT">UMT</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Cantidad UMT" id="Cantidad UMT">
                                        <label for="Cantidad UMT">Cantidad UMT</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Pais V/C" id="Pais V/C">
                                        <label for="Pais V/C">Pais V/C</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Pais O/D" id="Pais O/D">
                                        <label for="Pais O/D">Pais O/D</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Descripcion" id="Descripcion">
                                        <label for="Descripcion">Descripcion</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Val. ADU/USD" id="Val. ADU/USD">
                                        <label for="Val. ADU/USD">Val. ADU/USD</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Imp. Precio Pag." id="Imp. Precio Pag">
                                        <label for="Imp. Precio Pag">Imp. Precio Pag</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Precio unitario" id="Precio unitario">
                                        <label for="Precio unitario">Precio unitario</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Val. Agreg" id="Val. Agreg">
                                        <label for="Val. Agreg">Val. Agreg</label>
                                    </li>
                                    
                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Marca" id="Marca">
                                        <label for="Marca">Marca</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Modelo" id="Modelo">
                                        <label for="Modelo">Modelo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Codigo de producto" id="Codigo de producto">
                                        <label for="Codigo de producto">Codigo de producto</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="IGI efectivo" id="IGI efectivo">
                                        <label for="IGI efectivo">IGI efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas a nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="IVA efectivo" id="IVA efectivo">
                                        <label for="IVA efectivo">IVA efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas a nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="CC efectivo" id="CC efectivo">
                                        <label for="CC efectivo">CC efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas a nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="ISAN efectivo" id="ISAN efectivo">
                                        <label for="ISAN efectivo">ISAN efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas a nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS efectivo" id="IEPS efectivo">
                                        <label for="IEPS efectivo">IEPS efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas a nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="ITV efectivo" id="ITV efectivo">
                                        <label for="ITV efectivo">ITV efectivo</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Tasas a nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Tasa" id="Tasa">
                                        <label for="Tasa">Tasa</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Contribuciones partida diferentes a efectivo" id="Contribuciones partida diferentes a efectivo">
                                        <label for="Contribuciones partida diferentes a efectivo">Contribuciones partida diferentes a efectivo</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="CC pendiente de pago" id="CC pendiente de pago">
                                        <label for="CC pendiente de pago">CC pendiente de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="CC compensación" id="CC compensación">
                                        <label for="CC compensación">CC compensación</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IVA pendiente de pago" id="IVA pendiente de pago">
                                        <label for="IVA pendiente de pago">IVA pendiente de pago</label>
                                    </li>
                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="IVA exento de pago" id="IVA exento de pago">
                                        <label for="IVA exento de pago">IVA exento de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IVA pago ya efectuado" id="IVA pago ya efectuado">
                                        <label for="IVA pago ya efectuado">IVA pago ya efectuado</label>
                                    </li>
                                    
                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS pendiente de pago" id="IEPS pendiente de pago">
                                        <label for="IEPS pendiente de pago">IEPS pendiente de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IGI temporal no sujeta a impuestos" id="IGI temporal no sujeta a impuestos">
                                        <label for="IGI temporal no sujeta a impuestoso">IGI temporal no sujeta a impuestos</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IGI pendiente de pago" id="IGI pendiente de pago">
                                        <label for="IGI pendiente de pago">IGI pendiente de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IGI exento de pago" id="IGI exento de pago">
                                        <label for="IGI exento de pago">IGI exento de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IGI compensación" id="IGI compensación">
                                        <label for="IGI compensación">IGI compensación</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IGI pago ya efectuado" id="IGI pago ya efectuado">
                                        <label for="IGI pago ya efectuado">IGI pago ya efectuado</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Datos nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="MT pendiente de pago" id="MT pendiente de pago">
                                        <label for="MT pendiente de pago">MT pendiente de pago</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="MT compensación" id="MT compensación">
                                        <label for="MT compensación">MT compensación</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IDENT C1 C2 C3" id="IDENT C1 C2 C3">
                                        <label for="IDENT C1 C2 C3">IDENT C1 C2 C3</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Observaciones" id="Observaciones">
                                        <label for="Observaciones">Observaciones</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Clave firma número valor comercial dólares-cantidad" id="Clave firma número valor comercial dólares-cantidad">
                                        <label for="Clave firma número valor comercial dólares-cantidad">Clave firma número valor comercial dólares-cantidad</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Vin-Kilometraje" id="Vin-Kilometraje">
                                        <label for="Vin-Kilometraje">Vin-Kilometraje</label>
                                    </li>

                                </ul>

                                <li class="list_inside list--click">
                                    <div class="list_button--click">
            
                                        <a href="#" class="nav_bloques">Valores nivel partida</a>
                                        <img src="barra.svg" alt="" class="list_arrow">
                                    </div>
                                <ul class="list_show">

                                    <li class="articulos">
                                        <input type="checkbox" name="Crédito en IVA 21" id="Crédito en IVA 21">
                                        <label for="Crédito en IVA 21">Crédito en IVA 21</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Garantía en IVA 22" id="Garantía en IVA 22">
                                        <label for="Garantía en IVA 22">Garantía en IVA 22</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Crédito en IEPS 21" id="Crédito en IEPS 21">
                                        <label for="Crédito en IEPS 21">Crédito en IEPS 21</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="Garantía en IEPS 22" id="Garantía en IEPS 22">
                                        <label for="Garantía en IEPS 22">Garantía en IEPS 22</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 22" id="IEPS 22">
                                        <label for="IEPS 22">IEPS 22</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 24" id="IEPS 24">
                                        <label for="IEPS 24">IEPS 24</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 25" id="IEPS 25">
                                        <label for="IEPS 25">IEPS 25</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 26" id="IEPS 26">
                                        <label for="IEPS 26">IEPS 26</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 27" id="IEPS 27">
                                        <label for="IEPS 27">IEPS 27</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 28" id="IEPS 28">
                                        <label for="IEPS 28">IEPS 28</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 29" id="IEPS 29">
                                        <label for="IEPS 29">IEPS 29</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 30" id="IEPS 30">
                                        <label for="IEPS 30">IEPS 30</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 31" id="IEPS 31">
                                        <label for="IEPS 31">IEPS 31</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 32" id="IEPS 32">
                                        <label for="IEPS 32">IEPS 32</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 33" id="IEPS 33">
                                        <label for="IEPS 33">IEPS 33</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS 34" id="IEPS 34">
                                        <label for="IEPS 34">IEPS 34</label>
                                    </li>

                                    <li class="articulos">
                                        <input type="checkbox" name="IEPS otros" id="IEPS otros">
                                        <label for="IEPS otros">IEPS otros</label>
                                    </li>

                                </ul>

                                
                            </ul>
                    </nav>
                 </div>   
            </form> 
            
    </div>
<script src="script.js"></script>
</body>
</html>
