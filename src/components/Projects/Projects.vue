<script>
  import cl from './Projects.module.sass'
  export default {
    data () {
      return { cl }
    }
  }
</script>


<template>
	<section id="projects" class="pd_section">
		<div :class="cl.Projects_container">
			<div :class="cl.Projects_header">
				<h1> Our Projects & Plans </h1>
			</div>
			<div :class="cl.Projects_content">
				<div :class="[cl.Column, cl.Column_1]">
					<svg :class="cl.Polygon_1" width="60" height="62" viewBox="0 0 28 30" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path d="M16.6517 2.26302L23.7047 6.33506C25.3456 7.28242 26.3564 9.03323 26.3564 10.928V19.072C26.3564 20.9668 25.3456 22.7176 23.7047 23.6649L16.6517 27.737C15.0108 28.6843 12.9892 28.6843 11.3483 27.737L4.2953 23.6649C2.65442 22.7176 1.64359 20.9668 1.64359 19.072V10.928C1.64359 9.03323 2.65442 7.28242 4.2953 6.33506L11.3483 2.26302C12.9892 1.31565 15.0108 1.31565 16.6517 2.26302Z" stroke="url(#paint0_linear_26:258)" stroke-width="3"/>
						<defs>
							<linearGradient id="paint0_linear_26:258" x1="-2" y1="-1" x2="30" y2="31" gradientUnits="userSpaceOnUse">
								<stop stop-color="#ee724c"/>
								<stop offset="1" stop-color="#f5af30"/>
							</linearGradient>
						</defs>
					</svg>
					<div :class="[cl.Project, cl.Project_1]">
						<div :class="cl.Perks">
							<div :class="cl.Perk">
								<span :class="cl.Perk_span"></span>
								<span :class="cl.Perk_description"> Open source </span>
							</div>
							<div :class="cl.Perk">
								<span :class="cl.Perk_span"></span>
								<span :class="cl.Perk_description"> In developing </span>
							</div>
						</div>
						<div :class="cl.Content">
							<div :class="cl.Title"> 
								Rock
								<span :class="cl.Separator"></span>
							</div>
							<div :class="cl.Description">
								Analogue of Git.
							</div>
						</div>
					</div>
				</div>
				<div :class="[cl.Column, cl.Column_2]">
					<svg :class="cl.Polygon_2" width="60" height="62" viewBox="0 0 28 30" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path d="M16.6517 2.26302L23.7047 6.33506C25.3456 7.28242 26.3564 9.03323 26.3564 10.928V19.072C26.3564 20.9668 25.3456 22.7176 23.7047 23.6649L16.6517 27.737C15.0108 28.6843 12.9892 28.6843 11.3483 27.737L4.2953 23.6649C2.65442 22.7176 1.64359 20.9668 1.64359 19.072V10.928C1.64359 9.03323 2.65442 7.28242 4.2953 6.33506L11.3483 2.26302C12.9892 1.31565 15.0108 1.31565 16.6517 2.26302Z" stroke="url(#paint0_linear_26:258)" stroke-width="3"/>
						<defs>
							<linearGradient id="paint0_linear_26:258" x1="-2" y1="-1" x2="30" y2="31" gradientUnits="userSpaceOnUse">
								<stop stop-color="#f5af30"/> 
								<stop offset="1" stop-color="#f7be57"/>
							</linearGradient>
						</defs>
					</svg>
					<div :class="[cl.Project, cl.Project_2]">
						<div :class="cl.Perks">
							<div :class="cl.Perk">
								<span :class="cl.Perk_span"></span>
								<span :class="cl.Perk_description"> Open source </span>
							</div>
							<div :class="cl.Perk">
								<span :class="cl.Perk_span"></span>
								<span :class="cl.Perk_description"> Have created </span>
							</div>
							<div :class="cl.Perk">
								<span :class="cl.Perk_span"></span>
								<span :class="cl.Perk_description"> Multi-platformed </span>
							</div>
						</div>
						<div :class="cl.Content">
							<div :class="cl.Title">
								Tce Mandarin
								<span :class="cl.Separator"></span>
							</div>
							<div :class="cl.Description">
								Chinese Consulting Platform written in React & mobx
							</div>
						</div>
					</div>
					<div :class="[cl.Project, cl.Project_3]">
						<div :class="cl.Perks">
							<div :class="cl.Perk">
								<span :class="cl.Perk_span"></span>
								<span :class="cl.Perk_description"> Open source </span>
							</div>
							<div :class="cl.Perk">
								<span :class="cl.Perk_span"></span>
								<span :class="cl.Perk_description"> In developing </span>
							</div>
						</div>
						<div :class="cl.Content">
							<div :class="cl.Title">
								Caloid
								<span :class="cl.Separator"></span>
							</div>
							<div :class="cl.Description">
								Voip application designed to improve the quality of p2p calls
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>