<template>
    <div>
        <!-- html -->
        <header>
        <nav>
            <div class="container header-nav">
                <a href="#" class="logo">PROWEB</a>
                <ul>
                    <li><a href="#">Обо мне</a></li>
                    <li><a href="#">Мои работы</a></li>
                    <li><a href="#">Контакты</a></li>
                </ul>
            </div>
        </nav>
        <div class="header-content">
            <h1>Добро пожаловать на мой сайт</h1>
            <a href="tel:+998907777777" class="call">Позвонить</a>
        </div>
    </header>

    </div>
</template>

<script>
    export default {
        // javascript code
    }
</script>

<style>

        /* css */

.container {
    max-width: 1140px;
    width: 100%;
    padding: 0 15px;
    margin: 0 auto;
}

nav {
    background: #000000;
    padding: 14px 0;
}

.logo {
    font-weight: 700;
    font-size: 40px;
    line-height: 48px;
    color: #FFFFFF;
}

.header-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header ul {
    display: flex;
    gap: 75px;
}

header ul a {
    font-size: 25px;
    line-height: 30px;
    color: #FFFFFF;
    transition: color 500ms;
}

header ul a:hover {
    color: orange;
}

.header-content {
    height: 850px;
    background: url(../assets/Rectangle\ 2.png) no-repeat center /cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.header-content h1 {
    font-size: 40px;
    line-height: 48px;
    color: #000000;
    margin-bottom: 150px;
}

.call {
    background: #FFFFFF;
    border-radius: 10px;
    font-weight: 700;
    font-size: 35px;
    line-height: 42px;
    color: #000000;
    padding: 10px 23px;
}

</style>