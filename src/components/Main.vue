<template>
    <div class="container">
        <section class="introduction-section">
            <div class="cols-section-title">
                <p>START LEARNING CODING LANGUAGES</p>
                <h1>Build Your Dream <span>TODAY</span></h1>
            </div>

            <div class="row">
                <div class="col">
                    <img src="/images/home-5-image-box-01.png" alt="">
                    <h5>Idea Discussion</h5>
                    <p>Get teamed up with the specialist who work and teach coding for years at famous universities.</p>
                    <a href="">Start now &rightarrow;</a>
                </div>
                <div class="col">
                    <img src="/images/home-5-image-box-02.png" alt="">
                    <h5>Web Development</h5>
                    <p>Learn to start building a webpage from scratch. You decide your own pace, course and speed.</p>
                    <a href="">Start now &rightarrow;</a>
                </div>
                <div class="col">
                    <img src="/images/home-5-image-box-03.png" alt="">
                    <h5>System Administration</h5>
                    <p>Learners are encouraged to study the mechanism and structure of system administration.</p>
                    <a href="">Start now &rightarrow;</a>
                </div>
                <div class="col">
                    <img src="/images/home-5-image-box-04.png" alt="">
                    <h5>Graphic Design</h5>
                    <p>Have a passion for graphic and arts? <br> Show your talents with confidence and
                        self-assertiveness. </p>
                    <a href="">Start now &rightarrow;</a>
                </div>
            </div>
        </section>

        <section class="maxcoach-section">
            <div class="row">
                <div class="col">
                    <img src="/images/about-us-03-image-01.png" alt="">
                </div>
                <div class="col">
                    <div class="big-cols-section-title">
                        <p>DREAM WITH <strong>MAXCOACH</strong></p>
                        <h1>
                            Constructor A <span>Stunning</span> <br>
                            Career Perspective
                        </h1>
                    </div>

                    <div class="card">
                        <div class="card-header">
                            Multiple Platforms Supported for Teaching & Studying
                        </div>
                        <div class="card-body">
                            <p class="card-text">MaxCoach supports the act of teaching and learning
                                on multiple platforms like online or offline via material downloads. We know
                                thing aren't supposed to be devoured in a short time, you can always access
                                our knowledge base from any device.
                            </p>
                        </div>
                    </div>

                    <div class="card mini-card">
                        <div class="card-header">
                            Multiple Course Participation at the Same Time
                        </div>
                    </div>

                    <div class="card mini-card">
                        <div class="card-header">
                            Track Study Progress & Deliver Prompt Feedback
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    data() {
        return {}
    }
}
</script>

<style lang="scss" scoped>
.introduction-section {
    padding: 0 80px;

    .cols-section-title {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 70px;

        p {
            font-size: 15px;
            color: #21AD96;
        }

        h1 {
            font-size: 40px;
            font-weight: 600;
            color: #3F3A64;

            span {
                font-weight: 200;
                font-size: 40px;
                color: #21AD96;
            }
        }
    }

    .row {

        .col {
            text-align: center;

            h5 {
                margin: 20px 0;
                font-weight: 600;
            }

            p {
                color: #696969;
                font-size: 14px;
            }

            a {
                text-decoration: none;
                color: #8D89A2;
                font-size: 13px;
                font-weight: 800;
            }
        }
    }

}

.maxcoach-section {
    padding: 0 100px;
    margin-top: 100px;

    .big-cols-section-title {

        p {
            font-size: 15px;
            color: #21AD96;
        }

        h1 {
            font-size: 40px;
            font-weight: 600;
            color: #3F3A64;

            span {
                font-weight: 200;
                font-size: 40px;
                color: #21AD96;
            }
        }

    }

    .card {
        margin-top: 50px;
        border: none;

        .card-header {
            padding: 20px;
            background-color: #21AD96;
            color: white;
            font-size: 17px;
            font-weight: 600;
        }

        .card-body {
            font-weight: 300;
            padding: 20px;
            color: #696969;
            background-color: #FFFFFF;
            border-radius: 50%;
        }
    }

    .mini-card {
        margin-top: 30px;
        border: none;

        .card-header {
            background-color: #FFFFFF;
            color: #696969;
            border: none;
            border-radius: 50%;
        }
    }
}
</style>