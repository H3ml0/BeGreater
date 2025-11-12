<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BeGreater - Строй свое тело сильным</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <div class="logo">BeGreater</div>
            <div class="name-board">Спортивный фестиваль 2025</div>
            
            <div class="nav-buttons">
                <button class="nav-btn" onclick="scrollToSection('about')">О НАС</button>
                <button class="nav-btn" onclick="scrollToSection('info')">ИНФО</button>
                <button class="nav-btn" onclick="scrollToSection('activate')">АКТИВИРУЙ ПОТЕНЦИАЛ</button>
                <button class="nav-btn" onclick="scrollToSection('programs')">ПРОГРАММЫ</button>
            </div>
            
            <button class="cta-button" onclick="scrollToSection('programs')">Начать сейчас</button>
        </div>
    </header>
    
    <!-- About Section -->
    <section id="about" class="content-section">
        <div class="container">
            <h2 class="section-title">КТО МЫ</h2>
            <div class="section-content">
                <div class="section-text">
                    <p>BeGreater - это сообщество профессиональных спортсменов и тренеров, объединенных общей целью: помочь каждому раскрыть свой потенциал и достичь максимальных результатов в спорте.</p>
                    <p>Мы создаем уникальные тренировочные программы, организуем спортивные мероприятия и предоставляем доступ к лучшему оборудованию и экспертам в области фитнеса.</p>
                    <p>Наша миссия - вдохновлять людей на здоровый образ жизни и помогать им становиться сильнее как физически, так и ментально.</p>
                    <button class="cta-button" onclick="scrollToSection('programs')">Присоединиться</button>
                </div>
                <div class="section-image">
                    <img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80 " alt="О нас">
                </div>
            </div>
        </div>
    </section>
    
    <div class="divider"></div>
    
    <!-- Info Section -->
    <section id="info" class="content-section">
        <div class="container">
            <h2 class="section-title">ИНФОРМАЦИЯ</h2>
            <div class="section-content">
                <div class="section-image">
                    <img src="https://images.unsplash.com/photo-1536922246289-88c42f957773?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80 " alt="Информация">
                </div>
                <div class="section-text">
                    <p>Мы предоставляем полную информацию о наших программах, тренерах и мероприятиях. У нас вы найдете все необходимое для достижения ваших спортивных целей.</p>
                    <p>Наши залы оборудованы современными тренажерами, а тренеры имеют международные сертификаты и многолетний опыт работы.</p>
                    <p>Мы регулярно проводим мастер-классы, семинары и соревнования для наших участников. Присоединяйтесь к нашему сообществу и откройте для себя мир возможностей!</p>
                    <button class="cta-button" onclick="scrollToSection('contact')">Узнать больше</button>
                </div>
            </div>
        </div>
    </section>
    
    <div class="divider"></div>
    
    <!-- Activate Potential Section -->
    <section id="activate" class="content-section">
        <div class="container">
            <h2 class="section-title">АКТИВИРУЙ СВОЙ ПОТЕНЦИАЛ</h2>
            <div class="section-content">
                <div class="section-text">
                    <p>Раскрой свои скрытые возможности и достигни новых высот в спорте вместе с нами!</p>
                    <p>Присоединяйтесь к нашему Telegram-каналу, где мы делимся эксклюзивными материалами, анонсами мероприятий и полезными советами по тренировкам и питанию.</p>
                    <p>В нашем канале вы найдете:</p>
                    <ul style="color: #b0b0b0; margin-left: 20px; margin-bottom: 20px;">
                        <li>Ежедневные тренировочные программы</li>
                        <li>Советы по питанию и восстановлению</li>
                        <li>Анонсы мероприятий и мастер-классов</li>
                        <li>Эксклюзивные интервью с чемпионами</li>
                        <li>Мотивационные материалы и истории успеха</li>
                    </ul>
                    <button class="cta-button">Присоединиться к Telegram-каналу</button>
                </div>
                <div class="section-image">
                    <img src="https://images.unsplash.com/photo-1534367507877-0edd93bd013b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80 " alt="Активируй потенциал">
                </div>
            </div>
        </div>
    </section>
    
    <div class="divider"></div>
    
    <!-- Video Section -->
    <section id="programs" class="video-section">
        <div class="container">
            <h2 class="section-title">ПРОФЕССИОНАЛЬНЫЕ ПРОГРАММЫ</h2>
            <div class="video-container">
                <div class="video-wrapper">
                    <iframe src="https://www.youtube.com/embed/Q3CEPgWyCuk " allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <div class="video-description">
                    <h3 class="video-title">Обзор тренировочной программы</h3>
                    <p class="video-text">В этом видео мы демонстрируем профессиональную программу тренировок, разработанную нашими экспертами. Программа включает в себя силовые упражнения, кардио-нагрузки и функциональный тренинг для достижения максимальных результатов.</p>
                    <p class="video-text">Программа подходит как для начинающих, так и для опытных спортсменов. Каждое упражнение подробно объясняется и демонстрируется с правильной техникой выполнения.</p>
                    <button class="cta-button">Начать программу</button>
                </div>
            </div>
        </div>
    </section>
    
    <div class="divider"></div>
    
    <!-- Diamond Section -->
    <section class="diamond-section">
        <h2 class="section-title">НАШИ ЧЕМПИОНЫ</h2>
        <div class="diamond-container">
            <div class="diamond-item">
                <div class="diamond-content">
                    <img src="https://images.unsplash.com/photo-1548690312-e3b507d8c110?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80 " alt="Спортсмен 1" class="diamond-image">
                    <div class="diamond-title">Алексей Иванов</div>
                    <div class="diamond-text">Чемпион мира по пауэрлифтингу 2023</div>
                </div>
            </div>
            <div class="diamond-item">
                <div class="diamond-content">
                    <img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80 " alt="Спортсмен 2" class="diamond-image">
                    <div class="diamond-title">Мария Петрова</div>
                    <div class="diamond-text">Чемпионка Европы по фитнесу 2024</div>
                </div>
            </div>
            <div class="diamond-item">
                <div class="diamond-content">
                    <img src="https://images.unsplash.com/photo-1581009146145-b5ef050c2e1e?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80 " alt="Спортсмен 3" class="diamond-image">
                    <div class="diamond-title">Дмитрий Сидоров</div>
                    <div class="diamond-text">Победитель турнира "Стальной кулак" 2024</div>
                </div>
            </div>
            <div class="diamond-item">
                <div class="diamond-content">
                    <img src="https://images.unsplash.com/photo-1549060279-7e168fce7090?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80 " alt="Кубок" class="diamond-image">
                    <div class="diamond-title">Наши награды</div>
                    <div class="diamond-text">Более 50 кубков и медалей за 2023-2024 годы</div>
                </div>
            </div>
        </div>
    </section>
    
    <div class="divider"></div>
    
    <!-- Equipment Section -->
    <section class="equipment-section">
        <h2 class="section-title">СПОРТИВНОЕ ОБОРУДОВАНИЕ</h2>
        <div class="equipment-container">
            <div class="equipment-slider" id="equipmentSlider">
                <div class="equipment-card">
                    <div class="equipment-icon">🏋️</div>
                    <h3 class="equipment-title">Гантели</h3>
                    <p class="equipment-description">Профессиональные гантели различного веса от 1 до 50 кг. Идеально подходят для силовых тренировок и развития мышц рук, плеч и груди.</p>
                </div>
                <div class="equipment-card">
                    <div class="equipment-icon">🥊</div>
                    <h3 class="equipment-title">Боксерские груши</h3>
                    <p class="equipment-description">Качественные боксерские груши для отработки ударов и развития выносливости. Подходят как для начинающих, так и для профессионалов.</p>
                </div>
                <div class="equipment-card">
                    <div class="equipment-icon">🧘</div>
                    <h3 class="equipment-title">Йога-мат</h3>
                    <p class="equipment-description">Профессиональные маты для йоги и стретчинга. Обеспечивают комфорт и безопасность во время тренировок на полу.</p>
                </div>
                <div class="equipment-card">
                    <div class="equipment-icon">⚡</div>
                    <h3 class="equipment-title">Эллиптический тренажер</h3>
                    <p class="equipment-description">Современные эллиптические тренажеры для кардио-тренировок. Развивают выносливость и укрепляют сердечно-сосудистую систему.</p>
                </div>
            </div>
            <div class="slider-controls">
                <button class="slider-btn" id="prevBtn">←</button>
                <button class="slider-btn" id="nextBtn">→</button>
            </div>
        </div>
    </section>
    
    <div class="divider"></div>
    
    <!-- Keep Body Fit Section -->
    <section class="section keep-fit">
        <h2 class="section-title">СОДЕРЖИ СВОЕ ТЕЛО В ФОРМЕ И СИЛЬНЫМ</h2>
        <div class="section-text">
            <p>Регулярные тренировки и правильное питание - ключ к успеху.<br>
            Наши программы помогут вам достичь идеальной формы<br>
            и поддерживать ее на протяжении всей жизни.<br>
            Присоединяйтесь к нашему сообществу уже сегодня!</p>
        </div>
    </section>
    
    <!-- Footer -->
    <footer id="contact" class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>CHARGETT</h3>
                    <p>О нас</p>
                    <p>Контакты</p>
                    <p>Расписание</p>
                </div>
                <div class="footer-column">
                    <h3>Тренировки</h3>
                    <p>Силовые</p>
                    <p>Кардио</p>
                    <p>Функциональные</p>
                </div>
                <div class="footer-column">
                    <h3>Программы</h3>
                    <p>Для начинающих</p>
                    <p>Профессиональные</p>
                    <p>Индивидуальные</p>
                </div>
                <div class="footer-column">
                    <h3>Контакты</h3>
                    <p>+7 (999) 123-45-67</p>
                    <p>info@begreater.ru</p>
                    <p>Москва, ул. Спортивная, 15</p>
                    <div class="social-buttons">
                        <a href="#" class="social-btn telegram">📱</a>
                        <a href="#" class="social-btn youtube">▶️</a>
                    </div>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 BeGreater. Все права защищены.</p>
            </div>
        </div>
    </footer>
    
    <!-- Scroll Button -->
    <div class="scroll-btn up" id="scrollBtn"></div>
    
    <script>
        // Improved smooth scroll function
        function smoothScrollTo(targetPosition, duration = 1500) {
            const startPosition = window.pageYOffset;
            const distance = targetPosition - startPosition;
            let startTime = null;
            
            function animation(currentTime) {
                if (startTime === null) startTime = currentTime;
                const timeElapsed = currentTime - startTime;
                const progress = Math.min(timeElapsed / duration, 1);
                
                // Easing function for smoother animation
                const ease = progress < 0.5 
                    ? 4 * progress * progress * progress 
                    : 1 - Math.pow(-2 * progress + 2, 3) / 2;
                
                window.scrollTo(0, startPosition + (distance * ease));
                
                if (timeElapsed < duration) {
                    requestAnimationFrame(animation);
                }
            }
            
            requestAnimationFrame(animation);
        }
        
        // Scroll to section function
        function scrollToSection(sectionId) {
            const element = document.getElementById(sectionId);
            if (element) {
                const elementPosition = element.getBoundingClientRect().top + window.pageYOffset;
                smoothScrollTo(elementPosition, 1200);
            }
        }
        
        // Scroll Button Functionality
        const scrollBtn = document.getElementById('scrollBtn');
        
        // Initially show the down arrow (scroll to bottom)
        scrollBtn.classList.remove('up');
        scrollBtn.classList.add('down');
        
        scrollBtn.addEventListener('click', function() {
            if (scrollBtn.classList.contains('down')) {
                // Scroll to bottom with smooth animation
                smoothScrollTo(document.body.scrollHeight, 1800);
            } else {
                // Scroll to top with smooth animation
                smoothScrollTo(0, 1800);
            }
        });
        
        // Change button direction based on scroll position
        window.addEventListener('scroll', function() {
            const scrollPosition = window.scrollY;
            const windowHeight = window.innerHeight;
            const documentHeight = document.body.scrollHeight;
            
            // If we're near the bottom, show up arrow, otherwise show down arrow
            if (scrollPosition + windowHeight >= documentHeight - 100) {
                scrollBtn.classList.remove('down');
                scrollBtn.classList.add('up');
            } else {
                scrollBtn.classList.remove('up');
                scrollBtn.classList.add('down');
            }
        });
        
        // Equipment Slider
        const equipmentSlider = document.getElementById('equipmentSlider');
        const prevBtn = document.getElementById('prevBtn');
        const nextBtn = document.getElementById('nextBtn');
        let currentSlide = 0;
        const totalSlides = 4;
        
        function updateSlider() {
            equipmentSlider.style.transform = `translateX(-${currentSlide * 100}%)`;
        }
        
        nextBtn.addEventListener('click', function() {
            currentSlide = (currentSlide + 1) % totalSlides;
            updateSlider();
        });
        
        prevBtn.addEventListener('click', function() {
            currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
            updateSlider();
        });
        
        // Auto slide every 5 seconds
        setInterval(function() {
            currentSlide = (currentSlide + 1) % totalSlides;
            updateSlider();
        }, 5000);
        
        // Diamond Hover Effects
        const diamondItems = document.querySelectorAll('.diamond-item');
        
        diamondItems.forEach(item => {
            item.addEventListener('mouseenter', function() {
                this.style.transform = 'rotate(45deg) scale(1.05)';
            });
            
            item.addEventListener('mouseleave', function() {
                this.style.transform = 'rotate(45deg) scale(1)';
            });
        });
    </script>
</body>
</html>
