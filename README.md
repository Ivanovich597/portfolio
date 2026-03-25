<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IT-Услуги | Профессиональная разработка</title>
    <style>
        /* CSS - Оформление сайта */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; line-height: 1.6; color: #333; background: #f4f7f6; }
        header { background: #2c3e50; color: white; padding: 60px 20px; text-align: center; }
        nav { background: #34495e; padding: 10px; text-align: center; position: sticky; top: 0; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        .container { max-width: 1000px; margin: 20px auto; padding: 20px; background: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .services { display: flex; flex-wrap: wrap; justify-content: space-around; gap: 20px; margin-top: 30px; }
        .service-card { background: #fff; border: 1px solid #ddd; padding: 20px; width: 280px; border-radius: 10px; transition: 0.3s; text-align: center; }
        .service-card:hover { transform: translateY(-5px); box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .btn { display: inline-block; background: #e74c3c; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin-top: 20px; }
        footer { text-align: center; padding: 40px; background: #2c3e50; color: white; margin-top: 40px; }
        form { display: flex; flex-direction: column; gap: 10px; max-width: 500px; margin: 0 auto; }
        input, textarea { padding: 10px; border: 1px solid #ccc; border-radius: 5px; }
    </style>
</head>
<body>

<header>
    <h1>Разработка Telegram-ботов и сайтов</h1>
    <p>Помогаю вашему бизнесу зарабатывать больше в интернете</p>
</header>

<nav>
    <a href="#about">Обо мне</a>
    <a href="#services">Услуги</a>
    <a href="#contact">Заказать проект</a>
</nav>

<div class="container" id="about">
    <h2>Почему выбирают меня?</h2>
    <p>Я создаю быстрые и эффективные решения для малого и среднего бизнеса. Мои боты автоматизируют продажи, а сайты привлекают новых клиентов.</p>
    
    <div class="services" id="services">
        <div class="service-card">
            <h3>Telegram Боты</h3>
            <p>Автоматизация заказов, техподдержка и чат-менеджеры под ключ.</p>
            <strong>от 150 BYN</strong>
        </div>
        <div class="service-card">
            <h3>Лендинги</h3>
            <p>Продающие одностраничные сайты с высокой конверсией.</p>
            <strong>от 300 BYN</strong>
        </div>
        <div class="service-card">
            <h3>Настройка рекламы</h3>
            <p>Привлечение целевого трафика из соцсетей и поиска.</p>
            <strong>от 100 BYN</strong>
        </div>
    </div>
</div>

<div class="container" id="contact">
    <h2 style="text-align: center;">Оставить заявку</h2>
    <form id="contactForm">
        <input type="text" placeholder="Ваше имя" required>
        <input type="email" placeholder="Ваш Email или Telegram" required>
        <textarea rows="5" placeholder="Опишите вашу задачу"></textarea>
        <button type="submit" class="btn" style="border: none; cursor: pointer;">Отправить сообщение</button>
    </form>
</div>

<footer>
    <p>&copy; 2024 Мой IT-Проект. Сделано с помощью ИИ.</p>
</footer>

<script>
    // Простая логика для формы
    document.getElementById('contactForm').addEventListener('submit', function(e) {
        e.preventDefault();
        alert('Спасибо за заявку! Я свяжусь с вами в ближайшее время.');
        this.reset();
    });
</script>

</body>
</html># portfolio
.
