<script lang="ts">
	import '@fontsource-variable/rubik';
	import '@fontsource-variable/roboto-slab';

	import profile from '$lib/assets/profile.jpg';
</script>

<header>
	<div>
		<h1>Johan Schuijt</h1>
		<p>R&D / Hacker. I make machines empower humans. Systems-thinker.</p>
		<address>
			Wollbell 22<br />
			6094 Axams<br />
			<a href="tel:+31651952461">+31651952461</a><br />
			<a href="mailto:johan@resolve.works">johan@resolve.works</a>
		</address>
	</div>

	<img src={profile} alt="profile" />
</header>

<div class="group">
	<h2>Experience</h2>

	<section>
		<h3><strong>OpenSanctions</strong>, Berlin — <i>Creative Technologist</i></h3>
		<p class="year">2025 - Present</p>
		<p>
			Builing tooling to discover and convert arbitrary public sources into structured data, with
			the goal of enriching Wikidata.
		</p>
	</section>
</div>

<section>
	<h3><strong>Follow the Money</strong>, Amsterdam — <i>Full Stack Developer</i></h3>
	<p class="year">2021 - 2025</p>
	<p>
		Designed, built, and maintained the (cloud) data infrastructure of a investigative journalism
		platform. Built data-pipelines and a RAG application for PDF files.
	</p>
</section>

<section>
	<h3><strong>Forest.host</strong>, Utrecht — <i>Founder</i></h3>
	<p class="year">2017 - 2021</p>
	<p>
		Designed, built, and maintained the (hardware) infrastructure and APIs for a "zero-config" CI/CD
		hosting company.
	</p>
</section>

<section>
	<h3><strong>Freelance</strong>, Utrecht — <i>Full Stack Developer</i></h3>
	<p class="year">2014 - 2017</p>
	<p>
		Project based freelancer developer and UI/UX designer. Designed and developed custom
		administration systems, APIs and websites.
	</p>
</section>

<section>
	<h3><strong>1200WD</strong>, Amsterdam — <i>Front-end Developer</i></h3>
	<p class="year">2012 - 2014</p>
	<p>UI/UX design and front-end development of e-commerce websites.</p>
</section>

<div class="group">
	<h2>Skills</h2>

	<section>
		<h3><strong>Programming</strong></h3>
		<p>
			I continuously keeping up to date with modern development practices throughout my career. I'm
			well-informed and experiment with new technologies. I use language models and agents
			extensively.
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
					<td>Javascript/Typescript</td>
					<td>~20+</td>
				</tr>
				<tr>
					<td>HTML/CSS</td>
					<td>~20+</td>
				</tr>
				<tr>
					<td>Python</td>
					<td>~15+</td>
				</tr>
				<tr>
					<td>SQL</td>
					<td>~15+</td>
				</tr>
				<tr>
					<td>PHP</td>
					<td>~10+</td>
				</tr>
				<tr>
					<td>Rust</td>
					<td>~3</td>
				</tr>
				<tr>
					<td>Ruby</td>
					<td>~1</td>
				</tr>
			</tbody>
		</table>
	</section>
</div>

<section>
	<h3><strong>Tools</strong></h3>

	<p>
		I use exclusively open-source software. I've always used Linux as my operating system, and have
		extensive experience with the ecosystem. Some of the keywords that come to mind in no specific
		order:
	</p>

	<p>
		GNU/Linux, Vim, Git, Docker/Podman/Compose, Kubernetes, Systemd, PostgreSQL, Mysql/MariaDB,
		ElasticSearch/OpenSearch, Neo4J, RabbitMQ, Svelte/SvelteKit, React/Next.js, Ansible/Terraform,
		DuckDB, Ollama/vLLM/SGLang, Pi, Pydantic AI, OpenID/oAuth. Django/Wagtail, FastAPI, Pydantic,
		JSON/JSON Schema. Playwright/CDP.
	</p>

	<p>
		I've been using LLMs since early on, and coding agents since the
		<a href="https://code.claude.com/">Claude Code</a> early access program. As my understanding of
		the technology deepens, so does my control over my agentic coding process. After initially
		moving to
		<a href="https://pi.dev">Pi</a> with a set of plugins I developed myself, I'm currently using a
		<a href="https://pi.dev">custom coding harness</a> built on
		<a href="https://github.com/earendil-works/pi/tree/main/packages/durable">Pi durable</a>.
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

<div class="group">
	<h2>Education</h2>

	<p>
		I am a college drop-out that has been programming since childhood. Schoolwork came easily, so I
		looked to the computer for a challenge. I learned to keep learning and am continuously adapting
		to the changing landscape.
	</p>

	<section>
		<h3><strong>Hogeschool Utrecht</strong>, Utrecht — <i>Media Technology</i></h3>
		<p class="year">2010 - 2011</p>
		<p>Followed several classes. Stopped before completion.</p>
	</section>
</div>

<section>
	<h3><strong>Hogeschool van Amsterdam</strong>, Amsterdam — <i>Game Development</i></h3>
	<p class="year">2009 - 2010</p>
	<p>Followed several classes. Stopped before completion.</p>
</section>

<div class="group">
	<h2>Projects</h2>

	<section>
		<h3>
			<strong><a href="https://everypolitician.org/">EveryPolitician</a></strong> —
			<i>open political data</i>
		</h3>
		<p class="year">2025 - Present</p>
		<p>An atlas of political offices and their holders across the world.</p>
		<ul>
			<li>
				<strong
					><a href="https://github.com/opensanctions/everypolitician.org">everypolitician.org</a
					></strong
				> — main website, served from the OpenSanctions API.
			</li>
			<li>
				<strong><a href="https://github.com/opensanctions/poliloom">PoliLoom</a></strong> — automatically
				extracts and enriches politicians with information from the web. Humans verify, verified statements
				flow into Wikidata.
			</li>
			<li>
				<strong><a href="https://github.com/opensanctions/funes">Funes</a></strong> — agentic spider for
				arbitrary definitions of PEP categories. PEP discovery through multiple agents and queues.
			</li>
			<li>
				<strong><a href="https://github.com/opensanctions/pravda">Pravda</a></strong> — shared evidence
				layer. Content addressed, human inspectable archive.
			</li>
		</ul>
	</section>
</div>

<section>
	<h3>
		<strong><a href="https://github.com/resolveworks/key">Key</a></strong> —
		<i>coding agent harness</i>
	</h3>
	<p class="year">2026 - Present</p>
	<p>A durable transcript host, containerized toolcalling. Parallel worktrees. Multi-client.</p>
</section>

<section>
	<h3><strong>Pi extensions</strong> — <i>coding-agent tooling</i></h3>
	<p class="year">2026</p>
	<p>
		Extensions for <a href="https://pi.dev">Pi</a>
	</p>
	<ul>
		<li>
			<strong><a href="https://github.com/resolveworks/fork">fork</a></strong> — spawn subagents in isolated
			worktrees and tmux windows, steered over a Unix socket.
		</li>
		<li>
			<strong><a href="https://github.com/resolveworks/trace">trace</a></strong> — tree-sitter and SQLite
			index backing codebase exploration tools.
		</li>
		<li>
			<strong><a href="https://github.com/resolveworks/mine">mine</a></strong> — stealth-patched Chrome
			in Podman, returning pages as clean markdown.
		</li>
		<li>
			<strong><a href="https://github.com/resolveworks/scry">scry</a></strong> — web search through the
			Brave Search API.
		</li>
		<li>
			<strong><a href="https://github.com/resolveworks/recall">recall</a></strong> — search and review
			past agent sessions.
		</li>
		<li>
			<strong><a href="https://github.com/resolveworks/ward">ward</a></strong> — disposable Arch Linux
			container holding the agent toolchain.
		</li>
	</ul>
</section>

<section>
	<h3>
		<strong><a href="https://github.com/resolveworks/pathfinder">Pathfinder</a></strong> —
		<i>native Android research agent</i>
	</h3>
	<p class="year">2026</p>
	<p>
		Searches the web and reads pages to answer. Its runtime runs on device, and is a selective
		Kotlin port of Pi's agent runtime.
	</p>
</section>

<section>
	<h3>
		<strong><a href="https://github.com/resolveworks/memex">Memex</a></strong> —
		<i>shared memory</i>
	</h3>
	<p class="year">2026</p>
	<p>A multilingual conversational assistant that remembers. A shareable knowledge base.</p>
</section>

<section>
	<h3>
		<strong><a href="https://github.com/resolveworks/worldgraph">Worldgraph</a></strong> —
		<i>knowledge from news</i>
	</h3>
	<p class="year">2026</p>
	<p>
		A developing research into knowledge extraction from news. Cross-source structural matching
		through graph deduplication. Using the fact-checked redundancy of the press as a signal.
	</p>
</section>

<section>
	<h3>
		<strong><a href="https://github.com/resolveworks/insight">Insight</a></strong> —
		<i>local-first research agent</i>
	</h3>
	<p class="year">2025 - Present</p>
	<p>
		Rewrite of Hindsight as a desktop research agent: a local index over documents, agentic
		search-and-read, and peer-to-peer collection sync.
	</p>
</section>

<section>
	<h3>
		<strong><a href="https://github.com/resolveworks/hindsight">Hindsight</a></strong> —
		<i>RAG for FOIA documents</i>
	</h3>
	<p class="year">2023 - 2025</p>
	<p>Built at Follow the Money to make large FOIA request dumps searchable and answerable.</p>
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

	ul {
		margin: 0.5rem 0;
		padding-left: 1.25rem;
	}

	li {
		margin: 0.15rem 0;
	}

	code {
		font-size: 0.9em;
	}

	@media print {
		section {
			break-inside: avoid;
		}

		/* Keeps a heading on the same page as its first block: Firefox does not
		support break-after: avoid, so the pair has to share one fragmentation unit. */
		.group {
			break-inside: avoid;
		}
	}

	/*
	@media print {
		.pagebreak {
			page-break-before: always;
		}
	}
    */
</style>
