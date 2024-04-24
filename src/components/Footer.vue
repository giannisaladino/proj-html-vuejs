<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <ul>
                        <li>
                            <h4>Address</h4>
                        </li>
                        <li>382 NE 191st St # 87394 Miami, FL 33179-3899</li>
                        <li>+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)</li>
                        <li>support@maxcoach.com</li>
                    </ul>

                    <ul class="socials">
                        <li><font-awesome-icon :icon="['fab', 'square-facebook']" /></li>
                        <li><font-awesome-icon :icon="['fab', 'twitter']" /></li>
                        <li><font-awesome-icon :icon="['fab', 'instagram']" /></li>
                        <li><font-awesome-icon :icon="['fab', 'linkedin']" /></li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li>
                            <h4>Explore</h4>
                        </li>
                        <li>Start here</li>
                        <li>Blog</li>
                        <li>About us</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li>
                            <h4><br></h4>
                        </li>
                        <li>Success story</li>
                        <li>Courses</li>
                        <li>Contact us</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li>
                            <h4>Information</h4>
                        </li>
                        <li>Membership</li>
                        <li>Purchase guide</li>
                        <li>Privacy policy</li>
                        <li>Terms of services</li>
                    </ul>
                </div>

                <div class="copy">
                    <p>2020 Maxcoach. All Rights Reserved</p>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    data() {
        return {}
    }
}
</script>

<style lang="scss" scoped>
footer {
    background-color: #FFFFFF;
    padding-top: 35px;
    padding-bottom: 10px;

    .container {
        width: 1200px;
    }
    
    ul {
        display: flex;
        flex-direction: column;
        gap: 20px;

        li {
            color: #696969;
            font-size: 15px;
            font-weight: 300;

            h4 {
                color: black;
                font-size: 20px;
                font-weight: 600;
            }
        }
    }

    .socials {
        margin-top: 30px;
        flex-direction: row;

        li {
            font-size: 25px;
        }
    }

    .copy {
        color: #9c9696;
        text-align: center;
        margin-top: 50px;
        font-size: 13px;
        font-weight: 500;
    }
}
</style>