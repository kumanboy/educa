<template>
    <section id="courses">
        <h1>Our Popular Courses</h1>
        <p>Replenish man have thing gathering light yielding shall you</p>
        <div class="course-box">
            <div class="courses">
                <img src="@/images/c1.jpg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
            <div class="courses">
                <img src="@/images/c1.jpg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
            <div class="courses">
                <img src="@/images/c2.jpg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
            <div class="courses">
                <img src="@/images/c3.jpg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
            <div class="courses">
                <img src="@/images/c4.jpg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
            <div class="courses">
                <img src="@/images/c5.jpg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
            <div class="courses">
                <img src="@/images/c6.jpg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
            <div class="courses">
                <img src="@/images/c7.jpeg" alt="c1">
                <div class="details">
                    <span>Updated 21/8/21</span>
                    <h3>Javascript Beginners Course</h3>
                    <div class="star">
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <span>(234)</span>
                    </div>
                </div>
                <div class="cost">
                    $49.99
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "CoursesRow"
}
</script>

<style scoped>
#courses{
    padding: 8vw 8vw 0 8vw;
    text-align: center;
}
#courses .courses{
    text-align: start;
    background-color: #f9f9ff;
    height: 100%;
    position: relative;
}
#courses .courses img{
    border-radius: 5px;
    width: 100%;
    height: 60%;
    background-size: cover;
    background-position: center;
}
#courses .courses .details{
    padding: 15px 15px 0 15px;
}
#courses .courses .details i{
    color: #FDC93B;
    font-size: .9rem;
}
#courses .course-box{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    grid-gap: 1rem;
    margin-top: 50px;
}
#courses .courses .cost{
    background-color: rgb(74,74,136);
    color: #ffffff;
    line-height: 70px;
    width: 70px;
    height: 70px;
    text-align: center;
    border-radius: 50%;
    position: absolute;
    right: 15px;
    bottom: 100px;
}
</style>