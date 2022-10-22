<script>
    import { store } from '../../assets/store.js'
    import cl from './Header.module.sass'
    export default {
        data () {
            return { cl, store }
        }
    }
</script>

<template>
    <header :class="cl.Header_container">
        <div :class="cl.Logo_container">
            <img src="../../assets/logo.svg"/>
            <p>Amber</p>
        </div>
        <nav :class="cl.Header_navigation">
            <button @click="store.nav_active = true" :class="[cl.Hamburger_btn, store.nav_active ? cl.Active : '']">
                <span :class="[cl.Line, cl.Line_1]"></span>
                <span :class="[cl.Line, cl.Line_2]"></span>
                <span :class="[cl.Line, cl.Line_3]"></span>
            </button>
            <div :class="[cl.Navigation_list, store.nav_active ? cl.Mobile_active : '']">
                <div :class="cl.Mobile_header">
                    <div :class="cl.Logo">
                        <img src="../../assets/logo.svg"/>
                        <p>Amber</p>
                    </div>
                    <div :class="cl.Close">
                        <button @click="store.nav_active = false" :class="[cl.Hamburger_btn, store.nav_active ? cl.Active : '']">
                            <span :class="[cl.Line, cl.Line_1]"></span>
                            <span :class="[cl.Line, cl.Line_2]"></span>
                            <span :class="[cl.Line, cl.Line_3]"></span>
                        </button>
                    </div>
                </div>
                <a :class="cl.Navigation_a" href="#home">Home</a>
                <a :class="cl.Navigation_a" href="#about">About</a>
                <a :class="cl.Navigation_a" href="#projects">Projects</a>
                <a :class="cl.Navigation_a" href="#team">Team</a>
                <a :class="cl.Navigation_a" href="#joinus">Join Us</a>
            </div>
        </nav>
    </header>
</template>