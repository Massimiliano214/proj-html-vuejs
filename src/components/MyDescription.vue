<script>
    export default {
        name: "MyDescription"
    }
</script>

<template>
    <div class="container">
        <h6>WHO WE ARE</h6>
        <h2>
            
            <mark class="decorations"><i class="fa-regular fa-gem"></i> Excellence</mark>
            in Transport
        </h2>

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita corrupti tempora voluptas qui omnis nobis suscipit voluptates architecto, mollitia molestias?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A blanditiis at doloremque quas aut perferendis praesentium odio commodi, hic earum?</p>

        <em class="citation">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Adipisci neque nisi delectus eveniet magnam exercitationem assumenda obcaecati inventore similique architecto.</em>
    </div>

</template>

<style scoped lang="scss">
    @import "../styles/general.scss";

    h6 {
        padding-top: 20px;
        color: $cube-darkGreen;
    }
    h2 {
        font-weight: bolder;
        padding: 20px 0;
    }
    .citation {
        padding-left: 50px;
        border-left: 5px solid $cube-darkGreen;
    }
    .decorations {
        color: $cube-darkGreen;
        background-color: rgba($color: $cube-darkGreen, $alpha: 0.2);
    }

</style>