<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>saoqa | информация</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <style>
        @font-face {
            font-family: 'Fixedsys';
            src: local('Fixedsys Excelsior'), local('FixedSys');
            font-style: normal;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #000;
            color: #ff69b4;
            font-family: 'Fixedsys', 'Courier New', monospace;
            line-height: 1.4;
            padding: 20px;
            overflow-x: hidden;
            position: relative;
            min-height: 100vh;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            position: relative;
            z-index: 10;
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
            padding: 15px;
            animation: fadeIn 2s ease-in-out;
        }
        
        .decorative-symbols {
            font-size: 24px;
            margin-bottom: 15px;
            letter-spacing: 3px;
        }
        
        h1 {
            font-size: 24px;
            font-weight: normal;
            margin: 10px 0;
            text-transform: uppercase;
            animation: glow 2s infinite alternate;
        }
        
        /* Специальный стиль для основного информационного блока */
        .main-info {
            text-align: center;
            margin: 30px auto;
            padding: 30px 20px;
            border: 2px solid #ff69b4;
            border-radius: 15px;
            position: relative;
            max-width: 500px;
            background: rgba(0, 0, 0, 0.7);
            box-shadow: 0 0 15px rgba(255, 105, 180, 0.5);
            z-index: 20;
        }
        
        .main-info::before {
            content: "";
            position: absolute;
            top: -10px;
            left: -10px;
            right: -10px;
            bottom: -10px;
            border: 1px solid #ff69b4;
            border-radius: 20px;
            opacity: 0.5;
            z-index: -1;
        }
        
        .main-info p {
            font-size: 20px;
            margin: 15px 0;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .pseudo {
            font-size: 32px !important;
            font-weight: bold;
            color: #ff1493;
            text-shadow: 0 0 10px #ff1493;
            margin: 20px 0 !important;
            animation: pulse 2s infinite;
        }
        
        .section {
            margin-bottom: 25px;
            padding: 15px;
            border: 1px solid #ff69b4;
            animation: slideIn 1s ease-out;
            background: rgba(0, 0, 0, 0.8);
        }
        
        .cloud {
            background: #ff69b4;
            border-radius: 20px;
            padding: 20px;
            margin: 15px 0;
            position: relative;
        }
        
        .cloud::after {
            content: "";
            position: absolute;
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
            border-width: 15px 15px 0;
            border-style: solid;
            border-color: #ff69b4 transparent transparent;
        }
        
        .cloud p {
            color: #000 !important;
            font-weight: bold;
        }
        
        .section-title {
            font-size: 22px;
            margin-bottom: 15px;
            text-align: center;
            font-family: 'Playfair Display', serif;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #ff1493;
            text-shadow: 0 0 5px #ff69b4;
        }
        
        ul {
            list-style-type: none;
            padding-left: 5px;
        }
li {
            margin-bottom: 8px;
            position: relative;
            padding-left: 15px;
        }
        
        li:before {
            content: "·";
            position: absolute;
            left: 0;
        }
        
        p {
            margin-bottom: 12px;
        }
        
        /* Анимация лепестков сакуры */
        .sakura-petal {
            position: absolute;
            background-color: #ff69b4;
            border-radius: 50% 0% 50% 50%;
            transform: rotate(45deg);
            z-index: 1;
            pointer-events: none;
            opacity: 0.7;
        }
        
        /* Анимации */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes glow {
            from { text-shadow: 0 0 5px #ff69b4; }
            to { text-shadow: 0 0 15px #ff69b4, 0 0 20px #ff1493; }
        }
        
        @keyframes slideIn {
            from { transform: translateX(-20px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        @keyframes fall {
            from { transform: translateY(-100px) rotate(0deg); }
            to { transform: translateY(100vh) rotate(360deg); }
        }
        
        .text-animation {
            animation: fadeIn 2s ease-in-out;
        }
        
        /* Адаптивность */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .decorative-symbols {
                font-size: 18px;
            }
            
            h1 {
                font-size: 20px;
            }
            
            .section {
                padding: 10px;
            }
            
            .main-info p {
                font-size: 16px;
            }
            
            .pseudo {
                font-size: 24px !important;
            }
        }
    </style>
</head>
<body>
    <!-- Контейнер для лепестков сакуры -->
    <div id="sakura-container"></div>
    
    <div class="container">
        <div class="header">
            <div class="decorative-symbols">⁺‧₊˚ ཐི⋆♱⋆ཋྀ ˚₊‧⁺</div>
            <h1>инфо.</h1>
        </div>
        
        <div class="main-info text-animation">
            <p class="pseudo">saoqa (сока)</p>
            <p>зз: козерог 19.01</p>
            <p>возраст скрыт</p>
            <p>свободна</p>
            <p>прон: she/her</p>
        </div>
        
        <div class="section text-animation">
            <h3 class="section-title">кинны</h3>
            <ul>
                <li>лаума (геншин)</li>
                <li>ая (парень, которым увлечена)</li>
                <li>астарот (геншин)</li>
            </ul>
        </div>
        
        <div class="section text-animation">
            <h3 class="section-title">фд, интересы</h3>
            <div class="cloud">
                <p>фав фд: Отель Хазбин, Последняя реальность, Тринадцать огней, Голос времени, Осколки снов, Вместе, Дневник плохих мыслей, дроны убийцы, ключи королевства, метал фемили, уцц, кпоп (50/50), блюлок, волейбол.</p>
            </div>
            
            <div class="cloud">
                <p>фав игры: FNAF, Yandere Simulator, The Purgatory of Hopes (тпох), майн, genshin impact, roblox, zzz.</p>
            </div>
            
            <div class="cloud">
<p>фав аниме и манга: Твоё имя, Бездомный бог, Форма голоса, Унесённые призраками, Нет игры — нет жизни, Ходячий замок, Иная, Хоримия, Кукла влюбилась, Укрась прощальное утро цветами, Чудовище за последней партой, Сад изящных слов, Ангел кровопролития, Повар-боец, Ребёнок идола, Агент времени, Очень приятно Бог, Госпожа Кагуя, Банановая рыба, Кланнад, Монолог фармацевта, Семья шпиона, Не моя вина, что я непопулярна, Кейон!, Добро пожаловать в класс превосходства, Пять невест, Двуличная сестрёнка Умару, Связь сердец, Чудачества любви не помеха, Нана, У Коми проблемы с общением, Дотянуться до тебя, Как воспитать героиню из девушки, Неудержимая юность, Не издевайся, Нагаторо-сан, Человек-бензопила, крд</p>
            </div>
            
            <div class="cloud">
                <p>Твич: Еблан Скв, 89, Шпана.</p>
            </div>
        </div>
        
        <div class="section text-animation">
            <h3 class="section-title">музыкальный вкус</h3>
            <p>Любимые исполнители:</p>
            <ul>
                <li>mzlff (!)</li>
                <li>beabadoobee (!!)</li>
                <li>Ado (!)</li>
            </ul>
            
            <p>Любимые треки:</p>
            <ul>
                <li>«Цветочек маленький»</li>
                <li>«Readymade»</li>
                <li>«Glue Song»</li>
                <li>«Talk»</li>
            </ul>
        </div>
        
        <div class="section text-animation">
            <h3 class="section-title">предпочтения</h3>
            <p>фав жанры: Романтика, Фэнтези</p>
            <p>фав игры (в которые часто играю): Genshin Impact, Murder Mystery 2, севх</p>
            <p>Хобби: Музыка, Писательство</p>
            
            <p>Еда:</p>
            <ul>
                <li>обожаю: Гречневый суп</li>
                <li>не переношу: Всю молочку</li>
            </ul>
            
            <p>Любимый цвет: темно-синий, белый (пастельный) и впринцепи вся пастельная палитра, из ярких кислотно-зеленый если это сочетается</p>
        </div>
        
        <div class="section text-animation">
            <h3 class="section-title">мбти (для интереса)</h3>
            <ul>
                <li>MBTI: ENTP-T (основной)</li>
                <li>грин/ф: ENFP-T, INTJ-T-A</li>
                <li>ред/ф: ENTJ</li>
            </ul>
            
            <p>пояснение: мой мбти, с развитым fe, поэтому не бойтесь я добрая</p>
        </div>
        
        <div class="section text-animation">
            <p>примечание: эта карточка была создана для флуда, но теперь живёт здесь для любознательных</p>
        </div>
    </div>

    <script>
        // Создание лепестков сакуры
        function createSakuraPetals() {
            const container = document.getElementById('sakura-container');
            const numberOfPetals = 25;
            
            for (let i = 0; i < numberOfPetals; i++) {
                const petal = document.createElement('div');
                petal.classList.add('sakura-petal');
                
                // Случайный размер
                const size = Math.random() * 15 + 5;
                petal.style.width = `${size}px`;
                petal.style.height = `${size}px`;
                
                // Начальная позиция
                petal.style.left = `${Math.random() * 100}vw`;
                petal.style.top = `${Math.random() * 100}vh`;
                
                // Прозрачность
                petal.style.opacity = Math.random() * 0.5 + 0.3;
                
                // Анимация
                const animationDuration = Math.random() * 10 + 10;
                petal.style.animation = `fall ${animationDuration}s linear infinite`;
                
                container.appendChild(petal);
            }
        }
        
        // Анимация появления текста с задержкой
        function animateText() {
            const sections = document.querySelectorAll('.text-animation');
            sections.forEach((section, index) => {
                section.style.
animationDelay = `${index * 0.2}s`;
            });
        }
        
        // Запуск при загрузке страницы
        window.onload = function() {
            createSakuraPetals();
            animateText();
        };
    </script>
</body>
</html>
