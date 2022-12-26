<template>
    <div class="header">
        <div class="main-main-menu">
            <ul class="main-menu">
                <li>
                    <router-link class="menu-item" to="/page">
                        <div class="page-link">Главная</div>
                    </router-link>
                </li>
                <li>
                    <a href="#" class="menu-item">
                        <div class="page-link">Услуги&nbsp;></div>
                    </a>
                    <ul class="main-menu dropdown">
                        <li>
                            <a href="#" class="menu-item">
                                <div class="page-link dropdown">Ремонт квартир</div>
                            </a>
                        </li>
                        <li>
                            <a href="#" class="menu-item">
                                <div class="page-link dropdown">Ремонт частных домов</div>
                            </a>
                        </li>
                        <li>
                            <a href="#" class="menu-item">
                                <div class="page-link dropdown">Отделочные работы</div>
                            </a>
                        </li>
                        <li>
                            <a href="#" class="menu-item">
                                <div class="page-link dropdown">Сантехнические работы</div>
                            </a>
                        </li>
                        <li>
                            <a href="#" class="menu-item">
                                <div class="page-link dropdown">Электромонтажные работы</div>
                            </a>
                        </li>
                    </ul>
                </li>
                <li>
                    <router-link class="menu-item" to="/feedback">
                        <div class="page-link">Отзывы</div>
                    </router-link>
                </li>
                <li>
                    <router-link class="menu-item" to="/price">
                        <div class="page-link">Цены</div>
                    </router-link>
                </li>                
            </ul>
        </div>

        <div class="link-reg">
            
            <router-link class="menu-item" to="/basket">
                <div class="page-link">
                    <img src="images/basket.png">
                </div>
            </router-link>

            <router-link class="menu-item" to="/login" onclick="document.getElementById('id01').style.display='block'"
                style="width:auto;">
                <div class="page-link">Log in</div>
            </router-link>

            <router-link class="menu-item" to="/signup">
                <div class="page-link">Sign up</div>
            </router-link>


        </div>
    </div>
</template>