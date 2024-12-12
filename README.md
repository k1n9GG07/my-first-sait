<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="utf-8"/>
    <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
    <title>Все о NFT</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;family=Orbitron:wght@400;700&amp;display=swap" rel="stylesheet"/>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212; /* Темный фон */
            color: #ffffff; /* Светлый цвет текста */
            overflow-x: hidden; /* Скрыть горизонтальный скролл */
            background-image: url('https://storage.googleapis.com/a1aa/image/nft-background.jpg'); /* Фоновое изображение */
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }
        header {
            background-color: #1e1e1e; /* Темный фон для шапки */
            color: #00ffcc; /* Светло-зеленый цвет текста */
            padding: 1rem 0;
            text-align: center;
            box-shadow: 0 0 10px rgba(0, 255, 204, 0.5); /* Эффект свечения */
        }
        header h1 {
            margin: 0;
            font-family: 'Orbitron', sans-serif; /* Шрифт, напоминающий компьютерный */
            font-size: 2.5rem;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .section-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 2rem;
            margin-bottom: 1rem;
            color: #00ffcc; /* Светло-зеленый цвет текста */
        }
        .content {
            background-color: rgba(30, 30, 30, 0.9); /* Темный фон для контента с небольшой прозрачностью */
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 255, 204, 0.5); /* Эффект свечения */
            margin-bottom: 2rem;
            display: flex;
            flex-direction: column;
        }
        .content img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 255, 204, 0.5); /* Эффект свечения */
            margin-right: 1rem;
        }
        .content-wrapper {
            display: flex;
            align-items: flex-start;
        }
        .text-content {
            flex: 1;
            font-size: 1.5rem; /* Увеличенный размер текста */
        }
        footer {
            background-color: #1e1e1e; /* Темный фон для футера */
            color: #ffffff; /* Светлый цвет текста */
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
            box-shadow: 0 0 10px rgba(0, 255, 204, 0.5); /* Эффект свечения */

    <!-- Основной контент -->
    <div id="content">
        <header>
            <h1>Все о NFT</h1>
        </header>
        <div class="container">
            <section class="content" id="home">
                <h2 class="section-title">Добро пожаловать</h2>
                <p class="text-content">Наш сайт посвященный невзаимозаменяемым токенам (NFT). Здесь вы найдете всю необходимую информацию о том, что такое NFT, как они работают, их историю, популярные платформы для торговли и советы по инвестированию.</p>
            </section>
            <section class="content" id="what-is-nft">
                <h2 class="section-title">Что такое NFT</h2>
                <div class="content-wrapper">
                    <img alt="Изображение, объясняющее концепцию NFT, с графикой блокчейна и цифровых активов" height="400" src="https://storage.googleapis.com/a1aa/image/I9cOVnCjve39ZS3ps8Gm9MLi5Zn2jZeuMUDI92VNHmfyHhxnA.jpg" width="600"/>
                    <div class="text-content">
                        <p>NFT (невзаимозаменяемые токены) — это уникальные цифровые активы, которые представляют собой собственность на определенные предметы или контент, такие как произведения искусства, музыка, видео и другие цифровые файлы. В отличие от криптовалют, таких как биткойн или эфир, каждый NFT уникален и не может быть заменен другим токеном один к одному.</p>
                    </div>
                </div>
            </section>
            <section class="content" id="how-nft-works">
                <h2 class="section-title">Как работают NFT</h2>
                <div class="content-wrapper">
                    <img alt="Техническая диаграмма, показывающая, как NFT работают на блокчейне" height="400" src="https://storage.googleapis.com/a1aa/image/2PZbm0OLeEUJd6CDDsgJ2arXB5sGVjw0T5P5zW13dVX9RY8JA.jpg" width="600"/>
                    <div class="text-content">
                        <p>NFT работают на основе технологии блокчейн, которая обеспечивает безопасность и прозрачность транзакций. Каждый NFT содержит уникальную информацию, записанную в блокчейне, что делает его неподдельным и легко проверяемым. Основные блокчейны, используемые для создания и торговли NFT, включают Ethereum, Binance Smart Chain и другие.</p>
                    </div>
                </div>
            </section>
            <section class="content" id="history">
                <h2 class="section-title">История NFT</h2>
                <div class="content-wrapper">
                    <img alt="Хронологическая шкала, показывающая ключевые моменты в истории развития NFT" height="400" src="https://storage.googleapis.com/a1aa/image/GbjIC4JOz8aADh3n5yQeG56fk8Hk5Qr2VsqicPuIKSb9jw4TA.jpg" width="600"/>
                    <div class="text-content">
                        <p>История NFT начинается с появления первых цифровых активов на блокчейне. Одним из первых известных примеров является проект CryptoPunks, запущенный в 2017 году. С тех пор рынок NFT значительно вырос, и сегодня он включает в себя множество различных проектов и платформ, таких как OpenSea, Rarible и другие.</p>
                    </div>
                </div>
            </section>
            <section class="content" id="platforms">
                <h2 class="section-title">Популярные платформы</h2>
                <div class="content-wrapper">
                    <img alt="Логотипы популярных платформ для торговли NFT, таких как OpenSea, Rarible и другие" height="400" src="https://storage.googleapis.com/a1aa/image/FQfrX1f8rxq8EEwDeD6nLqydfKhgf00NSlil3VUHMOnGgEGfE.jpg" width="600"/>
                    <div class="text-content">
                        <p>Существует множество платформ для торговли NFT, каждая из которых предлагает уникальные возможности и функции. Некоторые из самых популярных платформ включают:</p>
                        <ul>
                            <li>OpenSea</li>
                            <li>Rarible</li>
                            <li>SuperRare</li>
                            <li>Foundation</li>
                            <li>Mintable</li>
                        </ul>
                    </div>
                </div>
            </section>
            <section class="content" id="investing">
                <h2 class="section-title">Инвестирование в NFT</h2>
                <div class="content-wrapper">
                    <img alt="График, показывающий рост и падение цен на рынке NFT" height="400" src="https://storage.googleapis.com/a1aa/image/7zODQlEjhb45Jx5fKLimfmlkf8EKv4NFLo6MxjST6K33HhxnA.jpg" width="600"/>
                    <div class="text-content">
                        <p>Инвестирование в NFT может быть прибыльным, но также связано с рисками. Вот несколько советов для начинающих инвесторов:</p>
                        <ul>
                            <li>Исследуйте рынок и изучайте проекты перед покупкой.</li>
                            <li>Инвестируйте только те средства, которые вы готовы потерять.</li>
                            <li>Следите за новостями и трендами в мире NFT.</li>
                            <li>Используйте надежные платформы для торговли и хранения NFT.</li>
                        </ul>
                    </div>
                </div>
            </section>
            <section class="content" id="forum">
                <h2 class="section-title">Форум</h2>
                <p class="text-content">Присоединяйтесь к нашему форуму, чтобы обсуждать статьи и темы, связанные с NFT. Делитесь своим опытом, задавайте вопросы и получайте ответы от сообщества.</p>
                <div id="comments"></div>
                <form id="comment-form">
                    <input type="text" id="author" placeholder="Ваше имя" required>
                    <textarea id="text" placeholder="Ваш комментарий" required></textarea>
                    <button type="submit">Отправить</button>
                </form>
            </section>
        </div>
        <footer>
            <p>© 2024 Все о NFT. Все права защищены.</p>
        </footer>
    </div>

    <script>
        function toggleSidebar() {
            document.body.classList.toggle('sidebar-open');
        }

        // Загрузка комментариев из локального хранилища
        function loadComments() {
            const comments = JSON.parse(localStorage.getItem('comments')) || [];
            const commentsContainer = document.getElementById('comments');
            commentsContainer.innerHTML = '';
            comments.forEach(comment => {
                const commentElement = document.createElement('div');
                commentElement.className = 'comment';
                commentElement.innerHTML = `
                    <div class="author">${comment.author}</div>
                    <div class="text">${comment.text}</div>
                `;
                commentsContainer.appendChild(commentElement);
            });
        }

        // Сохранение комментария в локальное хранилище
        function saveComment(author, text) {
            const comments = JSON.parse(localStorage.getItem('comments')) || [];
            comments.push({ author, text });
            localStorage.setItem('comments', JSON.stringify(comments));
            loadComments();
        }

        // Обработка отправки формы
        document.getElementById('comment-form').addEventListener('submit', function(event) {
            event.preventDefault();
            const author = document.getElementById('author').value;
            const text = document.getElementById('text').value;
            saveComment(author, text);
            document.getElementById('author').value = '';
            document.getElementById('text').value = '';
        });

        // Загрузка комментариев при загрузке страницы
        window.addEventListener('load', loadComments);
    </script>
</body>
</html>
