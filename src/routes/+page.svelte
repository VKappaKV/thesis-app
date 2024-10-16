<script>
	import Hero from './hero.svelte';
</script>

<Hero />

<main class="max-w-2xl mx-auto p-6 bg-white rounded-lg shadow-lg mt-8">
	<h1 class="text-3xl font-bold text-gray-900 mb-4">CODELAB: Algorand Thesis Program</h1>
	<section class="mb-6">
		<p class="text-gray-700 leading-relaxed mb-4">
			The University of Milan, through its student association CODELAB and
			<a href="https://algorand.co/" class="text-blue-500 underline hover:text-blue-600"
				>Algorand Foundation</a
			>, is offering an internship program aimed at consolidating students’ efforts during their
			final semester. This initiative is a collaborative effort with the university, allowing
			Computer Science students to delve deeper into Algorand technology and produce tangible
			outcomes. During this internship, participants will engage in various activities, including
			creating innovative projects and conducting research.
		</p>
		<p class="text-gray-700 leading-relaxed">
			The work produced will be published under your authorship, contributing valuable knowledge to
			the community. Additionally, all participating students will be awarded a special certificate
			from the Algorand Foundation for their contributions. This program enhances practical skills
			and theoretical understanding, bridging academic learning with real-world application.
		</p>
	</section>
	<section class="mb-6">
		<p class="text-gray-700 leading-relaxed">
			Algorand is an energy-efficient, quantum-secure, single-layer blockchain, with instant
			finality, consistently high throughput, and low fees.
		</p>
	</section>
	<section>
		<h2 class="text-2xl font-semibold text-gray-900 mb-3">WHAT WILL YOU LEARN</h2>
		<p class="text-gray-700 leading-relaxed mb-4">
			The project aims to create or contribute to a development initiative, allowing students from
			the University of Milan to learn about Algorand and develop a sustainable project.
			Collaborating closely with different professionals from the Algorand Foundation, students will
			engage in meaningful discussions to identify and select the project. This project will be
			developed within Codelab and will involve:
		</p>
		<ul class="list-disc list-inside text-gray-700 space-y-2">
			<li>Learning about decentralized technology</li>
			<li>Integrating with an existing codebase</li>
			<li>Code development and thesis formation</li>
			<li>Improving technical documentation</li>
		</ul>
	</section>
</main>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}
</style>
