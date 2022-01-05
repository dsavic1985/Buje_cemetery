<template>
    <div class="home">

        <div id="wrapper">

            <div id="header">

                <img src="" />

                <p>Buje cemetery</p>

            </div>

            <div id="menu">

                <a href="">Home</a>
                <a href="">Tour</a>
                <a href="">Gallery</a>
                <a href="">Facts</a>
                <a href="">Contact</a>

            </div>


            <div id="main"></div>

            <div id="maTe">

                <p id="we">{{ msg }}</p>

                <p id="choo">Choose your dates for the tour!</p>

            </div>

            <div id="footer">&copy; 2022 DeeS. All rights reserved</div>


        </div>
    </div>

</template>

<script>
    export default {
        name: 'Home',
        props: {
            msg: String
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    #header {
        background-color: #43263A;
        color: #FFF;
        font-size: 24px;
        text-align: right;
        padding-top: 100px;
        padding-right: 40px;
        padding-bottom: 100px;
        background-image: url(/cem_hed_.jpg);
        background-repeat: no-repeat;
        background-position: center center;
    }

    #menu {
        background-color: #C8BBCF;
        padding-top: 10px;
        padding-right: 25px;
        padding-bottom: 10px;
        text-align: right;
    }

        #menu a {
            text-decoration: none;
            color: #FFF;
            margin-right: 10px;
        }

            #menu a:hover {
                color: #43263A;
            }

    #maTe {
        text-align: center;
        margin: 0;
        width: 20%;
        position: absolute;
        top: 50%;
        left: 50%;
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }

    #footer {
        color: #666;
        font-size: 14px;
        text-align: center;
        padding-top: 8px;
        padding-bottom: 8px;
        position: fixed;
        left: 0px;
        bottom: 0px;
        width: 100%;
    }
</style>

