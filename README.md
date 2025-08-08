# el-mundo-verde
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mundo Verde - Conectando con la Naturaleza</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #2e8b57;
            --secondary-color: #3cb371;
            --dark-green: #1e5631;
            --light-green: #a4de9e;
            --cream: #f8f9fa;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            color: #333;
            background-color: var(--cream);
        }
        
        h1, h2, h3, h4 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            color: var(--dark-green);
        }
        
        .navbar {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .navbar-brand {
            font-weight: 700;
            color: var(--dark-green) !important;
        }
        
        .nav-link {
            color: var(--dark-green) !important;
            font-weight: 500;
        }
        
        .hero-section {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1476231682828-37e571bc172f?ixlib=rb-4.0.3');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 150px 0;
            text-align: center;
        }
        
        .btn-primary {
            background-color: var(--primary-color);
            border-color: var(--primary-color);
        }
        
        .btn-primary:hover {
            background-color: var(--dark-green);
            border-color: var(--dark-green);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }
        
        .card {
            border: none;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .card:hover {
            transform: translateY(-10px);
        }
        
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }
        
        .testimonial-card {
            background-color: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .testimonial-img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid var(--light-green);
        }
        
        .newsletter-section {
            background-color: var(--light-green);
            padding: 60px 0;
        }
        
        footer {
            background-color: var(--dark-green);
            color: white;
        }
        
        .social-icon {
            color: white;
            font-size: 1.5rem;
            margin-right: 15px;
            transition: color 0.3s;
        }
        
        .social-icon:hover {
            color: var(--light-green);
        }
        
        .animate-on-scroll {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.6s ease-out;
        }
        
        .animate-on-scroll.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>


<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-leaf me-2"></i>Mundo Verde
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#inicio">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#nosotros">Nosotros</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#servicios">Servicios</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#blog">Blog</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contacto">Contacto</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="hero-section">
        <div class="container animate-on-scroll">
            <h1 class="display-3 fw-bold mb-4">Conecta con la Naturaleza</h1>
            <p class="lead mb-5">Descubre el poder transformador del mundo natural y aprende cómo proteger nuestro planeta para las futuras generaciones.</p>
            <a href="#servicios" class="btn btn-primary btn-lg px-4 me-2">Explorar</a>
            <a href="#contacto" class="btn btn-outline-light btn-lg px-4">Contacto</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="nosotros" class="py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6 mb-4 mb-lg-0 animate-on-scroll">
                    <h2 class="mb-4">Nuestra Misión</h2>
                    <p class="lead">Promovemos un estilo de vida sostenible en armonía con la naturaleza.</p>
                    <p>En Mundo Verde creemos que cada acción cuenta. Desde 2010, trabajamos para educar, inspirar y empoderar a las personas para que tomen decisiones más ecológicas en su vida diaria.</p>
                    <p>Nuestro equipo de expertos en ecología, biólogos y activistas ambientales está comprometido con la protección de los ecosistemas y la biodiversidad del planeta.</p>
                    <a href="#" class="btn btn-primary mt-3">Conoce más</a>
                </div>
                <div class="col-lg-6 animate-on-scroll">
        
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5 animate-on-scroll">
                <h2>¿Por qué unirte a Mundo Verde?</h2>
                <p class="lead">Descubre los beneficios de conectar con la naturaleza</p>
            </div>
            <div class="row g-4">
                <div class="col-md-4 animate-on-scroll">
                    <div class="text-center p-4">
                        <div class="feature-icon">
                            <i class="fas fa-heart"></i>
                        </div>
                        <h4>Salud Mental</h4>
                        <p>El contacto con la naturaleza reduce el estrés, la ansiedad y mejora el estado de ánimo.</p>
                    </div>
                </div>
                <div class="col-md-4 animate-on-scroll">
                    <div class="text-center p-4">
                        <div class="feature-icon">
                            <i class="fas fa-lungs"></i>
                        </div>
                        <h4>Aire Puro</h4>
                        <p>Los espacios verdes mejoran la calidad del aire que respiramos, esencial para nuestra salud.</p>
                    </div>
                </div>
                <div class="col-md-4 animate-on-scroll">
                    <div class="text-center p-4">
                        <div class="feature-icon">
                            <i class="fas fa-globe-americas"></i>
                        </div>
                        <h4>Sostenibilidad</h4>
                        <p>Aprendemos a vivir de manera sostenible, reduciendo nuestro impacto en el planeta.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

  <!-- Services Section -->
<section id="servicios" class="py-5">
    <div class="container">
        <div class="text-center mb-5 animate-on-scroll">
            <h2>Nuestros Servicios</h2>
            <p class="lead">Ofrecemos soluciones para una vida más saludable</p>
        </div>
        <div class="row g-4">
            <div class="col-md-4 animate-on-scroll">
                <div class="card h-100">
                    <img src="https://thumbs.dreamstime.com/b/huertos-de-granja-campo-paisaje-ganadero-cultivo-hortalizas-primer-plano-con-ganado-vacuno-en-la-parte-superior-del-rural-colina-244810671.jpg" class="card-img-top" alt="Huertos urbanos">
                    <div class="card-body">
                        <h5 class="card-title">Huertos Rurales</h5>
                        <p class="card-text">Aprende a cultivar tus propios alimentos en casa. Cultívalos a tu manera y descubre los cuidados necesarios para tus plantas.</p>
                        <a href="https://steven17leiva15.github.io/huertos-rurales/" class="btn btn-outline-success">Más información</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4 animate-on-scroll">
                <div class="card h-100">
                    <img src="https://img.hogar.mapfre.es/wp-content/uploads/2020/01/06-jardines-urbanos.jpg" class="card-img-top" alt="Jardines urbanos">
                    <div class="card-body">
                        <h5 class="card-title">Jardines</h5>
                        <p class="card-text">Conoce diferentes tipos de jardines, incluyendo jardines florales, aromáticos y decorativos.</p>
                        <a href="jardines.html" class="btn btn-outline-success">Más información</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4 animate-on-scroll">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1585320806297-9794b3e4eeae" class="card-img-top" alt="Educación ambiental">
                    <div class="card-body">
                        <h5 class="card-title">Educación Ambiental</h5>
                        <p class="card-text">Programas educativos para escuelas y empresas sobre sostenibilidad y conservación del medio ambiente.</p>
                        <a href="educación-ambiental.html" class="btn btn-outline-success">Más información</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

    <!-- Stats Section -->
    <section class="py-5 bg-primary text-white">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-3 mb-4 mb-md-0 animate-on-scroll">
                    <h3 class="display-4 fw-bold">10+</h3>
                    <p>Años de experiencia</p>
                </div>
                <div class="col-md-3 mb-4 mb-md-0 animate-on-scroll">
                    <h3 class="display-4 fw-bold">500+</h3>
                    <p>Proyectos completados</p>
                </div>
                <div class="col-md-3 mb-4 mb-md-0 animate-on-scroll">
                    <h3 class="display-4 fw-bold">10K+</h3>
                    <p>Personas impactadas</p>
                </div>
                <div class="col-md-3 animate-on-scroll">
                    <h3 class="display-4 fw-bold">50+</h3>
                    <p>Especies protegidas</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5 animate-on-scroll">
                <h2>Últimas Noticias</h2>
                <p class="lead">Mantente informado sobre ecología y sostenibilidad</p>
            </div>
            <div class="row g-4">
                <div class="col-lg-4 col-md-6 animate-on-scroll">
                    <div class="card h-100">
                        <img src="https://img.freepik.com/fotos-premium/pequenos-arboles-que-crecen-lampara-ahorro-energia-iconos-relacionados-energia_104677-776.jpg" class="card-img-top" alt="Reforestación">
                        <div class="card-body">
                            <span class="badge bg-success mb-2">Reforestación</span>
                            <h5 class="card-title">Siembra de árboles</h5>
                            <p class="card-text">sembrar árboles en zonas que son propensas a incendios; la reforestación ayuda a prevenir la eroción del suelo y proteje las fuentes de agua. </p>
                        </div>
                        <div class="card-footer bg-transparent">
                            <a href="siembra-árboles.html" class="btn btn-sm btn-primary">Leer más</a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 animate-on-scroll">
                    <div class="card h-100">
                        <img src="https://www.seslatam.com/wp-content/uploads/foto-blog-rensus-01-1200-0600.jpg" class="card-img-top" alt="Energías renovables">
                        <div class="card-body">
                            <span class="badge bg-success mb-2">Energía</span>
                            <h5 class="card-title">Cómo Reducir tu Huella de Carbono en Casa</h5>
                            <p class="card-text">Guía práctica con 10 consejos sencillos para hacer tu hogar más eficiente energéticamente.</p>
                        </div>
                        <div class="card-footer bg-transparent">
                            <a href="energía.html" class="btn btn-sm btn-primary">Leer más</a>
                        </div>
                    </div><bg></bg>
                </div>
                <div class="col-lg-4 col-md-6 animate-on-scroll">
                    <div class="card h-100">
                        <img src="https://miro.medium.com/v2/resize:fit:640/1*4WxR2H3sAvSh3erBvLcNKg.jpeg" class="card-img-top" alt="Biodiversidad">
                        <div class="card-body">
                            <span class="badge bg-success mb-2">Biodiversidad</span>
                            <h5 class="card-title">Descubre la Naturaleza</h5>
                            <p class="card-text">Científicos identifican una nueva especie mientras estudian los efectos del cambio climático.</p>
                        </div>
                        <div class="card-footer bg-transparent">
                            <a href="biodiversidad.html" class="btn btn-sm btn-primary">Leer más</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-4 animate-on-scroll">
                <a href="#" class="btn btn-primary">Ver más artículos</a>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-5">
        <div class="container">
            <div class="text-center mb-5 animate-on-scroll">
                <h2>Lo que dicen nuestros participantes</h2>
                <p class="lead">Experiencias transformadoras con la naturaleza</p>
            </div>
            <div class="row g-4">
                <div class="col-md-4 animate-on-scroll">
                    <div class="testimonial-card h-100">
                        <div class="text-center mb-3">
                            <img src="https://randomuser.me/api/portraits/women/32.jpg" class="testimonial-img" alt="Testimonio 1">
                        </div>
                        <p class="text-center mb-4">"Los talleres de Mundo Verde cambiaron mi perspectiva sobre el consumo. Ahora tengo mi propio huerto en casa y reduzco mi basura significativamente."</p>
                        <h5 class="text-center mb-1">María González</h5>
                        <p class="text-center text-muted">Profesora, 42 años</p>
                    </div>
                </div>
                <div class="col-md-4 animate-on-scroll">
                    <div class="testimonial-card h-100">
                        <div class="text-center mb-3">
                            <img src="https://randomuser.me/api/portraits/men/75.jpg" class="testimonial-img" alt="Testimonio 2">
                        </div>
                        <p class="text-center mb-4">"Las excursiones de ecoturismo son increíbles. He aprendido más sobre nuestra biodiversidad en un mes que en toda mi vida. ¡Altamente recomendado!"</p>
                        <h5 class="text-center mb-1">Carlos Martínez</h5>
                        <p class="text-center text-muted">Ingeniero, 35 años</p>
                    </div>
                </div>
                <div class="col-md-4 animate-on-scroll">
                    <div class="testimonial-card h-100">
                        <div class="text-center mb-3">
                            <img src="https://randomuser.me/api/portraits/women/68.jpg" class="testimonial-img" alt="Testimonio 3">
                        </div>
                        <p class="text-center mb-4">"Llevé a mis estudiantes al programa educativo y fue transformador. Ahora son pequeños defensores del medio ambiente en sus comunidades."</p>
                        <h5 class="text-center mb-1">Laura Sánchez</h5>
                        <p class="text-center text-muted">Directora escolar, 45 años</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="newsletter-section">
        <div class="container">
            <div class="row justify-content-center animate-on-scroll">
                <div class="col-lg-8 text-center">
                    <h2 class="mb-4">Únete a Nuestra Comunidad Verde</h2>
                    <p class="mb-5">Suscríbete a nuestro boletín mensual y recibe consejos ecológicos, noticias ambientales y promociones exclusivas.</p>
                    <form class="row g-2 justify-content-center">
                        <div class="col-md-8">
                            <input type="email" class="form-control form-control-lg" placeholder="Tu correo electrónico">
                        </div>
                        <div class="col-md-4">
                            <button type="submit" class="btn btn-dark btn-lg w-100">Suscribirme</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 mb-5 mb-lg-0 animate-on-scroll">
                    <h2 class="mb-4">Contáctanos</h2>
                    <p class="mb-5">¿Tienes preguntas o quieres colaborar con nosotros? Estamos aquí para ayudarte.</p>
                    <div class="mb-4">
                        <h5><i class="fas fa-map-marker-alt me-2 text-primary"></i> Dirección</h5>
                        <p>Calle Ecológica 123, Bosque Urbano, Ciudad Verde</p>
                    </div>
                    <div class="mb-4">
                        <h5><i class="fas fa-phone me-2 text-primary"></i> Teléfono</h5>
                        <p>+1 234 567 890</p>
                    </div>
                    <div class="mb-4">
                        <h5><i class="fas fa-envelope me-2 text-primary"></i> Email</h5>
                        <p>info@mundoverde.org</p>
                    </div>
                </div>
                <div class="col-lg-6 animate-on-scroll">
                    <div class="card shadow">
                        <div class="card-body p-5">
                            <h4 class="mb-4">Envía un mensaje</h4>
                            <form>
                                <div class="mb-3">
                                    <input type="text" class="form-control" placeholder="Nombre completo">
                                </div>
                                <div class="mb-3">
                                    <input type="email" class="form-control" placeholder="Correo electrónico">
                                </div>
                                <div class="mb-3">
                                    <input type="text" class="form-control" placeholder="Asunto">
                                </div>
                                <div class="mb-3">
                                    <textarea class="form-control" rows="5" placeholder="Mensaje"></textarea>
                                </div>
                                <button type="submit" class="btn btn-primary w-100">Enviar mensaje</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Map Section -->
    <div class="animate-on-scroll">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3022.215256027068!2d-73.9878449241642!3d40.74844097138977!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c259a9b3117469%3A0xd134e199a405a163!2sEmpire%20State%20Building!5e0!3m2!1sen!2sus!4v1689876543210!5m2!1sen!2sus" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

    <!-- Footer -->
    <footer class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-4 mb-4 mb-lg-0 animate-on-scroll">
                    <h4 class="text-white mb-4"><i class="fas fa-leaf me-2"></i>Mundo Verde</h4>
                    <p>Promoviendo un estilo de vida sostenible y en armonía con la naturaleza desde 2010.</p>
                    <div class="mt-4">
                        <a href="#" class="social-icon"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="social-icon"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="social-icon"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                <div class="col-lg-2 col-md-6 mb-4 mb-md-0 animate-on-scroll">
                    <h5 class="text-white mb-4">Enlaces</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="#inicio" class="text-white text-decoration-none">Inicio</a></li>
                        <li class="mb-2"><a href="#nosotros" class="text-white text-decoration-none">Nosotros</a></li>
                        <li class="mb-2"><a href="#servicios" class="text-white text-decoration-none">Servicios</a></li>
                        <li class="mb-2"><a href="#blog" class="text-white text-decoration-none">Blog</a></li>
                        <li><a href="#contacto" class="text-white text-decoration-none">Contacto</a></li>
                    </ul>
                </div>
                <div class="col-lg-2 col-md-6 mb-4 mb-md-0 animate-on-scroll">
                    <h5 class="text-white mb-4">Servicios</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="#" class="text-white text-decoration-none">Huertos Urbanos</a></li>
                        <li class="mb-2"><a href="#" class="text-white text-decoration-none">Ecoturismo</a></li>
                        <li class="mb-2"><a href="#" class="text-white text-decoration-none">Educación Ambiental</a></li>
                        <li class="mb-2"><a href="#" class="text-white text-decoration-none">Consultoría Verde</a></li>
                        <li><a href="#" class="text-white text-decoration-none">Voluntariado</a></li>
                    </ul>
                </div>
                <div class="col-lg-4 animate-on-scroll">
                    <h5 class="text-white mb-4">Horario</h5>
                    <ul class="list-unstyled text-white">
                        <li class="mb-2">Lunes - Viernes: 9:00 - 18:00</li>
                        <li class="mb-2">Sábado: 10:00 - 15:00</li>
                        <li>Domingo: Cerrado</li>
                    </ul>
                    <div class="mt-4">
                        <a href="#" class="btn btn-outline-light">Haz una donación</a>
                    </div>
                </div>
            </div>
            <hr class="my-4 bg-light">
            <div class="row">
                <div class="col-md-6 text-center text-md-start animate-on-scroll">
                    <p class="mb-0">&copy; 2023 Mundo Verde. Todos los derechos reservados.</p>
                </div>
                <div class="col-md-6 text-center text-md-end animate-on-scroll">
                    <a href="#" class="text-white text-decoration-none me-3">Política de privacidad</a>
                    <a href="#" class="text-white text-decoration-none">Términos de servicio</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <!-- Custom JS -->




    <script>
        // Animación al hacer scroll
        document.addEventListener('DOMContentLoaded', function() {
            const animateElements = document.querySelectorAll('.animate-on-scroll');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, {
                threshold: 0.1
            });
            
            animateElements.forEach(element => {
                observer.observe(element);
            });
            
            // Smooth scrolling para enlaces internos
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    const targetElement = document.querySelector(targetId);
                    
                    if (targetElement) {
                        window.scrollTo({
                            top: targetElement.offsetTop - 70,
                            behavior: 'smooth'
                        });
                    }
                });
            });
        });
    </script>
</body>
</html>
