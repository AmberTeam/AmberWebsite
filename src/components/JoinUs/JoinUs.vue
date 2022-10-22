<script>
  import cl from './JoinUs.module.sass'
  export default {
    data () {
      return { cl }
    }
  }
</script>

<template>
    <section id="joinus" class="pd_section" :class="cl.Joinus">
      <div :class="cl.Joinus_container">
        <svg :class="cl.Polygon_1" width="78" height="80" viewBox="0 0 28 30" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M16.6517 2.26302L23.7047 6.33506C25.3456 7.28242 26.3564 9.03323 26.3564 10.928V19.072C26.3564 20.9668 25.3456 22.7176 23.7047 23.6649L16.6517 27.737C15.0108 28.6843 12.9892 28.6843 11.3483 27.737L4.2953 23.6649C2.65442 22.7176 1.64359 20.9668 1.64359 19.072V10.928C1.64359 9.03323 2.65442 7.28242 4.2953 6.33506L11.3483 2.26302C12.9892 1.31565 15.0108 1.31565 16.6517 2.26302Z" stroke="url(#paint0_linear_26:258)" stroke-width="3"/>
          <defs>
            <linearGradient id="paint0_linear_26:258" x1="-2" y1="-1" x2="30" y2="31" gradientUnits="userSpaceOnUse">
              <stop stop-color="#ee724c"/>
              <stop offset="1" stop-color="#f5af30"/>
            </linearGradient>
          </defs>
        </svg>
        <svg :class="cl.Polygon_2" width="45" height="47" viewBox="0 0 28 30" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M16.6517 2.26302L23.7047 6.33506C25.3456 7.28242 26.3564 9.03323 26.3564 10.928V19.072C26.3564 20.9668 25.3456 22.7176 23.7047 23.6649L16.6517 27.737C15.0108 28.6843 12.9892 28.6843 11.3483 27.737L4.2953 23.6649C2.65442 22.7176 1.64359 20.9668 1.64359 19.072V10.928C1.64359 9.03323 2.65442 7.28242 4.2953 6.33506L11.3483 2.26302C12.9892 1.31565 15.0108 1.31565 16.6517 2.26302Z" stroke="url(#paint0_linear_26:258)" stroke-width="3"/>
          <defs>
            <linearGradient id="paint0_linear_26:258" x1="-2" y1="-1" x2="30" y2="31" gradientUnits="userSpaceOnUse">
              <stop stop-color="#ee724c"/>
              <stop offset="1" stop-color="#f5af30"/>
            </linearGradient>
          </defs>
        </svg>
        <div :class="cl.Joinus_header">
          <h1> Join Us </h1>
        </div>
        <div :class="cl.Joinus_content">
          <div :class="cl.Joinus_form">
            <input :class="cl.Email" class="styled_inp" name="email" placeholder="Enter your email"/>
            <label class="inp_lab" for="email"></label>
            <input :class="cl.Name" class="styled_inp" name="name" placeholder="Enter your name"/>
            <label class="inp_lab" for="name"></label>
            <button class="styled_btn"> Send </button>
          </div>
        </div>
      </div>
    </section>
</template>