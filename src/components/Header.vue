<template>
    <header>
        <div class="container">
            <div class="navbar">
                <img src="/public/images/dark-logo.png" alt="">
                <ul>
                    <li>Home <font-awesome-icon :icon="['fas', 'chevron-down']" /></li>
                    <li>Pages <font-awesome-icon :icon="['fas', 'chevron-down']" /></li>
                    <li>Courses <font-awesome-icon :icon="['fas', 'chevron-down']" /></li>
                    <li>Features <font-awesome-icon :icon="['fas', 'chevron-down']" /></li>
                    <li>Blog <font-awesome-icon :icon="['fas', 'chevron-down']" /></li>
                    <li>Shop <font-awesome-icon :icon="['fas', 'chevron-down']" /></li>
                    <li><font-awesome-icon class="fs-5" :icon="['fas', 'cart-shopping']" /></li>
                    <li><font-awesome-icon class="fs-5" :icon="['far', 'circle-user']" /></li>
                </ul>
                <input type="text" placeholder="search...">
            </div>
            <div class="hero">
                <div class="text-box">
                    <h1>Complete Your <br> Dreams in JavaS <br> Programming</h1>
                    <p>Learn any coding program in distance and for a <br> reasonable fee.
                    You don't have to struggle alone, <br> you've got our assistance and help</p>
                    <button class="green-button"><font-awesome-icon :icon="['fas', 'cloud-arrow-down']" /> Download free E-book</button>
                </div>
                <div class="image">
                    <img src="/public/images/home-5-hero-image.png" alt="">
                </div>
            </div>
        </div>

        <div class="absolute-list">
            <ul>
                <li><font-awesome-icon :icon="['fas', 'ruler-combined']" /></li>
                <li><font-awesome-icon :icon="['far', 'circle-dot']" /></li>
                <li><font-awesome-icon :icon="['fas', 'book']" /></li>
                <li><font-awesome-icon :icon="['fas', 'cart-shopping']" /></li>
            </ul>
        </div>
    </header>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>

<style lang="scss" scoped>

header {
    position: relative;
    padding-bottom: 60px;
    margin-bottom: 80px;
    background-color: #EAE6E3;
    background-image: url(/public/svg/jumbo-overlay.svg);

    
    .container {
        width: 1250px;
    }
    
}

.navbar {
    padding-top: 20px ;
    align-items: center;

    img {
        width: 200px;
    }

    ul {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 35px;

        li {
            color: #3F3A64;
        }
    }

    input {
        border: none;
        border-radius: 5px;
        padding: 15px;
        outline: none;
    }
}

.hero {
    padding-top: 60px;
    display: flex;
    justify-content: center;
    gap: 105px;

    .text-box {
        display: flex;
        flex-direction: column;
        gap: 30px;
        align-self: center;

        h1 {
            color: #3F3A64;
            font-weight: 700;
            font-size: 50px;
            line-height: 65px;
        }

        p {
            color: #8D89A2;
            font-weight: 600;
            font-size: 17px;
            line-height: 30px;
        }

        .green-button {
            font-weight: 700;
            align-self: flex-start;
        }
    }

}

.absolute-list {
    position: absolute;
    bottom: 400px;
    right: 0;
    background-color: white;
    padding: 8px;
    border-radius: 3px;

    ul {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 18px;
    }
}
</style>