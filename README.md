<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Institución Educativa Manuela Beltrán</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/heroicons/2.0.16/24/outline/academic-cap.svg" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .slide {
            transition: opacity 1s ease-in-out;
        }
        /* Animación para el gradiente del título */
        @keyframes gradient-animation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        .animate-gradient {
            background-size: 200% 200%;
            animation: gradient-animation 6s ease infinite;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Encabezado y Navegación -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <svg class="h-10 w-10 text-blue-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 017.843 4.582M12 3a8.997 8.997 0 00-7.843 4.582m15.686 0A11.953 11.953 0 0112 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0121 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0112 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 013 12c0-1.605.42-3.113 1.157-4.418" />
                </svg>
                <h1 class="text-lg md:text-xl font-bold text-gray-700 hidden sm:block">I.E. Manuela Beltrán</h1>
            </div>
            <div class="flex items-center space-x-4">
                <a href="#" class="px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition duration-300 text-sm font-medium">Iniciar Sesión</a>
            </div>
        </nav>
    </header>

    <!-- Contenido Principal -->
    <main class="container mx-auto px-6 py-8">

        <!-- Título principal -->
        <div class="text-center mb-10">
            <h2 class="text-3xl md:text-4xl font-extrabold bg-gradient-to-r from-blue-700 via-teal-500 to-blue-700 text-transparent bg-clip-text animate-gradient">INSTITUCIÓN EDUCATIVA MANUELA BELTRÁN</h2>
            <p class="text-gray-600 mt-2">DISTRITO DE CARTAGENA DE INDIAS</p>
        </div>
        
        <!-- Slider de Mensajes Motivacionales -->
        <div id="slider" class="relative max-w-4xl mx-auto h-40 bg-blue-800 text-white rounded-xl shadow-2xl flex items-center justify-center overflow-hidden mb-12">
            <div class="slide absolute w-full text-center px-4 opacity-0">
                <p class="text-xl md:text-2xl font-semibold">"La educación es el arma más poderosa que puedes usar para cambiar el mundo."</p>
                <span class="text-sm text-blue-200 mt-2 block">- Nelson Mandela</span>
            </div>
            <div class="slide absolute w-full text-center px-4 opacity-0">
                <p class="text-xl md:text-2xl font-semibold">"El aprendizaje nunca agota la mente."</p>
                <span class="text-sm text-blue-200 mt-2 block">- Leonardo da Vinci</span>
            </div>
            <div class="slide absolute w-full text-center px-4 opacity-0">
                <p class="text-xl md:text-2xl font-semibold">"El único lugar donde el éxito viene antes que el trabajo es en el diccionario."</p>
                <span class="text-sm text-blue-200 mt-2 block">- Vidal Sassoon</span>
            </div>
             <div class="slide absolute w-full text-center px-4 opacity-0">
                <p class="text-xl md:text-2xl font-semibold">"Invierte en tu mente y tu mente llenará tus bolsillos."</p>
                <span class="text-sm text-blue-200 mt-2 block">- Benjamin Franklin</span>
            </div>
        </div>

        <!-- Motor de Búsqueda -->
        <div class="max-w-2xl mx-auto mb-12">
            <div class="relative">
                <input type="search" placeholder="Buscar un recurso, materia o tema..." class="w-full p-4 pl-12 rounded-full border-2 border-gray-300 focus:outline-none focus:border-blue-500 transition duration-300">
                <div class="absolute top-0 left-0 inline-flex items-center justify-center h-full w-12 text-gray-400">
                    <svg class="h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor">
                        <path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                    </svg>
                </div>
            </div>
        </div>
        
        <!-- Botones de Enlaces Externos -->
        <div class="flex flex-col sm:flex-row justify-center items-center gap-6 mb-16">
            <a href="https://www.youtube.com" target="_blank" class="flex items-center justify-center gap-3 w-64 px-6 py-3 bg-red-600 text-white font-bold rounded-lg shadow-lg hover:bg-red-700 transform hover:scale-105 transition-all duration-300">
                <svg class="h-7 w-7" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0C.887 3.433 0 4.949 0 8.714v6.572c0 3.766.887 5.282 4.385 5.531 3.6.245 11.626.246 15.23 0 3.498-.249 4.385-1.765 4.385-5.531V8.714c0-3.765-.887-5.281-4.385-5.53zM9.5 15.568V8.432L15.5 12 9.5 15.568z"/>
                </svg>
                <span>Canal de YouTube</span>
            </a>
            <a href="https://classroom.google.com" target="_blank" class="flex items-center justify-center gap-3 w-64 px-6 py-3 bg-green-600 text-white font-bold rounded-lg shadow-lg hover:bg-green-700 transform hover:scale-105 transition-all duration-300">
                 <svg class="h-7 w-7" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                   <path d="M22 5.72l-10-4.44L2 5.72v4.86c0 5.17 3.46 9.87 8.31 11.53.51.18 1.05.28 1.6.28s1.09-.1 1.6-.28C18.54 20.45 22 15.75 22 10.58V5.72zM12 12.32L4 8.23v-1.2l8 3.56 8-3.56v1.2l-8 4.09zM12 14.09l8-4.09v1.58c0 3.96-2.69 7.48-6.31 8.86-.39.14-.81.21-1.25.21-.44 0-.86-.07-1.25-.21C7.69 19.56 5 16.04 5 12.08v-1.58l7 3.59z"/>
                 </svg>
                <span>Google Classroom</span>
            </a>
        </div>

        <!-- Sección de Áreas -->
        <div>
            <h3 class="text-2xl font-semibold text-center text-gray-700 mb-8">Nuestras Áreas de Estudio</h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
                
                <!-- Tarjeta de Ciencias Naturales -->
                <a href="#" class="bg-white rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300 group flex flex-col">
                    <div class="p-6 flex-grow">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-green-100 text-green-600 mb-4 mx-auto">
                           <svg class="h-8 w-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M14.25 10.5a4.5 4.5 0 00-8.25-2.124M14.25 10.5a4.5 4.5 0 01-8.25 2.124M14.25 10.5a4.5 4.5 0 005.64-6.444M14.25 10.5a4.5 4.5 0 015.64 6.444M6 18.75a3 3 0 006 0M6 18.75a3 3 0 016 0m-6 0H3.375c-.621 0-1.125-.504-1.125-1.125V11.25c0-.621.504-1.125 1.125-1.125h3.75z" />
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center text-gray-800">Ciencias Naturales</h4>
                        <p class="text-gray-600 text-center mt-2 text-sm">Explora el mundo de la física, la química y los fenómenos naturales.</p>
                        <p class="text-xs italic text-gray-500 text-center mt-3">"Mira profundamente en la naturaleza y comprenderás todo mejor."</p>
                    </div>
                </a>

                <!-- Tarjeta de Biología -->
                <a href="#" class="bg-white rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300 group flex flex-col">
                    <div class="p-6 flex-grow">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-teal-100 text-teal-600 mb-4 mx-auto">
                            <svg class="h-8 w-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                               <path stroke-linecap="round" stroke-linejoin="round" d="M7.5 14.25v2.25m3-4.5v4.5m3-6.75v6.75m3-9v9M6 20.25h12A2.25 2.25 0 0020.25 18V6A2.25 2.25 0 0018 3.75H6A2.25 2.25 0 003.75 6v12A2.25 2.25 0 006 20.25z" />
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center text-gray-800">Biología</h4>
                        <p class="text-gray-600 text-center mt-2 text-sm">Descubre los secretos de los seres vivos, desde la célula hasta los ecosistemas.</p>
                        <p class="text-xs italic text-gray-500 text-center mt-3">"La vida es el mayor experimento de la naturaleza."</p>
                    </div>
                </a>

                <!-- Tarjeta de Matemáticas -->
                <a href="#" class="bg-white rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300 group flex flex-col">
                    <div class="p-6 flex-grow">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-purple-100 text-purple-600 mb-4 mx-auto">
                            <svg class="h-8 w-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75l3 3m0 0l3-3m-3 3v-7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center text-gray-800">Matemáticas</h4>
                        <p class="text-gray-600 text-center mt-2 text-sm">Domina los números, el álgebra, la geometría y el cálculo.</p>
                        <p class="text-xs italic text-gray-500 text-center mt-3">"Las matemáticas son el alfabeto con el que Dios ha escrito el universo."</p>
                    </div>
                </a>

                <!-- Tarjeta de Sociales -->
                <a href="#" class="bg-white rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300 group flex flex-col">
                    <div class="p-6 flex-grow">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-yellow-100 text-yellow-600 mb-4 mx-auto">
                            <svg class="h-8 w-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M12 21v-8.25M15.75 21v-8.25M8.25 21v-8.25M3 9l9-6 9 6m-1.5 12V10.332A48.36 48.36 0 0012 9.75c-2.551 0-5.056.2-7.5.582V21M3 21h18M12 6.75h.008v.008H12V6.75z" />
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center text-gray-800">Ciencias Sociales</h4>
                        <p class="text-gray-600 text-center mt-2 text-sm">Analiza la historia, la geografía y las estructuras de nuestra sociedad.</p>
                        <p class="text-xs italic text-gray-500 text-center mt-3">"Un pueblo que no conoce su historia está condenado a repetirla."</p>
                    </div>
                </a>
                
                <!-- Tarjeta de Tecnologia -->
                <a href="#" class="bg-white rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300 group flex flex-col">
                    <div class="p-6 flex-grow">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-blue-100 text-blue-600 mb-4 mx-auto">
                           <svg class="h-8 w-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                               <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 7.5l3 2.25-3 2.25m4.5 0h3m-9 8.25h13.5A2.25 2.25 0 0021 18V6a2.25 2.25 0 00-2.25-2.25H5.25A2.25 2.25 0 003 6v12a2.25 2.25 0 002.25 2.25z" />
                           </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center text-gray-800">Tecnología</h4>
                        <p class="text-gray-600 text-center mt-2 text-sm">Crea, innova y resuelve problemas con las herramientas del futuro.</p>
                        <p class="text-xs italic text-gray-500 text-center mt-3">"La tecnología es mejor cuando une a las personas."</p>
                    </div>
                </a>

                <!-- Tarjeta de Lenguaje -->
                <a href="#" class="bg-white rounded-lg shadow-lg overflow-hidden transform hover:-translate-y-2 transition-transform duration-300 group flex flex-col">
                    <div class="p-6 flex-grow">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-orange-100 text-orange-600 mb-4 mx-auto">
                            <svg class="h-8 w-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25" />
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center text-gray-800">Lenguaje</h4>
                        <p class="text-gray-600 text-center mt-2 text-sm">Domina el poder de las palabras, la comunicación y la literatura.</p>
                        <p class="text-xs italic text-gray-500 text-center mt-3">"El lenguaje es el mapa de una cultura."</p>
                    </div>
                </a>

            </div>
        </div>
    </main>

    <!-- Pie de Página -->
    <footer class="bg-gray-800 text-white mt-12">
        <div class="container mx-auto px-6 py-8">
            <div class="text-center">
                <h4 class="text-xl font-semibold mb-4">Contáctanos</h4>
                <p class="mb-2">Si tienes dudas o necesitas soporte, no dudes en comunicarte.</p>
                <div class="flex flex-col sm:flex-row justify-center items-center sm:space-x-6 space-y-2 sm:space-y-0 mt-4">
                    <div class="flex items-center space-x-2">
                        <svg class="h-5 w-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                          <path d="M2.5 3A1.5 1.5 0 001 4.5v.793c.026.009.051.02.076.032L7.674 8.51c.206.1.446.1.652 0l6.598-3.185A.755.755 0 0115 5.293V4.5A1.5 1.5 0 0013.5 3h-11z" />
                          <path d="M15 6.954L8.978 9.86a2.25 2.25 0 01-1.956 0L1 6.954V15.5A1.5 1.5 0 002.5 17h11a1.5 1.5 0 001.5-1.5V6.954z" />
                        </svg>
                        <span>correo@institucion.edu.co</span>
                    </div>
                    <div class="flex items-center space-x-2">
                        <svg class="h-5 w-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                          <path fill-rule="evenodd" d="M2 3.5A1.5 1.5 0 013.5 2h1.148a1.5 1.5 0 011.465 1.175l.716 3.223a1.5 1.5 0 01-1.052 1.767l-.933.267c-.41.117-.643.555-.48.95a11.542 11.542 0 006.254 6.254c.395.163.833-.07.95-.48l.267-.933a1.5 1.5 0 011.767-1.052l3.223.716A1.5 1.5 0 0118 15.352V16.5a1.5 1.5 0 01-1.5 1.5h-1.528a13.5 13.5 0 01-12.7-12.7V3.5z" clip-rule="evenodd" />
                        </svg>
                        <span>(605) 123-4567</span>
                    </div>
                </div>
                <p class="text-sm text-gray-400 mt-8">&copy; 2025 Institución Educativa Manuela Beltrán. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>
    
    <script>
        // Lógica para el slider de mensajes motivacionales
        const slides = document.querySelectorAll('#slider .slide');
        let currentSlide = 0;

        function showSlide(index) {
            slides.forEach((slide, i) => {
                slide.style.opacity = i === index ? '1' : '0';
            });
        }

        function nextSlide() {
            currentSlide = (currentSlide + 1) % slides.length;
            showSlide(currentSlide);
        }

        // Mostrar la primera diapositiva inmediatamente
        showSlide(currentSlide);

        // Cambiar de diapositiva cada 5 segundos
        setInterval(nextSlide, 5000);
    </script>

</body>
</html>

