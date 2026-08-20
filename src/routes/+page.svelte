<script lang="ts">
	import '@fontsource-variable/rubik';
	import '@fontsource-variable/roboto-slab';

	import profile from '$lib/assets/profile.jpg';
</script>

<header>
	<div>
		<h1>Johan Schuijt</h1>
		<p>Makes machines empower humans. Experienced systems-thinker.</p>
		<address>
			Wollbell 22<br />
			6094 Axams<br />
			<a href="tel:+31651952461">+31651952461</a><br />
			<a href="mailto:johan@resolve.works">johan@resolve.works</a>
		</address>
	</div>

	<img src={profile} alt="profile" />
</header>

<h2>Experience</h2>

<section>
	<h3><strong>OpenSanctions</strong>, Berlin — <i>Data Developer</i></h3>
	<p class="year">2025 - Present</p>
	<p>
		Builing tooling to extract data on politicians from Wikipedia and the wider web, with the goal
		of enriching Wikidata.
	</p>
</section>

<section>
	<h3><strong>Follow the Money</strong>, Amsterdam — <i>Full Stack Developer</i></h3>
	<p class="year">2021 - 2025</p>
	<p>
		Responsible for the data infrastructure of a investigative journalism platform. Built
		data-pipelines and tools, like a RAG application for PDF files.
	</p>
</section>

<section>
	<h3><strong>Forest.host</strong>, Utrecht — <i>Founder</i></h3>
	<p class="year">2017 - 2021</p>
	<p>
		Responsible for the infrastructure and backend for a "zero-config" CI/CD hosting company.
		Responsible for a production cluster that served as the CI/CD platform for web development
		agencies.
	</p>
</section>

<section>
	<h3><strong>Freelance</strong>, Utrecht — <i>Full Stack Developer</i></h3>
	<p class="year">2014 - 2017</p>
	<p>
		Project based freelancer in the capacity of developer or both developer and UI/UX designer.
		Developed custom administration systems, APIs and websites.
	</p>
</section>

<section>
	<h3><strong>1200WD</strong>, Amsterdam — <i>Front-end Developer</i></h3>
	<p class="year">2012 - 2014</p>
	<p>UI design and front-end development of e-commerce websites.</p>
</section>

<h2>Skills</h2>

<section>
	<h3><strong>Programming</strong></h3>
	<p>
		I have kept up to date with modern development practices throughout my career. I'm well-informed
		and like to experiment with new technologies. I use language models extensively.
	</p>

	<table>
		<thead>
			<tr>
				<th>Language</th>
				<th>Years</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Typescript/Javascript</td>
				<td>15+</td>
			</tr>
			<tr>
				<td>HTML/CSS</td>
				<td>15+</td>
			</tr>
			<tr>
				<td>PHP</td>
				<td>10+</td>
			</tr>
			<tr>
				<td>Python</td>
				<td>10+</td>
			</tr>
			<tr>
				<td>YAML</td>
				<td>10+</td>
			</tr>
			<tr>
				<td>SQL</td>
				<td>10+</td>
			</tr>
			<tr>
				<td>Rust</td>
				<td>2</td>
			</tr>
			<tr>
				<td>Ruby</td>
				<td>1</td>
			</tr>
		</tbody>
	</table>
</section>

<section>
	<h3><strong>Tools</strong></h3>
	<p>
		GNU/Linux, Vim, Git, Docker/Compose, Kubernetes, PostgreSQL, Mysql/MariaDB,
		ElasticSearch/OpenSearch, Neo4J, RabbitMQ, Svelte, React, Ansible, Terraform, Ollama, vLLM.
	</p>
</section>

<section>
	<h3><strong>Communication</strong></h3>
	<p>
		Being self-taught also taught me to communicate with anyone, whether technical or not. I can
		translate complex technical topics to layman's terms, and enjoy helping people understand the
		problems they face, after which we can solve them together.
	</p>
</section>

<section>
	<h3><strong>Languages</strong></h3>
	<p>English, Dutch, German.</p>
</section>

<h2>Education</h2>
<p>
	I am a college drop-out that has been programming since childhood. Where school was not
	challenging, understanding the computer was. I learned to keep learning and am continuously
	adapting to the changing landscape.
</p>

<section>
	<h3><strong>Hogeschool Utrecht</strong>, Utrecht — <i>Media Technology</i></h3>
	<p class="year">2010 - 2011</p>
	<p>Followed several classes. Stopped before completion.</p>
</section>

<section>
	<h3><strong>Hogeschool van Amsterdam</strong>, Amsterdam — <i>Game Development</i></h3>
	<p class="year">2009 - 2010</p>
	<p>Followed several classes. Stopped before completion.</p>
</section>

<h2>Projects</h2>

<section>
	<h3><strong>LLMs</strong> — <i>Wow it can do what?</i></h3>
	<p class="year">2023 - now</p>
	<p>
		Built a plethora of LLM based tools through agentic coding. For example to filter incoming
		newsletters, automatically creating cold emails for a list of NGOs, or allowing me to
		voice-control my sampler.
	</p>
</section>

<section>
	<h3><strong>Insight</strong> — <i>RAG for researchers</i></h3>
	<p class="year">2023 - 2025</p>
	<p>
		During my time at Follow the Money I've built a open-source RAG system for researchers. This
		system is set-up to help researchers make sense of huge amounts of documents.
	</p>
</section>

<section>
	<h3><strong>Drum Machine</strong> — <i>MIDI step sequencer</i></h3>
	<p class="year">2019 - 2020</p>
	<p>
		Built a 16 channel MIDI step sequencer for the AKAI APC40 & APC20 controllers. Developed in Rust
		on the JACK audio stack.
	</p>
</section>

<section>
	<h3><strong>Crypto Miner</strong> — <i>Litecoin GPU miner </i></h3>
	<p class="year">2013</p>
	<p>Built a 4 GPU Litecoin mining rig.</p>
</section>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	img {
		width: 15rem;
		aspect-ratio: 1;
		border-radius: 50%;
	}

	address {
		font-style: normal;
	}

	h1 {
		font-weight: 400;
		text-transform: uppercase;
	}

	h2 {
		font-weight: 300;
		text-transform: uppercase;
		margin-top: 4rem;
	}

	h3 {
		font-weight: 400;
		margin-bottom: 0;
	}

	.year {
		color: #a5a5a5;
	}

	section {
		margin-bottom: 1.5rem;
	}

	section p {
		margin: 0.5rem 0;
	}

	table {
		width: 100%;
		border-spacing: 0;
		border-collapse: collapse;
		margin: 1rem 0;
	}
	th,
	td {
		margin: 0;
		padding: 0;
	}

	th {
		text-align: left;
		font-weight: 400;
	}
	td:nth-child(2),
	th:nth-child(2) {
		text-align: right;
	}

	a {
		color: #2c6c2f;
	}

	strong,
	th {
		color: #348037;
	}

	/*
	@media print {
		.pagebreak {
			page-break-before: always;
		}
	}
    */
</style>
