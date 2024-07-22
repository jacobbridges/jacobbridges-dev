<script>
	export let name;
</script>

<svelte:head>
	<title>Jacob Bridges</title>
	<meta name="robots" content="noindex nofollow" />
	<html lang="en" />
</svelte:head>


<div class="layout">
	<div class="layout__graphic">
	  <div class="graphic1"></div>
	  <div class="graphic2"></div>
	  <div class="graphic3"></div>
	  <div class="graphic4"></div>
	</div>
	<div class="layout__information">
	  <div class="vcard">
		<div class="socials"><a class="no-underline" href="https://storage.googleapis.com/space.jacobbridges.pw/upload/filedrops/Jacob%20Bridges%20-%202024%20Resume.pdf" title="Download Resume" target="_blank"><i class="fas fa-file-download"></i></a><a class="no-underline" href="https://github.com/jacobbridges" title="Jacob Bridges Github"><i class="fab fa-github"></i></a><a class="no-underline" href="https://www.linkedin.com/in/jacobbridges" title="Jacob Bridges LinkedIn"><i class="fab fa-linkedin"></i></a><a class="no-underline" href="mailto:me@jacobbridges.dev" title="Email Jacob Bridges"><i class="fas fa-envelope"></i></a></div>
		<h1>Jacob Bridges<small>Data Engineer in Huntsville AL</small></h1>
		<!--<a class="button button__primary call-to-action" href="http://jacobbridges.github.io/">Read my blog</a>-->
		<h2>Work Experience</h2>
		<ul class="flat-list">
      <li>
				<a href="https://amfamlabs.com/about/">American Family Labs</a> (2022 - Present)
			</li>
			<li>
				<a href="https://www.invitae.com/en">Invitae</a> (2021 - 2022)
			</li>
			<li>
				<a href="https://cyware.com/">Cyware Labs</a> (2020 - 2021)
			</li>
			<li>
				<a href="https://www.fandom.com/about">Fandom</a> (2017 - 2020)
			</li>
			<li> 
				<a href="https://www.excelmicro.com/">Excel Micro</a> (2013 - 2017)
			</li>
		</ul>
		<h2>Education</h2>
		<ul class="flat-list">
		  <li>B.Sc. in Software Engineering</li>
		  <li>Minor in Mathematics</li>
		</ul>
	  </div>
	</div>
  </div>

<style>
a {
  color: #89c4f4;
}
a.no-underline {
  text-decoration: none;
}

ul.flat-list {
  list-style: none;
  padding-left: 0;
}

.layout {
  display: grid;
  grid-template-areas: "graphic" "information";
  grid-row-gap: 1rem;
  grid-template-columns: 1fr;
}
@media (min-width: 1000px) {
  .layout {
    grid-template-areas: "graphic information";
    grid-row-gap: default;
    grid-template-columns: 1fr 33vw;
    min-height: 100vh;
    max-height: 100vh;
  }
}
.layout__graphic {
  grid-area: graphic;
  display: none;
}
@media (min-width: 1000px) {
  .layout__graphic {
    display: grid;
    grid-template-columns: 1fr 1fr;
    row-gap: 1rem;
    column-gap: 1rem;
    padding: 16px;
  }
}
.layout__graphic div {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 10px;
}
.layout__graphic .graphic1 {
  background-color: #89c4f4;
  background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Python_logo_and_wordmark.svg/972px-Python_logo_and_wordmark.svg.png);
  background-size: 40vh 12vh;
  background-repeat: no-repeat;
  background-position: center;
}
.layout__graphic .graphic2 {
  background-color: #00CF80;
  background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/AmazonWebservices_Logo.svg/1200px-AmazonWebservices_Logo.svg.png);
  background-size: 29vh 10vh;
  background-repeat: no-repeat;
  background-position: center;
}
.layout__graphic .graphic3 {
  background-color: #7F7CAF;
  background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_%28container_engine%29_logo.svg/1280px-Docker_%28container_engine%29_logo.svg.png);
  background-size: 42vh 10vh;
  background-repeat: no-repeat;
  background-position: center;
}
.layout__graphic .graphic4 {
  background-color: #F18F01;
  background-image: url(https://images.vexels.com/media/users/3/140692/isolated/preview/72d1f12edf758d24f5b6db73bac4f297-linux-logo-by-vexels.png);
  background-size: 31vh;
  background-repeat: no-repeat;
  background-position: center;
}
.layout__information {
  grid-area: information;
  padding: 16px 40px;
  display: flex;
  align-content: center;
  align-items: center;
}

.vcard {
  width: 100%;
}
.vcard h1 small {
  display: block;
  font-size: 1rem;
}
.vcard h2 {
  margin-top: 3rem;
  font-weight: 100;
  text-transform: uppercase;
  font-size: 1rem;
  letter-spacing: 1px;
}

.socials {
  font-size: 32px;
}
.socials a {
  margin-right: 1rem;
}

a.button {
  text-decoration-color: initial !important;
  text-decoration: none;
  position: relative;
  padding: 0 1rem;
}
a.button__primary {
  background-color: #89c4f4;
}
a.button__secondary {
  background-color: #00CF80;
}

a.call-to-action {
  color: #444;
  border: 1px solid #305b8f;
  display: block;
  text-align: center;
  border-radius: 5px;
  cursor: pointer;
  box-sizing: border-box;
  white-space: nowrap;
  user-select: none;
  font-size: 1.1rem;
  line-height: 2.8rem;
  width: 100%;
  text-shadow: 0.5px 0.5px 0px #e0e0e0;
  box-shadow: 1px 1px 3px 0px rgba(50, 50, 50, 0.75);
}

</style>
