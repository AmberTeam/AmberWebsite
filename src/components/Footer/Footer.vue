<template>
    <div class="footer_container">
        <div class="footer_logo">
            <img src="../../assets/logo.svg"/>
            <p>Amber</p>
        </div>
        <div class="footer_information">
            <p>uaquax</p>
            <p>uorbius</p>
        </div>
    </div>
</template>

<style>

.footer_container {
    width: 100%;
    bottom: 0;
    padding: 10px;
    background-color: #181818;
    display: flex;
    position: fixed; 
    align-items: center;
    justify-content: space-between;
    cursor: pointer;
}

.footer_logo {
    display: flex;
    align-items: center;
}

.footer_logo img {
    height: 35px;
}

.footer_logo p {
    margin-left: 10px;
}

.footer_information {
    margin-left: auto;
    margin-right: 20px;
}

.footer_information p:hover {
    color:#ee724c;
    transition: all 0.5s ease 0s;
}


</style>