<template>
    <div class="header_container">
        <div class="header_logo">
            <img src="../../assets/logo.svg"/>
            <p>Amber</p>
        </div>
        <nav class="header_navigation">
            <ul class="header_navigation_list">
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Projects</a></li>
                <li><a href="#">Join us</a></li>
            </ul>
        </nav>
    </div>
</template>

<style>

.header_container {
    padding: 10px;
    background-color: #181818;
    display: flex;
    position: sticky; 
    align-items: center;
    justify-content: space-between;
    top: 0px;
    cursor: pointer;
}

.header_logo {
    display: flex;
    align-items: center;
}

.header_logo img {
    height: 35px;
}

.header_logo p {
    margin-left: 10px;
}

.header_navigation_list {
    display: flex;
    align-items: center;
    text-decoration: none;
}

.header_navigation_list li {
    margin-left: 30px;
    list-style: none;
}

.header_navigation_list li :hover {
    color: #ee724c;
    transition: all 0.5s ease 0s;
}

.header_navigation_list a {
    text-decoration: none;
}

</style>