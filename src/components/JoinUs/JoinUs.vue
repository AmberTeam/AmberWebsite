<template>
    <div class="joinus_container">
        <div class="joinus_email">
            <label>Email</label><br/>
            <input type="email" placeholder="Your email" class="joinus_email"/>
        </div>
        <div class="joinus_name">
            <label>Name</label><br/>
            <input type="text" placeholder="Your name" class="joinus_name"/>
        </div>
        <button class="joinus_button" type="submit">Join Us</button>
    </div>
</template>

<style>
    .joinus_container {
        display: grid;
        justify-content: center;
        align-items: center;
    }

    .joinus_email {
        margin-bottom: 10px;
    }

    .joinus_email input {
        padding: 10px;
        border: none;
    }

    .joinus_name input {
        padding: 10px;
        border: none;
    }

    .joinus_button {
        margin: 10px;
        padding: 10px;
        background-color: #ee724c;
        border: none;
        border-radius: 8px;
    }

    .joinus_button:hover {
        background-color: #d38871;
        transition: all 0.5s ease 0s;
    }

    .joinus_button:active {
        background-color: #ee724c;
    }
</style>