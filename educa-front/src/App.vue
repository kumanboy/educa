<template>
    <HeaderRow/>
    <HomeRow/>
    <FeaturesRow/>
    <CoursesRow/>
    <RegistrationRow/>
</template>

<script>

import HeaderRow from "@/components/Home/HeaderRow";
import HomeRow from "@/components/Home/HomeRow";
import FeaturesRow from "@/components/Home/FeaturesRow";
import CoursesRow from "@/components/Home/CoursesRow";
import RegistrationRow from "@/components/Home/RegistrationRow";

export default {
    name: 'App',
    components: {
        RegistrationRow,
        CoursesRow,
        FeaturesRow,
        HomeRow,
        HeaderRow

    }
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
}

/*Global tags*/

h1 {
    font-size: 2.5rem;
    font-weight: 700;
    color: rgba(35, 35, 85);
}

span {
    font-size: .9rem;
    color: #757373;
}

h6 {
    font-size: 1.1rem;
    color: rgb(24, 24, 49);
}

nav {
    position: fixed;
    width: 100%;
    background-color: #fff;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 1vw 8vw;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.15);
}

nav img {
    width: 150px;
    cursor: pointer;
}

nav .navigation ul {
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

nav .navigation ul li {
    list-style: none;
    margin-left: 30px;
}

nav .navigation ul li a {
    text-decoration: none;
    color: rgb(21, 21, 100);
    font-size: 16px;
    font-weight: 500;
    transition: 0.3s ease;
}

nav .navigation ul li a:hover {
    color: #FDC93B;
}
</style>
