<template>
    <div class="main">
        <div class="main-review">
            <div class="review">
                <div class="user-rev"></div>
                <div class="user-rev"></div>
                <div class="user-rev"></div>
            </div>
            <div class="form-review">
                <p>Ваш отзыв<br><br>
                    <textarea name="comment" cols="80" rows="5"></textarea>
                </p>
                <p><input type="submit" value="Отправить" class="button"></p>
            </div>
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
    name: 'FeedBack',
    components: {

    }
}
</script>