<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио - Приют для животных</title>
    <!-- Подключение CSS Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Подключение собственных стилей -->
    <link rel="stylesheet" href="css/тк4.css">
</head>
<body>

    <!-- Шапка сайта (Navbar) -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <!-- Логотип или название сайта -->
                <a class="navbar-brand" href="#">Приют для животных</a>
                <!-- Кнопка для мобильных устройств -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <!-- Меню навигации -->
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Главная</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">О нас</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Животные</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Контакты</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Блок контента с приветствием и изображением -->
    <section class="py-5">
        <div class="container text-center">
            <div class="row">
                <!-- Текстовый блок -->
                <div class="col-md-6">
                    <h1>Добро пожаловать в наш приют!</h1>
                    <p>Мы заботимся о животных и ищем для них новый дом.</p>
                </div>
                <!-- Изображение -->
                <div class="col-md-6">
                    <img src="https://pet-portal.ru/wp-content/uploads/shelter-solnczevo.webp" class="img-fluid" alt="Приют для животных">
                </div>
            </div>
        </div>
    </section>

    <!-- Секция с каруселью изображений -->
    <section class="py-5">
        <div class="container">
            <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <!-- Первый слайд (активный) -->
                    <div class="carousel-item active">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQzvoFOqhF1U2XWrWCps4CEJ2vJUIPGbp9ZFw&s" class="d-block w-100" alt="Животное 1">
                    </div>
                    <!-- Второй слайд -->
                    <div class="carousel-item">
                        <img src="https://i.pinimg.com/736x/10/8e/6d/108e6dbdcc4358116a5ae3b78a5e10a4.jpg" class="d-block w-100" alt="Животное 2">
                    </div>
                    <!-- Третий слайд -->
                    <div class="carousel-item">
                        <img src="https://i.pinimg.com/736x/63/ac/cb/63accb649a5af5cf7847aa9e2c0b4b92.jpg" class="d-block w-100" alt="Животное 3">
                    </div>
                </div>
                <!-- Кнопки управления каруселью -->
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Предыдущий</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Следующий</span>
                </button>
            </div>
        </div>
    </section>

    <!-- Секция с карточками животных -->
    <section class="py-5">
        <div class="container">
            <div class="row">
                <!-- Карточка 1 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEdp1iNWvff2UO8OWnmzcTa5UUWLQQpxmeNQ&s" class="card-img-top" alt="Кошка">
                        <div class="card-body">
                            <h5 class="card-title">Мурзик</h5>
                            <p class="card-text">Дружелюбный и игривый кот.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
                <!-- Карточка 2 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_EQw77TsBL1rcD5D9ELIFcSB6oxX5FobgtQ&s" class="card-img-top" alt="Собака">
                        <div class="card-body">
                            <h5 class="card-title">Мухтар</h5>
                            <p class="card-text">Весёлый и активный пёс.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
                <!-- Карточка 3 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfOpMd4nc95Pd0_5RopmYsYqxGi1JknZx59Q&s" class="card-img-top" alt="Кролик">
                        <div class="card-body">
                            <h5 class="card-title">Пушистик</h5>
                            <p class="card-text">Милый и спокойный кролик.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Секция с формой для связи -->
    <section class="py-5">
        <div class="container">
            <h2>Свяжитесь с нами</h2>
            <form>
                <!-- Поле для имени -->
                <div class="mb-3">
                    <label for="name" class="form-label">Ваше имя</label>
                    <input type="text" class="form-control" id="name">
                </div>
                <!-- Поле для email -->
                <div class="mb-3">
                    <label for="email" class="form-label">Ваш email</label>
                    <input type="email" class="form-control" id="email">
                </div>
                <!-- Поле для сообщения -->
                <div class="mb-3">
                    <label for="message" class="form-label">Сообщение</label>
                    <textarea class="form-control" id="message" rows="3"></textarea>
                </div>
                <!-- Кнопка отправки формы -->
                <button type="submit" class="btn btn-primary">Отправить</button>
            </form>
        </div>
    </section>

    <!-- Подвал сайта -->
    <footer class="bg-light py-4">
        <div class="container text-center">
            <p>Адрес: ул. Гагарина, д. 10</p>
            <p>Телефон: +7 (929) 999-99-99</p>
            <p>Email: info@gmail.com</p>
        </div>
    </footer>

    <!-- Подключение JS Bootstrap -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
