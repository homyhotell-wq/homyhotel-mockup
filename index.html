<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HomyHotel - Alojamiento con Servicio Hotelero</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #f9faf8; }
        .hero-background {
            /* Mantiene el azul oscuro para el contraste del texto, pero usaremos el ámbar para resaltar */
            background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.6)), url('https://placehold.co/1200x600/1e293b/ffffff?text=Fondo+Departamento+Premium');
            background-size: cover;
            background-position: center;
        }
        .chart-container { position: relative; width: 100%; max-width: 300px; height: 300px; margin: 0 auto; }
        .sticky-nav {
            backdrop-filter: blur(10px);
            background-color: rgba(255, 255, 255, 0.9);
        }
    </style>
</head>
<body>

<div id="app">
    <!-- Navegación Fija -->
    <header id="navbar" class="sticky-nav sticky top-0 z-50 shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo con color Ámbar -->
                <a href="#" class="flex-shrink-0 font-bold text-2xl text-amber-600">HomyHotel</a>
                <nav class="hidden md:flex space-x-8">
                    <a href="#propiedades" class="text-gray-700 hover:text-amber-600 transition duration-150">Propiedades</a>
                    <a href="#servicios" class="text-gray-700 hover:text-amber-600 transition duration-150">Servicios</a>
                    <a href="#contacto" class="text-gray-700 hover:text-amber-600 transition duration-150">Contacto</a>
                    <!-- Botón Mi Reserva con color Ámbar -->
                    <button onclick="document.getElementById('busqueda-resultados').scrollIntoView({ behavior: 'smooth' });" class="px-3 py-1 text-sm bg-amber-500 text-white rounded-full hover:bg-amber-600 transition duration-150">Mi Reserva</button>
                </nav>
            </div>
        </div>
    </header>

    <!-- 1. Sección Principal (Hero) con Buscador Central -->
    <section class="hero-background h-[60vh] flex items-center justify-center p-4">
        <div class="text-center">
            <h1 class="text-5xl font-extrabold text-white mb-4">Alojamiento con la <span class="text-amber-300">flexibilidad de un hogar</span></h1>
            <p class="text-xl text-gray-200 mb-10">y el servicio dedicado de un hotel.</p>

            <!-- Buscador Central (Simulación de Widget de App de Booking) -->
            <div class="bg-white p-6 md:p-8 rounded-xl shadow-2xl max-w-4xl mx-auto">
                <h2 class="text-xl font-semibold text-gray-800 mb-4">Encuentra tu próximo Homy</h2>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                    <!-- Destino -->
                    <div class="col-span-2 md:col-span-1">
                        <select id="destino" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-amber-500 focus:border-amber-500">
                            <option value="">Destino</option>
                            <option value="santiago">Santiago Centro</option>
                            <option value="providencia">Providencia</option>
                            <option value="lascondes">Las Condes</option>
                        </select>
                    </div>
                    <!-- Fechas -->
                    <input type="date" id="checkin" placeholder="Check-in" class="col-span-1 p-3 border border-gray-300 rounded-lg focus:ring-amber-500 focus:border-amber-500">
                    <input type="date" id="checkout" placeholder="Check-out" class="col-span-1 p-3 border border-gray-300 rounded-lg focus:ring-amber-500 focus:border-amber-500">
                    <!-- Huéspedes -->
                    <div class="col-span-2 md:col-span-1">
                        <input type="number" id="huespedes" min="1" max="8" placeholder="Huéspedes" value="2" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-amber-500 focus:border-amber-500">
                    </div>
                </div>
                <!-- Botón Buscar Propiedades con color Ámbar -->
                <button onclick="buscarPropiedades()" class="mt-6 w-full md:w-auto px-8 py-3 bg-amber-500 text-white font-bold rounded-xl shadow-md hover:bg-amber-600 transition duration-150 transform hover:scale-[1.02]">
                    Buscar Propiedades
                </button>
            </div>
        </div>
    </section>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">

        <!-- Área Dinámica de Resultados de Búsqueda -->
        <section id="busqueda-resultados" class="min-h-[20vh] mb-16 pt-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b pb-2">Resultados de tu Búsqueda</h2>
            <div id="resultados-content" class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <p id="mensaje-busqueda" class="md:col-span-3 text-gray-600 italic">Ingresa un destino y fechas para ver la disponibilidad.</p>
                <!-- Las tarjetas de resultados se inyectarán aquí -->
            </div>
        </section>

        <!-- 2. Sección de Propuestas de Valor (Servicios Hoteleros Flexibles) -->
        <section id="servicios" class="mb-16">
            <h2 class="text-4xl font-extrabold text-gray-800 text-center mb-4">Servicios Hoteleros a tu Medida</h2>
            <p class="text-lg text-gray-600 text-center mb-12">Disfruta de la comodidad de un hogar con la atención profesional que mereces. Tú eliges.</p>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Tarjeta 1: Limpieza Flexible (Borde Ámbar) -->
                <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-amber-500 hover:shadow-xl transition duration-300">
                    <span class="text-3xl text-amber-600 mb-3 block">✨</span>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Limpieza Profunda Extra</h3>
                    <p class="text-gray-600">Programa limpiezas adicionales durante tu estadía según tu necesidad. Fácil de añadir en el checkout.</p>
                    <ul class="mt-3 text-sm text-gray-500 list-disc list-inside">
                        <li>Se añade como un "add-on" (Producto separado).</li>
                        <li>Cobro por servicio de precio fijo.</li>
                    </ul>
                </div>
                <!-- Tarjeta 2: Ropa de Cama y Baño (Borde Ámbar) -->
                <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-amber-500 hover:shadow-xl transition duration-300">
                    <span class="text-3xl text-amber-600 mb-3 block">🧖‍♀️</span>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Cambio de Ropa Frecuente</h3>
                    <p class="text-gray-600">Cambio de sábanas y toallas iniciales incluidos, con sets extra disponibles a solicitud.</p>
                    <ul class="mt-3 text-sm text-gray-500 list-disc list-inside">
                        <li>Un set de toallas extra es un "add-on" (Producto separado).</li>
                        <li>Permite cobro por cantidad (por set).</li>
                    </ul>
                </div>
                <!-- Tarjeta 3: Lavandería y Logística (Borde Ámbar) -->
                <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-amber-500 hover:shadow-xl transition duration-300">
                    <span class="text-3xl text-amber-600 mb-3 block">🧺</span>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Servicio de Lavandería Personal</h3>
                    <p class="text-gray-600">Deja tu ropa en la puerta y recíbela limpia y planchada. Cobro simple por bolsa o kilo.</p>
                    <ul class="mt-3 text-sm text-gray-500 list-disc list-inside">
                        <li>Se gestiona como un "Producto de Servicio" fijo.</li>
                        <li>Optimiza la liquidación con el dueño.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- 3. Sección de Gestión de Dueños y Dashboard (Mock) -->
        <section id="gestion" class="mb-16 bg-white p-8 rounded-xl shadow-inner">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">Métricas Operacionales Clave (Administración)</h2>
            <p class="text-gray-600 mb-8">La integración con Metacampos permite una conciliación de ingresos y un seguimiento transparente de las propiedades y servicios, fundamental para la liquidación con dueños.</p>

            <div class="grid md:grid-cols-3 gap-8 items-center">
                <!-- Indicador Clave (Fondo y Texto Ámbar) -->
                <div class="flex flex-col space-y-4">
                    <div class="bg-amber-50 p-4 rounded-lg shadow">
                        <p class="text-sm text-gray-500">Uso de Metacampos</p>
                        <p class="text-2xl font-bold text-amber-700 mt-1">5 Claves Utilizadas</p>
                        <p class="text-xs text-gray-500 mt-2">ID Propietario, Tarifa Dueño, Capacidad Máx., etc.</p>
                    </div>
                    <div class="bg-amber-50 p-4 rounded-lg shadow">
                        <p class="text-sm text-gray-500">Integración PMS</p>
                        <p class="text-2xl font-bold text-green-600 mt-1">Automatización vía Zapier/App</p>
                        <p class="text-xs text-gray-500 mt-2">Flujo de trabajo post-checkout esencial.</p>
                    </div>
                </div>

                <!-- Gráfico de Ocupación (Chart.js) -->
                <div class="md:col-span-2 bg-gray-50 p-4 rounded-lg shadow-md">
                    <h3 class="text-lg font-semibold text-gray-800 mb-4">Proporción de Productos de Servicio</h3>
                    <p class="text-sm text-gray-500 mb-4">Distribución de tipos de productos activos en Shopify para liquidación.</p>
                    <div class="chart-container">
                        <canvas id="tipoProductoChart"></canvas>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. Sección de Propiedades Destacadas (Listado) -->
        <section id="propiedades" class="pt-8">
            <h2 class="text-4xl font-extrabold text-gray-800 text-center mb-4">Nuestras Propiedades Destacadas</h2>
            <p class="text-lg text-gray-600 text-center mb-12">Apartamentos seleccionados que combinan la mejor ubicación y servicios.</p>
            
            <div id="propiedades-destacadas-container" class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Tarjetas de propiedades inyectadas por JS -->
            </div>
        </section>

        <!-- 5. Pie de Página Simple -->
        <footer id="contacto" class="mt-16 border-t pt-8 text-center text-gray-500 text-sm">
            <p>HomyHotel es una plataforma impulsada por Shopify y Apps de Booking robustas.</p>
            <p class="mt-1">&copy; 2025 HomyHotel. Todos los derechos reservados.</p>
        </footer>

    </main>
</div>

<script>
    const dataPropiedades = [
        {
            id: 101,
            titulo: 'Depto. Loft Moderno - Santiago Centro',
            descripcion: 'Ideal para ejecutivos. Capacidad 2. Cerca del metro.',
            precio: 75000,
            camas: 1,
            destino: 'santiago',
            img: 'https://placehold.co/400x250/374151/ffffff?text=Depto+Santiago'
        },
        {
            id: 205,
            titulo: 'Departamento Familiar - 3 Dormitorios',
            descripcion: 'Perfecto para familias. Capacidad 6. Vista a la cordillera.',
            precio: 95000,
            camas: 3,
            destino: 'providencia',
            img: 'https://placehold.co/400x250/1f2937/ffffff?text=Depto+Providencia'
        },
        {
            id: 310,
            titulo: 'Estudio Premium - Las Condes',
            descripcion: 'Lujo y comodidad en el corazón de la zona financiera.',
            precio: 85000,
            camas: 1,
            destino: 'lascondes',
            img: 'https://placehold.co/400x250/4b5563/ffffff?text=Depto+Las+Condes'
        }
    ];

    // Colores del gráfico actualizados a tonos Ámbar
    const dataGrafico = {
        labels: ['Apartamentos (Producto)', 'Servicios (Producto)', 'Tasa Obligatoria (App)'],
        datasets: [{
            data: [45, 30, 25],
            backgroundColor: ['#F59E0B', '#FCD34D', '#FEF3C7'],
            hoverOffset: 4
        }]
    };

    function formatCLP(amount) {
        return new Intl.NumberFormat('es-CL', { style: 'currency', currency: 'CLP', minimumFractionDigits: 0 }).format(amount);
    }

    function renderPropiedades(propiedades, containerId) {
        const container = document.getElementById(containerId);
        container.innerHTML = propiedades.map(prop => `
            <div class="bg-white rounded-xl shadow-lg overflow-hidden transform hover:scale-[1.01] transition duration-300 cursor-pointer">
                <img src="${prop.img}" alt="${prop.titulo}" class="w-full h-48 object-cover">
                <div class="p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-1">${prop.titulo}</h3>
                    <p class="text-sm text-gray-500 mb-3">📍 Destino: ${prop.destino.charAt(0).toUpperCase() + prop.destino.slice(1)}</p>
                    <!-- Precio con color Ámbar -->
                    <p class="text-2xl font-bold text-amber-600 mb-4">${formatCLP(prop.precio)} <span class="text-sm font-normal text-gray-500">/ noche</span></p>
                    <p class="text-gray-600 text-sm mb-4">${prop.descripcion}</p>
                    <div class="flex justify-between items-center">
                        <p class="text-sm font-medium text-gray-700">🛌 ${prop.camas} Dormitorio(s)</p>
                        <!-- Botón Ver Detalles con color Ámbar -->
                        <button onclick="alert('Simulación: Redirección al producto de Shopify para Reservar (con App de Booking integrada)')" class="px-4 py-2 bg-amber-500 text-white text-sm font-medium rounded-lg hover:bg-amber-600 transition duration-150">
                            Ver Detalles
                        </button>
                    </div>
                </div>
            </div>
        `).join('');
    }

    function buscarPropiedades() {
        const destino = document.getElementById('destino').value;
        const checkin = document.getElementById('checkin').value;
        const checkout = document.getElementById('checkout').value;
        const huespedes = parseInt(document.getElementById('huespedes').value);

        const resultadosContent = document.getElementById('resultados-content');
        const mensajeBusqueda = document.getElementById('mensaje-busqueda');

        if (!destino || !checkin || !checkout || isNaN(huespedes)) {
            mensajeBusqueda.textContent = 'Por favor, completa todos los campos de búsqueda.';
            resultadosContent.innerHTML = '';
            return;
        }

        mensajeBusqueda.textContent = '';
        
        const resultadosFiltrados = dataPropiedades.filter(prop => 
            prop.destino === destino && prop.camas >= Math.ceil(huespedes / 2) // Mock logic: 2 personas por cama/dormitorio
        );

        if (resultadosFiltrados.length === 0) {
            resultadosContent.innerHTML = '<p class="md:col-span-3 text-red-500 font-semibold">❌ No encontramos propiedades disponibles con esos criterios. Prueba otras fechas o destinos.</p>';
        } else {
            resultadosContent.innerHTML = '<p class="md:col-span-3 text-green-600 font-semibold mb-4">✅ ¡Disponibilidad encontrada! Haz clic para reservar:</p>';
            renderPropiedades(resultadosFiltrados, 'resultados-content');
            document.getElementById('busqueda-resultados').scrollIntoView({ behavior: 'smooth' });
        }
    }

    function initCharts() {
        const ctx = document.getElementById('tipoProductoChart').getContext('2d');
        new Chart(ctx, {
            type: 'doughnut',
            data: dataGrafico,
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'bottom',
                    },
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                let label = context.label || '';
                                if (label) {
                                    label += ': ';
                                }
                                if (context.parsed !== null) {
                                    label += context.parsed + '%';
                                }
                                return label;
                            }
                        }
                    }
                }
            }
        });
    }

    window.onload = function() {
        // Renderizar propiedades destacadas al cargar
        renderPropiedades(dataPropiedades, 'propiedades-destacadas-container');
        // Inicializar gráfico de administración
        initCharts();
    };
</script>

</body>
</html>
