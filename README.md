<!-- Pagina de inicio -->

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tienda Sara - Inicio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #2c3e50; color: white; padding: 15px; text-align: center; }
        nav a { color: white; margin: 0 10px; text-decoration: none; font-weight: bold; }
        .buscador { margin-top: 10px; }
        .banner { background-color: #3498db; color: white; padding: 40px; text-align: center; }
        .seccion { padding: 20px; max-width: 900px; margin: auto; background: white; margin-top: 20px; border-radius: 5px; }
        .grid { display: flex; gap: 15px; justify-content: space-around; flex-wrap: wrap; }
        .tarjeta { border: 1px solid #ddd; padding: 15px; border-radius: 5px; text-align: center; width: 30%; }
        .btn { background-color: #27ae60; color: white; padding: 8px 12px; text-decoration: none; border-radius: 3px; display: inline-block; }
        footer { background-color: #2c3e50; color: white; text-align: center; padding: 15px; margin-top: 30px; }
    </style>
</head>
<body>

    <!-- 1. Encabezado con buscador y menú -->
    <header>
        <h1>Tienda Sara</h1>
        <div class="buscador">
            <input type="text" placeholder="Buscar productos...">
            <button>Buscar</button>
        </div>
        <br>
        <nav>
            <a href="index.html">Inicio</a> |
            <a href="galeria.html">Productos</a> |
            <a href="carrito.html">Carrito</a>
        </nav>
    </header>

    <!-- 2. Banner principal con CTA -->
    <div class="banner">
        <h2>¡Grandes Descuentos de Temporada!</h2>
        <p>Encuentra lo mejor en tecnología, calzado y hogar.</p>
        <a href="galeria.html" class="btn">Compra Ahora</a>
    </div>

    <!-- 3. Categorías principales -->
    <div class="seccion">
        <h3>Categorías Principales</h3>
        <div class="grid">
            <div class="tarjeta">📱 Electrónica</div>
            <div class="tarjeta">🧊 Línea Blanca</div>
            <div class="tarjeta">👟 Ropa y Calzado</div>
        </div>
    </div>

    <!-- 4. Productos Populares -->
    <div class="seccion">
        <h3>Productos Recomendados</h3>
        <div class="grid">
            <div class="tarjeta">
                <h4>Smart TV 55"</h4>
                <p>$8,500.00</p>
                <a href="galeria.html" class="btn">Ver producto</a>
            </div>
            <div class="tarjeta">
                <h4>Audífonos</h4>
                <p>$1,200.00</p>
                <a href="galeria.html" class="btn">Ver producto</a>
            </div>
        </div>
    </div>

    <!-- 5. Quiénes Somos -->
    <div class="seccion">
        <h3>Sobre Nosotros</h3>
        <p><b>Misión:</b> Brindar los mejores productos con el mejor servicio y calidad.</p>
        <p><b>Visión:</b> Ser la tienda preferida por todas las familias.</p>
    </div>

    <!-- 6. Testimonios -->
    <div class="seccion">
        <h3>Opiniones de Clientes</h3>
        <p><i>"Excelente atención y los envíos son muy rápidos."</i> - María F.</p>
    </div>

    <!-- 7. Pie de página -->
    <footer>
        <p>Contacto: contacto@tiendasara.com | Tel: 800-220-7735</p>
        <p>&copy; 2026 Tienda Sara</p>
    </footer>

</body>
</html>

<!-- Galería de productos -->

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tienda Sara - Productos</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #2c3e50; color: white; padding: 15px; text-align: center; }
        nav a { color: white; margin: 0 10px; text-decoration: none; font-weight: bold; }
        .contenido { display: flex; padding: 20px; max-width: 900px; margin: auto; gap: 20px; }
        .filtros { width: 30%; background: white; padding: 15px; border-radius: 5px; }
        .productos { width: 70%; display: flex; flex-wrap: wrap; gap: 15px; }
        .producto { background: white; padding: 15px; border-radius: 5px; border: 1px solid #ddd; width: 45%; text-align: center; }
        .btn { background-color: #3498db; color: white; border: none; padding: 8px; cursor: pointer; border-radius: 3px; }
    </style>
</head>
<body>

    <header>
        <h1>Tienda Sara</h1>
        <nav>
            <a href="index.html">Inicio</a> |
            <a href="galeria.html">Productos</a> |
            <a href="carrito.html">Carrito</a>
        </nav>
    </header>

    <div class="contenido">
        <!-- Filtros -->
        <div class="filtros">
            <h3>Filtrar por:</h3>
            <label>Categoría:</label><br>
            <select>
                <option>Todas</option>
                <option>Electrónica</option>
                <option>Línea Blanca</option>
            </select>
            <br><br>
            <label>Marca:</label><br>
            <select>
                <option>Todas</option>
                <option>Samsung</option>
                <option>Sony</option>
            </select>
        </div>

        <!-- Lista de productos -->
        <div class="productos">
            <div class="producto">
                <h4>Smart TV 55"</h4>
                <p><b>Marca:</b> Samsung</p>
                <p><b>Precio:</b> $8,500.00</p>
                <button class="btn">Agregar al Carrito</button>
            </div>
            <div class="producto">
                <h4>Audífonos</h4>
                <p><b>Marca:</b> Sony</p>
                <p><b>Precio:</b> $1,200.00</p>
                <button class="btn">Agregar al Carrito</button>
            </div>
            <div class="producto">
                <h4>Tenis Running</h4>
                <p><b>Marca:</b> Nike</p>
                <p><b>Precio:</b> $1,499.50</p>
                <button class="btn">Agregar al Carrito</button>
            </div>
        </div>
    </div>

</body>
</html>

<!-- Carrito de compras -->

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tienda Sara - Carrito</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #2c3e50; color: white; padding: 15px; text-align: center; }
        nav a { color: white; margin: 0 10px; text-decoration: none; font-weight: bold; }
        .contenedor { max-width: 800px; margin: 20px auto; background: white; padding: 20px; border-radius: 5px; }
        table { width: 100%; border-collapse: collapse; }
        th, td { border-bottom: 1px solid #ddd; padding: 10px; text-align: left; }
        .resumen { margin-top: 20px; text-align: right; }
        .btn-pagar { background-color: #27ae60; color: white; padding: 10px 20px; border: none; font-size: 16px; cursor: pointer; border-radius: 3px; }
    </style>
</head>
<body>

    <header>
        <h1>Tienda Sara</h1>
        <nav>
            <a href="index.html">Inicio</a> |
            <a href="galeria.html">Productos</a> |
            <a href="carrito.html">Carrito</a>
        </nav>
    </header>

    <div class="contenedor">
        <h2>Tu Carrito de Compras</h2>
        
        <!-- Tabla de productos agregados -->
        <table>
            <tr>
                <th>Producto</th>
                <th>Cantidad</th>
                <th>Subtotal</th>
            </tr>
            <tr>
                <td>Smart TV 55"</td>
                <td>1</td>
                <td>$8,500.00</td>
            </tr>
            <tr>
                <td>Audífonos Bluetooth</td>
                <td>1</td>
                <td>$1,200.00</td>
            </tr>
        </table>

        <!-- Resumen -->
        <div class="resumen">
            <h3>Total: $9,700.00</h3>
            <button class="btn-pagar">PAGAR</button>
        </div>
    </div>

</body>
</html>
