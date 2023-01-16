<template>
    <section id="features">
        <h1>Awesome Features</h1>
        <p>Replenish man have thing gathering light yielding shall you</p>
        <div class="fea-base">
            <div class="fea-box">
                <i class="fa-solid fa-graduation-cap"></i>
                <h3>Scholarship Facility</h3>
                <p>One make creepeth, man bearing theira firmament won't great heaven</p>
            </div>
            <div class="fea-box">
                <i class="fa-solid fa-pen"></i>
                <h3>Global Certification</h3>
                <p>One make creepeth, man bearing theira firmament won't great heaven</p>
            </div>
            <div class="fea-box">
                <i class="fa-solid fa-award"></i>
                <h3>Global Certification</h3>
                <p>One make creepeth, man bearing theira firmament won't great heaven</p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "FeaturesRow"
}
</script>

<style scoped>
#features {
    padding: 5vw 8vw 0 8vw;
    text-align: center;
}

#features .fea-base{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    grid-gap: 1rem;
    margin-top: 50px;
}

#features .fea-box {
    background-color: #ffffff;
    text-align: start;
}

#features .fea-box i {
    font-size: 2.3rem;
    color: rgb(44, 44, 80);
}

#features .fea-box h3 {
    font-size: 1.2rem;
    font-weight: 600;
    color: rgb(46, 46, 59);
    padding: 13px 0 7px 0;
}

#features .fea-box p {
    font-size: 1rem;
    font-weight: 400;
    color: rgb(70, 70, 87);
}
</style>