<script>
export default {
    name: "TheHeader",
}

</script>

<template>
<div class="container-fluid myBg">
    <div class="container d-flex justify-content-between align-items-center">
        <div class="hours">
            <i class="fa-solid fa-clock"></i>
            <span class="px-1">Open Hours Mon - Sat - 9:00 - 18:00</span>
        </div>

        <div class="contacts d-flex align-items-cente">
            <div class="phone">
                <i class="fa-solid fa-phone"></i>
                <span>+1 (305) 1234-5678</span>
            </div>
            
            <div class="email">
                <i class="fa-solid fa-envelope"></i>
                <span>hello@example.com</span>
            </div>
            
            <div class="iconsGroup">
                <i class="myIcons fa-brands fa-facebook-f"></i>
                <i class="myIcons fa-brands fa-twitter"></i>
                <i class="myIcons fa-brands fa-linkedin-in"></i>
            </div>
            
        </div>
    </div>
</div>


</template>

<style scoped lang="scss">
    @import "../styles/general.scss";
    .myBg {
        background-color: $header-test;

        .hours, .contacts {
            color: $cube-lightGray;
        }

        .contacts {
            display: flex;

            .phone, .email, .myIcons  {
                padding: 0 30px;
                span {
                    padding: 5px;
                }
            }
            .iconsGroup, .phone, .email {
                padding: 20px;
            }
            
        }
        
    }
</style>