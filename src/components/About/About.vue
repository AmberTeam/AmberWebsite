<script>
  import cl from './About.module.sass'
  export default {
    data () {
      return { cl }
    }
  }
</script>

<template>
	<section id="home" class="pd_section" :class="cl.About_welkome">
		<div :class="cl.Polygon_container">
			<svg :class="cl.Polygon_1" width="88" height="88" viewBox="0 0 88 88" fill="none" xmlns="http://www.w3.org/2000/svg">
			  <path id="base" d="M50.1538 7.01703L72.9513 20.1791C76.7593 22.3777 79.1051 26.4408 79.1051 30.8379V57.1621C79.1051 61.5592 76.7593 65.6223 72.9513 67.8209L50.1538 80.983C46.3458 83.1815 41.6542 83.1815 37.8462 80.983L15.0487 67.8209C11.2407 65.6223 8.89488 61.5592 8.89488 57.1621V30.8379C8.89488 26.4408 11.2407 22.3777 15.0487 20.1791L37.8462 7.01703C41.6542 4.81847 46.3458 4.81847 50.1538 7.01703Z" stroke="#000" stroke-width="6"/>
			  <defs>
			  	<linearGradient id="paint0_linear_30:200" x1="0" y1="0" x2="88" y2="88" gradientUnits="userSpaceOnUse">
			  		<stop stop-color="#000"/>
			  		<stop offset="0.760417" stop-color="#000"/>
			  	</linearGradient>
			  </defs>
			</svg>
			<svg :class="cl.Polygon_2" width="81" height="81" viewBox="0 0 81 81" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path id="base" d="M46.7692 7.82464L66.1025 18.9867C69.9105 21.1853 72.2564 25.2484 72.2564 29.6455V51.9697C72.2564 56.3668 69.9105 60.4299 66.1025 62.6285L46.7692 73.7906C42.9612 75.9892 38.2695 75.9892 34.4615 73.7906L15.1282 62.6285C11.3202 60.4299 8.97434 56.3668 8.97434 51.9697V29.6455C8.97434 25.2484 11.3202 21.1853 15.1282 18.9867L34.4615 7.82464C38.2695 5.62609 42.9612 5.62609 46.7692 7.82464Z" stroke="#000" stroke-width="6"/>
				<defs>
					<linearGradient id="paint0_linear_30:202" x1="0.615356" y1="0.807617" x2="80.6154" y2="80.8076" gradientUnits="userSpaceOnUse">
						<stop stop-color="#000"/>
						<stop offset="0.760417" stop-color="#000"/>
					</linearGradient>
				</defs>
			</svg>
			<svg :class="cl.Polygon_3" width="72" height="72" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path id="base" d="M42.1538 7.01703L58.0231 16.1791C61.8311 18.3777 64.1769 22.4408 64.1769 26.8379V45.1621C64.1769 49.5592 61.8311 53.6223 58.0231 55.8209L42.1538 64.983C38.3458 67.1815 33.6542 67.1815 29.8462 64.983L13.9769 55.8209C10.1689 53.6223 7.82309 49.5592 7.82309 45.1621V26.8379C7.82309 22.4408 10.1689 18.3777 13.9769 16.1791L29.8462 7.01703C33.6542 4.81847 38.3458 4.81847 42.1538 7.01703Z" stroke="#000" stroke-width="6"/>
				<defs>
					<linearGradient x1="0" y1="0" x2="72" y2="72" gradientUnits="userSpaceOnUse">
						<stop stop-color="#000"/>
						<stop offset="0.760417" stop-color="#000"/>
					</linearGradient>
				</defs>
			</svg>
			<svg :class="cl.Polygon_4" width="18" height="20" viewBox="0 0 18 20" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M10.25 2.45374L14.9103 5.14434C15.6838 5.59092 16.1603 6.41624 16.1603 7.3094V12.6906C16.1603 13.5838 15.6838 14.4091 14.9103 14.8557L10.25 17.5463C9.4765 17.9928 8.5235 17.9928 7.75 17.5463L3.08975 14.8557C2.31624 14.4091 1.83975 13.5838 1.83975 12.6906V7.3094C1.83975 6.41624 2.31624 5.59092 3.08975 5.14434L7.75 2.45374C8.5235 2.00716 9.4765 2.00716 10.25 2.45374Z" stroke="url(#paint0_linear_26:260)" stroke-width="3"/>
				<defs>
					<linearGradient id="paint0_linear_26:260" x1="-1" y1="0" x2="19" y2="20" gradientUnits="userSpaceOnUse">
						<stop stop-color="#ee724c"/>
						<stop offset="1" stop-color="#f5af30"/>
					</linearGradient>
				</defs>
			</svg>
			<svg :class="cl.Polygon_5" width="32" height="34" viewBox="0 0 32 34" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M18.4017 2.69603L27.1867 7.76807C28.6729 8.62612 29.5885 10.2119 29.5885 11.928V22.072C29.5885 23.7881 28.6729 25.3739 27.1867 26.2319L18.4017 31.304C16.9155 32.162 15.0845 32.162 13.5983 31.304L4.81325 26.2319C3.32707 25.3739 2.41154 23.7881 2.41154 22.072V11.928C2.41154 10.2119 3.32707 8.62612 4.81325 7.76807L13.5983 2.69603C15.0845 1.83798 16.9155 1.83798 18.4017 2.69603Z" stroke="url(#paint0_linear_26:257)" stroke-width="4"/>
				<defs>
					<linearGradient id="paint0_linear_26:257" x1="-2" y1="-1" x2="34" y2="35" gradientUnits="userSpaceOnUse">
						<stop stop-color="#ee724c"/>
						<stop offset="1" stop-color="#f5af30"/>
					</linearGradient>
				</defs>
			</svg>
			<svg :class="cl.Polygon_6" width="20" height="22" viewBox="0 0 20 22" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M11.25 2.45374L16.7763 5.64434C17.5498 6.09092 18.0263 6.91624 18.0263 7.8094V14.1906C18.0263 15.0838 17.5498 15.9091 16.7763 16.3557L11.25 19.5463C10.4765 19.9928 9.5235 19.9928 8.75 19.5463L3.22372 16.3557C2.45022 15.9091 1.97372 15.0838 1.97372 14.1906V7.8094C1.97372 6.91624 2.45022 6.09092 3.22372 5.64434L8.75 2.45374C9.5235 2.00716 10.4765 2.00716 11.25 2.45374Z" stroke="url(#paint0_linear_26:259)" stroke-width="3"/>
				<defs>
					<linearGradient id="paint0_linear_26:259" x1="-1" y1="0" x2="21" y2="22" gradientUnits="userSpaceOnUse">
						<stop stop-color="#ee724c"/>
						<stop offset="1" stop-color="#f5af30"/>
					</linearGradient>
				</defs>
			</svg>
			<svg :class="cl.Polygon_7" width="28" height="30" viewBox="0 0 28 30" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M16.6517 2.26302L23.7047 6.33506C25.3456 7.28242 26.3564 9.03323 26.3564 10.928V19.072C26.3564 20.9668 25.3456 22.7176 23.7047 23.6649L16.6517 27.737C15.0108 28.6843 12.9892 28.6843 11.3483 27.737L4.2953 23.6649C2.65442 22.7176 1.64359 20.9668 1.64359 19.072V10.928C1.64359 9.03323 2.65442 7.28242 4.2953 6.33506L11.3483 2.26302C12.9892 1.31565 15.0108 1.31565 16.6517 2.26302Z" stroke="url(#paint0_linear_26:258)" stroke-width="3"/>
				<defs>
					<linearGradient id="paint0_linear_26:258" x1="-2" y1="-1" x2="30" y2="31" gradientUnits="userSpaceOnUse">
						<stop stop-color="#ee724c"/>
						<stop offset="1" stop-color="#f5af30"/>
					</linearGradient>
				</defs>
			</svg>
		</div>
		<div :class="cl.About_container">
			<div :class="cl.About_header">
				<h1> Amber Team </h1>
			</div>
			<button class="btn_def styled_btn">
				Our Projects
			</button> 
		</div>	
	</section>
	<section id="about" class="pd_section" :class="cl.About_desc_container">
		<div :class="cl.About_description">
			<p> Amber Team - This is a young open source development team looking for partners to create something new. The one that will change the world </p>
			<button class="styled_btn"> Join Us </button>
		</div>	
	</section>
</template>