<script>
    export default {
        name: "FormsSector"
    }
</script>

<template>
    <div class="container my-5 d-flex justify-content-between">
        <div class="leftSection">
            <h6>SEND A MESSAGE</h6>
            <h2 class="py-4">Get in <mark>Touch</mark></h2>
            
            <div class="py-4">
                <span>We will respond to your message as soon as possible.</span>
            </div>
            
            <!--Form start-->
            <div class="row">
                <div class="col my-2">
                    <input type="text" class="form-control myDecorations" placeholder="Name" aria-label="Name">
                </div>
                <div class="col my-2">
                    <input type="text" class="form-control myDecorations" placeholder="Email" aria-label="Email">
                </div>
            </div>

            <div class="row">
                <div class="col my-2">
                    <input type="text" class="form-control myDecorations" placeholder="Phone" aria-label="Phone">
                </div>
                <div class=" col my-2">
                    <select id="inputState" class="form-select myDecorations">
                        <option selected>More info</option>
                        <option>...</option>
                    </select>
                </div>
            </div>

            <div class="mb-3">
                <textarea class="mySpace form-control myDecorations" id="exampleFormControlTextarea1" rows="3" placeholder="Message"></textarea>
            </div>

            <a class="my-5" href="#">SEND</a>
        </div>
        
        <div class="rightSection">
            <h4>Example Inc.</h4>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>

            <div class="divider py-3">
                <i class="contacts fa-solid fa-phone"></i>
                <span>+1 (305) 1234-5678</span>
            </div>
            

            <div class="divider py-3">
                <i class="contacts fa-solid fa-envelope"></i>
                <span>hello@example.com</span>
            </div>
            
            <div class="divider py-3">
                <i class="contacts different fa-solid fa-location-dot"></i>
                <span>Main Avenue, 987</span>
            </div>
            
            <div class="py-4">
                <a href="#">VIEW MAP</a>
            </div>
            

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
            font-size: 3rem;
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

        .mySpace {
            margin-bottom: 40px;
        }
        a {
            text-decoration: none;
            background-color: $cube-darkGreen;
            color: $cube-white;
            padding: 10px 20px;
            border-radius: 5px;

        }
        a:hover {
            background-color: $cube-mustard;
        }
    }

    .leftSection {
        width: 55%;
    }
    .rightSection {
        width: 40%;

        p {
            color: $cube-darkGray;
        }

        a {
            background-color: $cube-white;
            color: $cube-darkGreen;
            border: solid 1px $cube-darkGreen;
        }

        .contacts {
            font-size: 1.3rem;
            background-color: rgba($cube-lightGreen, $alpha: 0.5);
            padding: 15px;
            border-radius: 50%;
            margin-right: 20px;
        }

        .different {
            padding-left: 18px;
            width: 50.8px;
        }
    }

    .divider {
        color: $cube-darkGreen;

        span {
            color: $cube-darkGreen;
        }
    }
</style>

