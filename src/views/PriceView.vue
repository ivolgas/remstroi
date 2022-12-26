<template>
    <div class="main">
        <div class="price-content">
            <div class="name-content">
                <span>ОРИЕНТИРОВОЧНЫЕ ЦЕНЫ НА УСЛУГИ*</span>
            </div>
            <div class="table-content">
                <table>
                    <tr>
                        <th>Услуга</th>
                        <th>Стоимость, <br> за ед.</th>
                        <th>Заказать</th>
                    </tr>
                    <tr>
                        <td id="repair">Реммонт квартир</td>
                        <td class="price">1000</td>
                        <td>
                            <div class="basket">
                                <input type="number" min="0" id="sum">
                                <input type="button" class="btn-basket" value="в корзину">
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <td>Ремонт частных домов</td>
                        <td class="price">1000</td>
                        <td>
                            <div class="basket">
                                <input type="number" min="0" id="sum">
                                <input type="button" class="btn-basket" value="в корзину">
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <td>Отделочные работы</td>
                        <td class="price">1000</td>
                        <td>
                            <div class="basket">
                                <input type="number" min="0" id="sum">
                                <input type="button" class="btn-basket" value="в корзину">
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <td>Сантехнические работы</td>
                        <td class="price">1000</td>
                        <td>
                            <div class="basket">
                                <input type="number" min="0" id="sum">
                                <input type="button" class="btn-basket" value="в корзину">
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <td>Электромонтажные работы</td>
                        <td class="price">1000</td>
                        <td>
                            <div class="basket">                                
                                <input type="number" min="0" id="sum">
                                <input type="button" class="btn-basket" value="в корзину">
                            </div>
                        </td>
                    </tr>                    
                </table>
                
            </div>
            <!-- <div class="button-fly">
                <button>Наверх</button>
            </div> -->
        </div>
    </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

/* export default {
    name: 'HomeView',
    components: {
        HelloWorld
    }
} */

export default {
    name: 'PriceView',
    components: {

    }
}


</script>