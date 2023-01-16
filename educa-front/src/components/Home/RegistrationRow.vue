<template>
    <section id="registration">
        <div class="reminder">
            <p>Get 100 Online Courses for Free</p>
            <h1>Register to Get It</h1>
            <div class="time">
                <div class="data">
                    18 <br> Days
                </div>
                <div class="data">
                    23<br> Hours
                </div>
                <div class="data">
                    06<br> Minutes
                </div>
                <div class="data">
                    58 <br> Seconds
                </div>
            </div>
        </div>


        <div class="form">
            <h3>Create Free Account</h3>
            <input type="text" placeholder="Name" name="" id="">
            <input type="email" placeholder="Email Address" name="" id="">
            <input type="tel" placeholder="Phone Number" name="" id="">
            <div class="btn">
                <a class="yellow" href="#">Submit Form</a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "RegistrationRow"
}
</script>

<style scoped>
#registration {
    padding: 6vw 8vw 6vw 8vw;
    background-image: linear-gradient(rgba(99, 112, 168, 0.5), rgba(81, 91, 233, 0.5)), url("@/images/signup.jpg");
    width: 100%;
    height: 100%;
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

#registration .reminder {
    color: #ffffff;
}

#registration .reminder h1 {
    color: #ffffff;
}

#registration .reminder .time {
    display: flex;
    margin-top: 40px;
}

#registration .reminder .time .data {
    text-align: center;
    padding: 13px 33px;
    background: rgba(255, 255, 255, 0.25);
    backdrop-filter: blur(4px);
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    border-radius: 10px;
    margin: 0 5px 10px 5px;
    border: 1px solid rgba(255, 255, 255, 0.18);
    font-size: 1.1rem;
    font-weight: 600;
}

#registration .form {
    background: #ffffff;
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    padding: 70px;
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
}
#registration .form input{
    margin: 15px 0;
    padding: 15px 30px;
    border: 1px solid rgb(84,40,241);
    outline: none;
}
#registration .form input::placeholder{
    color: #413c3c;
    font-weight: 500;
    font-size: 0.9rem;
}
#registration .form .btn{
    margin-top:20px ;
}
#registration .form a.yellow{
    color: #ffffff;
    background-color: #FDC93B;
    transition: 0.3s ease;
    text-decoration: none;
    font-size: 0.9rem;
    padding: 13px 35px;
    font-weight: 600;
    border-radius: 5px;
}

#registration .form .btn a.yellow:hover{
    color: rgb(21,21,100);
    background-color: #ffffff;
}
</style>