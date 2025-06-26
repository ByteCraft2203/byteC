# byteC
<!DOCTYPE html>
<html lang="es">
<head>
    <title>Principal</title>
    <link rel="stylesheet" href="Principal.CSS">
    <style>
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
        }
        
        .top-bar {
            background-color: #2c3e50;
            color: white;
            padding: 10px 20px;
            text-align: right;
        }
        
        .top-bar a {
            color: white;
            margin-left: 15px;
            text-decoration: none;
        }
        
        .header {
            background-color: #3498db;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .logo-container {
            display: flex;
            align-items: center;
            margin-right: 20px;
            font-size: 20px;
        }
        
        .logo {
            height: 60px;
            margin-right: 10px;
        }
        
        .logo-text {
            font-size: 12px;
            color: #333;
            max-width: 180px;
            margin: 15px;
        }
        
        .nav-menu {
            display: flex;
            list-style: none;
        }
        
        .nav-menu li {
            margin: 0 15px;
        }
        
        .nav-menu a {
            text-decoration: none;
            color: white;
            font-size: 20px;
            transition: color 0.3s;
        }
        
        .nav-menu a:hover {
            color: #333;
            font-size: 16px;
        }
        
        .search-icon {
            font-size: 20px;
            color: #747474;
        }
        
        .content {
            max-width: 1200px;
            margin: 30px auto;
            padding: 30px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        
        .page-title {
            color: #666;
            margin-bottom: 30px;
            font-weight: normal;
        }
        
        .support-section {
            display: flex;
            margin-top: 50px;
            align-items: center;
        }
        
        .support-icon {
            width: 150px;
            margin-right: 30px;
        }
        
        .support-text {
            color: #777;
            line-height: 3;
        }
        
        .support-link {
            margin-top: 20px;
            text-align: right;
        }
        
        .support-link a {
            color: #ff5252;
            text-decoration: none;
        }
        
        .support-link a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="top-bar">
        <a href="#"><i class="fa">f</i></a>
        <a href="#"><i class="fa">t</i></a>
    </div>
    
    <header class="header">
        <div class="logo-container">
            <img src="UEB.jpg" height="89px"> 
            <div class="logo-text">
                <strong>ByteCraft</strong><br>
                Unidad Educativa Baños
            </div>
        </div>
        
        <nav>
            <ul class="nav-menu">
                <li><a href="Principal.html">Inicio</a></li>
                <li><a href="Nosotros.HTML">Nosotros</a></li>
                <li><a href="CurriC.HTML">Curriculo</a></li>
                <li><a href="Contacto.Html">Contactanos</a></li>
                 <li><a href="">Contactanos</a></li>
            </ul>
        </nav>
        
        <div class="search-icon">
            <i class="fa">🔍</i>
        </div>
    </header>
    <center>
    <div class="content">
        <h1 class="page-title">Módulo de Soporte Técnico y Mantenimiento de Equipos Eléctricos</h1>
        <img src="mantenimiento,png.avif" height="300px">
        <div class="support-section">
            <div>
                <div class="support-text">
                    <p>Este servicio esta dirigido a realizar actividades de Soporte en cuanto a la Operatividad de Laptops y PCs el cual permitirá básicamente en localizar y corregir las averías o desperfectos que estén impidiendo que la máquina realice su función de manera normal.</p>
                </center>
                </div>
            </div>
        </div>
    </div>

    <div>
        
    </div>

    <div class="content">
        <center><h1 class="page-title">COMPETENCIA GENERAL</h1></center>
            <div class="support-text">
                <p>
                    Optimizar el tratamiento de la información mediante el procesamiento automático,
                    utilizando lenguajes de programación, bases de datos, herramientas ofimáticas, redes
                    informáticas, herramientas web, sistemas operativos y soporte técnico; proponiendo
                    soluciones creativas e innovadoras que respondan a los requerimientos de los usuarios,
                    aplicando procedimientos y metodologías informáticas vigentes.
                </p>
            </div>
            <div>
                <center><p>Realizado por Ariel Villamil y Mateo Guevara</p></center>
            </div>
    </div>
</body>
</html>
