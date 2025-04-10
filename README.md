<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GetBeauty - Платформа бьюти-консультаций</title>
    <style>
        :root {
            --primary-color: #BC987E; /* Бледный серо-коричневый */
            --secondary-color: #D4BFA8; /* Светлый серо-коричневый */
            --accent-color: #A38F7C; /* Темный серо-коричневый */
            --light-color: #F5F0EB; /* Очень светлый бежевый */
            --dark-color: #5A4A42; /* Темно-коричневый */
            --text-color: #5A4A42; /* Основной текст */
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            margin: 0;
            padding: 0;
            background-color: var(--light-color);
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 40px 0;
            text-align: center;
            margin-bottom: 30px;
            border-radius: 0 0 15px 15px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.2);
        }
        
        .tagline {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 30px;
        }
        
        .section {
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            padding: 30px;
            margin-bottom: 30px;
            border: 1px solid rgba(0,0,0,0.05);
        }
        
        h2 {
            color: var(--dark-color);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 10px;
            margin-top: 0;
        }
        
        ul {
            padding-left: 20px;
        }
        
        li {
            margin-bottom: 10px;
            list-style-type: none;
            position: relative;
            padding-left: 25px;
        }
        
        li:before {
            content: "•";
            color: var(--primary-color);
            font-size: 1.5rem;
            position: absolute;
            left: 0;
            top: -5px;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            background-color: white;
        }
        
        th, td {
            padding: 15px;
            border: 1px solid #f0f0f0;
            vertical-align: top;
        }
        
        th {
            background-color: var(--secondary-color);
            text-align: left;
            color: white;
            font-weight: 600;
        }
        
        .partners {
            font-style: italic;
            margin: 20px 0;
            text-align: center;
            color: var(--dark-color);
            background-color: rgba(212, 191, 168, 0.3);
            padding: 10px;
            border-radius: 8px;
        }
        
        .cta-button {
            display: inline-block;
            background-color: var(--dark-color);
            color: white;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            transition: all 0.3s;
            border: none;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        .cta-button:hover {
            background-color: #4A3A32;
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }
        
        .more-link {
            text-align: right;
            font-style: italic;
            margin-top: 10px;
            color: var(--dark-color);
        }
        
        footer {
            background-color: var(--dark-color);
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 40px;
            border-radius: 15px 15px 0 0;
        }
        
        @media (max-width: 768px) {
            table {
                display: block;
                overflow-x: auto;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>GetBeauty</h1>
            <p class="tagline">Платформа бьюти-консультаций</p>
            <a href="#register" class="cta-button">Начать бесплатно</a>
        </div>
    </header>
    
    <div class="container">
        <section class="section" id="about">
            <h2>О НАС</h2>
            <p><strong>GetBeauty - многопользовательская платформа по предоставлению бьюти-консультаций.</strong></p>
            
            <h3>Мы предлагаем:</h3>
            <ul>
                <li>Индивидуальный подход к каждому клиенту</li>
                <li>Доступ к квалифицированным специалистам в чате нашего приложения</li>
                <li>Оплату подписки на услуги в проверенном платежном сервисе не выходя из приложения</li>
                <li>Огромное количество бесплатных статей, подборок, подкастов от ведущих блогеров и профессионалов</li>
                <li>Функцию умной камеры с ИИ для анализа вашего стиля</li>
            </ul>
            
            <div class="partners">
                Сотрудничаем с крупными брендами косметики и одежды «Золотое яблоко» и «Lime»
            </div>
        </section>
        
        <section class="section" id="trends">
            <h2>ТРЕНДЫ И НОВИНКИ</h2>
            
            <table>
                <tr>
                    <th>Для женщин</th>
                    <th>Для мужчин</th>
                </tr>
                <tr>
                    <td>
                        <ul>
                            <li>Эксперименты с текстурами</li>
                            <li>Спортивный шик</li>
                            <li>Традиционные ткани в современных формах</li>
                        </ul>
                    </td>
                    <td>
                        <ul>
                            <li>Модульная одежда</li>
                            <li>Новая классика</li>
                            <li>Уличный стиль</li>
                            <li>Аксессуары как акцент</li>
                        </ul>
                    </td>
                </tr>
            </table>
            
            <div class="more-link">подробнее о каждом тренде на следующей странице &gt;</div>
        </section>
        
        <section class="section" id="register">
            <h2>ГОТОВЫ НАЧАТЬ?</h2>
            <p>Присоединяйтесь к тысячам довольных клиентов, которые уже улучшили свой стиль с GetBeauty</p>
            <a href="#" class="cta-button">Зарегистрироваться</a>
        </section>
    </div>
    
    <footer>
        <div class="container">
            <p>&copy; 2025 GetBeauty. Все права защищены.</p>
            <p>Свяжитесь с нами: info@getbeauty.ru | +7 (123) 456-78-90</p>
        </div>
    </footer>
</body>
</html>
