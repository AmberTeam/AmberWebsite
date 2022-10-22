<script>
  import cl from './Team.module.sass'
  export default {
    data () {
      return { cl }
    }
  }
</script>


<template>
	<section id="team" class="pd_section" :class="cl.Team">
		<div :class="cl.Team_container">
			<div :class="cl.Team_header">
				<h1> The Team </h1>
			</div>
			<div :class="cl.Team_content">
				<div :class="cl.Team_description">
					Amber Team was created by two friends, that decided to create something new
				</div>
				<div :class="cl.Team_members">
					<div :class="[cl.Member, cl.Member_1]">
						<div :class="cl.Member_description">
							<div :class="cl.Member_info">
								<div :class="cl.Member_nickname">
									uaquax
								</div>
								<div :class="cl.Member_desc">
									Team leader, back-end dev, rust dev
								</div>
							</div>
							<div :class="cl.Member_soc">
								<div :class="cl.Soc">
									<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
									<span>	 
										uaquax
									</span>
								</div>
							</div>
							<svg :class="cl.Polygon_1" width="46" height="48" viewBox="0 0 28 30" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M16.6517 2.26302L23.7047 6.33506C25.3456 7.28242 26.3564 9.03323 26.3564 10.928V19.072C26.3564 20.9668 25.3456 22.7176 23.7047 23.6649L16.6517 27.737C15.0108 28.6843 12.9892 28.6843 11.3483 27.737L4.2953 23.6649C2.65442 22.7176 1.64359 20.9668 1.64359 19.072V10.928C1.64359 9.03323 2.65442 7.28242 4.2953 6.33506L11.3483 2.26302C12.9892 1.31565 15.0108 1.31565 16.6517 2.26302Z" stroke="url(#paint0_linear_26:258)" stroke-width="3"/>
								<defs>
									<linearGradient id="paint0_linear_26:258" x1="-2" y1="-1" x2="30" y2="31" gradientUnits="userSpaceOnUse">
										<stop stop-color="#ee724c"/>
										<stop offset="1" stop-color="#f5af30"/>
									</linearGradient>
								</defs>
							</svg>
						</div>
						<div :class="cl.Member_picture">
							<img draggable="false" src="../../assets/uaquax_pic.jpg"/>
						</div>
					</div>
					<div :class="[cl.Member, cl.Member_2]">
						<div :class="cl.Member_description">
							<div :class="cl.Member_info">
								<div :class="cl.Member_nickname">
									uorbius
								</div>
								<div :class="cl.Member_desc">
									Fullstack web dev, c++ dev
								</div>
							</div>
							<div :class="cl.Member_soc">
								<div :class="cl.Soc">
									<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
									<span>	 
										uorbius
									</span>
								</div>
							</div>
						</div>
						<svg :class="cl.Polygon_2" width="60" height="62" viewBox="0 0 28 30" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path d="M16.6517 2.26302L23.7047 6.33506C25.3456 7.28242 26.3564 9.03323 26.3564 10.928V19.072C26.3564 20.9668 25.3456 22.7176 23.7047 23.6649L16.6517 27.737C15.0108 28.6843 12.9892 28.6843 11.3483 27.737L4.2953 23.6649C2.65442 22.7176 1.64359 20.9668 1.64359 19.072V10.928C1.64359 9.03323 2.65442 7.28242 4.2953 6.33506L11.3483 2.26302C12.9892 1.31565 15.0108 1.31565 16.6517 2.26302Z" stroke="url(#paint0_linear_26:258)" stroke-width="3"/>
							<defs>
								<linearGradient id="paint0_linear_26:258" x1="-2" y1="-1" x2="30" y2="31" gradientUnits="userSpaceOnUse">
									<stop stop-color="#ee724c"/>
									<stop offset="1" stop-color="#f5af30"/>
								</linearGradient>
							</defs>
						</svg>
						<div :class="cl.Member_picture">
							<img draggable="false" src="../../assets/uorbius_pic.jpg"/>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>