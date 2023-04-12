<script>
    export default {
        name: "FormsSector"
    }
</script>

<template>
    <div class="container my-5">
        <div class="leftSection">
            <h6>SEND A MESSAGE</h6>
        <h2 class="my-4">Get in <mark>Touch</mark></h2>

        <span>We will respond to your message as soon as possible.</span>
        
        <!--Form start-->
        <div class="row">
            <div class="col my-2">
                <input type="text" class="form-control myDecorations" placeholder="Name" aria-label="First name">
            </div>
            <div class="col my-2">
                <input type="text" class="form-control myDecorations" placeholder="Email" aria-label="Last name">
            </div>
        </div>

        <div class="row">
            <div class="col my-2">
                <input type="text" class="form-control myDecorations" placeholder="Phone" aria-label="First name">
            </div>
            <div class="col my-2">
                <select id="inputState" class="form-select myDecorations">
                    <option selected>More info</option>
                    <option>...</option>
                </select>
            </div>
        </div>

        <div class="mb-3">
            <textarea class="form-control myDecorations" id="exampleFormControlTextarea1" rows="3" placeholder="Message"></textarea>
        </div>

        <a href="#">SEND</a>
        </div>
        
    </div>

</template>

<style scoped lang="scss">
     @import "../styles/general.scss";
    .container {
        h6 {
            color: $cube-darkGreen;
        }

        h2 {
            font-weight: bolder;
            mark {
                color: $cube-darkGreen;
                background-color: rgba($cube-darkGreen, $alpha: 0.1);
            }
        }
        span {
            color: $cube-darkGray;
        }

        .myDecorations {
            background-color: rgb(220, 219, 219);

        }
    }

    .leftSection {
        width: 55%;
    }
</style>