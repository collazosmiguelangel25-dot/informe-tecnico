<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informe Técnico</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Inter from Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
        .container {
            max-width: 800px;
        }
        .nav-link.active {
            font-weight: bold;
            color: #1d4ed8;
            border-bottom: 2px solid #1d4ed8;
        }
        .section {
            display: none;
        }
        .section.active {
            display: block;
        }
        .card {
            background-color: white;
            border-radius: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gray-100 p-8 flex flex-col items-center min-h-screen">

    <!-- Main Container -->
    <div class="container bg-white rounded-3xl shadow-lg p-8 md:p-12">

        <!-- Header -->
        <header class="text-center mb-10">
            <h1 class="text-4xl font-extrabold text-blue-800 tracking-tight">INFORME TÉCNICO</h1>
            <p class="mt-4 text-lg text-gray-600">
                Con este proyecto, queremos dar a conocer un poco sobre el informe técnico, abordando temas como su estructura, para qué sirve, sus características, etc.
            </p>
        </header>

        <!-- Navigation Menu -->
        <nav class="flex flex-wrap justify-center space-x-4 md:space-x-8 mb-10 border-b border-gray-300 pb-4">
            <a href="#intro" class="nav-link text-gray-600 hover:text-blue-800 transition duration-300 p-2 text-center" onclick="showSection('intro')">Introducción</a>
            <a href="#que-es" class="nav-link text-gray-600 hover:text-blue-800 transition duration-300 p-2 text-center" onclick="showSection('que-es')">¿Qué es?</a>
            <a href="#caracteristicas" class="nav-link text-gray-600 hover:text-blue-800 transition duration-300 p-2 text-center" onclick="showSection('caracteristicas')">Características</a>
            <a href="#estructura" class="nav-link text-gray-600 hover:text-blue-800 transition duration-300 p-2 text-center" onclick="showSection('estructura')">Estructura</a>
            <a href="#interactivo" class="nav-link text-gray-600 hover:text-blue-800 transition duration-300 p-2 text-center" onclick="showSection('interactivo')">Interactivo</a>
        </nav>

        <!-- Content Sections -->
        <main>
            <!-- Introducción -->
            <section id="intro" class="section active">
                <div class="card p-6">
                    <h2 class="text-2xl font-bold mb-4 text-blue-700">1. Introducción</h2>
                    <p class="text-gray-700">
                        Los informes técnicos son documentos esenciales en cualquier campo, ya que permiten comunicar de manera clara, precisa y concisa los resultados de una investigación, proyecto o estudio. Comprender su estructura y propósito es fundamental para la correcta toma de decisiones y el desarrollo de proyectos.
                    </p>
                </div>
            </section>

            <!-- ¿Qué es un informe técnico? -->
            <section id="que-es" class="section">
                <div class="card p-6">
                    <h2 class="text-2xl font-bold mb-4 text-blue-700">2. ¿Qué es un informe técnico?</h2>
                    <p class="text-gray-700">
                        Un informe técnico es un documento escrito que describe los detalles de un proceso, investigación o proyecto. Su objetivo es presentar información de manera objetiva y basada en evidencia para una audiencia específica, que puede ser interna (superiores, colegas) o externa (clientes, inversores). A diferencia de otros tipos de informes, se centra en datos, hechos y conclusiones prácticas.
                    </p>
                </div>
            </section>

            <!-- Características -->
            <section id="caracteristicas" class="section">
                <div class="card p-6">
                    <h2 class="text-2xl font-bold mb-4 text-blue-700">3. Características</h2>
                    <ul class="list-disc list-inside space-y-2 text-gray-700">
                        <li>**Objetividad:** La información se presenta de forma imparcial, sin opiniones personales.</li>
                        <li>**Claridad y Precisión:** El lenguaje es técnico pero comprensible, evitando ambigüedades.</li>
                        <li>**Estructura Lógica:** Sigue un orden predefinido (introducción, desarrollo, conclusión).</li>
                        <li>**Orientación a la Solución:** A menudo, presenta recomendaciones para resolver un problema o mejorar un proceso.</li>
                        <li>**Uso de Evidencia:** Se apoya en datos, gráficos, tablas y fuentes fiables.</li>
                    </ul>
                </div>
            </section>

            <!-- Estructura -->
            <section id="estructura" class="section">
                <div class="card p-6">
                    <h2 class="text-2xl font-bold mb-4 text-blue-700">4. Estructura</h2>
                    <ol class="list-decimal list-inside space-y-2 text-gray-700">
                        <li>**Título y Portada:** Identificación del informe y autores.</li>
                        <li>**Índice:** Listado de secciones y páginas.</li>
                        <li>**Resumen Ejecutivo:** Un vistazo rápido a las conclusiones.</li>
                        <li>**Introducción:** Contexto y objetivos.</li>
                        <li>**Metodología:** Cómo se realizó la investigación.</li>
                        <li>**Resultados:** Presentación de los hallazgos.</li>
                        <li>**Conclusiones y Recomendaciones:** Cierre del informe.</li>
                        <li>**Bibliografía y Anexos:** Fuentes y material de apoyo.</li>
                    </ol>
                </div>
            </section>

            <!-- Interactivo: Herramientas -->
            <section id="interactivo" class="section">
                <div class="card p-6">
                    <h2 class="text-2xl font-bold mb-4 text-blue-700">5. Herramientas para hacer un informe técnico</h2>
                    <p class="text-gray-700 mb-4">
                        A continuación, algunas herramientas útiles para la creación de informes técnicos:
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                        <!-- Card: Microsoft Word -->
                        <div class="bg-gray-50 p-4 rounded-lg shadow-sm text-center">
                            <h3 class="font-semibold text-xl text-gray-800">Microsoft Word</h3>
                            <p class="text-gray-600 mt-2 text-sm">Ideal para documentos con formato avanzado, tablas e índices automáticos.</p>
                        </div>
                        <!-- Card: Google Docs -->
                        <div class="bg-gray-50 p-4 rounded-lg shadow-sm text-center">
                            <h3 class="font-semibold text-xl text-gray-800">Google Docs</h3>
                            <p class="text-gray-600 mt-2 text-sm">Excelente para la colaboración en tiempo real y accesibilidad desde cualquier lugar.</p>
                        </div>
                        <!-- Card: LaTeX -->
                        <div class="bg-gray-50 p-4 rounded-lg shadow-sm text-center">
                            <h3 class="font-semibold text-xl text-gray-800">LaTeX</h3>
                            <p class="text-gray-600 mt-2 text-sm">Utilizado en entornos académicos y científicos para una maquetación profesional y fórmulas.</p>
                        </div>
                        <!-- Card: Lucidchart -->
                        <div class="bg-gray-50 p-4 rounded-lg shadow-sm text-center">
                            <h3 class="font-semibold text-xl text-gray-800">Lucidchart</h3>
                            <p class="text-gray-600 mt-2 text-sm">Herramienta para crear diagramas de flujo, gráficos y otros elementos visuales complejos.</p>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <!-- Footer -->
        <footer class="mt-10 text-center text-gray-500 text-sm">
            <p>
                Exposición por: Miguel Collazos, Juan Erazo, Julián Jaramillo
            </p>
        </footer>
    </div>

    <script>
        // JavaScript to handle section visibility and active navigation link
        function showSection(sectionId) {
            // Hide all sections
            const sections = document.querySelectorAll('.section');
            sections.forEach(section => {
                section.classList.remove('active');
            });

            // Deactivate all navigation links
            const navLinks = document.querySelectorAll('.nav-link');
            navLinks.forEach(link => {
                link.classList.remove('active');
            });

            // Show the selected section
            const targetSection = document.getElementById(sectionId);
            if (targetSection) {
                targetSection.classList.add('active');
            }

            // Activate the corresponding navigation link
            const targetLink = document.querySelector(`a[href="#${sectionId}"]`);
            if (targetLink) {
                targetLink.classList.add('active');
            }
        }

        // Initially show the first section and activate its link
        document.addEventListener('DOMContentLoaded', () => {
            showSection('intro');
        });
    </script>

</body>
</html>
