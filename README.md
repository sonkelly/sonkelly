### Hi there 👋
<img src="https://img.freepik.com/free-vector/corporate-cover-web-banner-template_207180-711.jpg?size=626&ext=jpg">
<html>

<head>
	<title>skills progress bar</title>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
</head>
<style>
	* {
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
		font-family: "arial";
	}

	.progress-bar {
		margin: 50px auto;
		width: 500px;
		height: 400px;
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-orient: vertical;
		-webkit-box-direction: normal;
		-ms-flex-flow: column wrap;
		flex-flow: column wrap;
		-ms-flex-pack: distribute;
		justify-content: space-around;
	}

	.progress-bar h1 {
		text-align: center;
	}

	.skills {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
	}

	.bar {
		width: 400px;
		background: #ddd;
		margin-left: 20px;
		height: 20px;
		border-radius: 10px;

	}

	.skill-title {
		width: 59px;
		font-weight: bold;
	}

	.bar-color {
		width: 0%;
		background: #ddd;
		height: 100%;
		border-radius: 10px;
		-webkit-transition: all 0.7s linear;
		transition: all 0.7s linear;
		-webkit-transition-delay: 0.5s;
		transition-delay: 0.5s;

	}
</style>

<body>
	<div class="progress-bar">

		<h1>My skills</h1>
		<div class="skills">
			<div class="skill-title">
				Html
			</div>
			<div class="bar">
				<div class="bar-color">

				</div>
			</div>
		</div>
		<div class="skills">
			<div class="skill-title">
				Css
			</div>
			<div class="bar">
				<div class="bar-color">

				</div>
			</div>
		</div>
		<div class="skills">
			<div class="skill-title">
				jQuery
			</div>
			<div class="bar">
				<div class="bar-color">

				</div>
			</div>
		</div>
		<div class="skills">
			<div class="skill-title">
				js
			</div>
			<div class="bar">
				<div class="bar-color">

				</div>
			</div>
		</div>
	</div>
	<script>
		jQuery(document).ready(function () {
			jQuery(".bar-color").css({
				"background": "#2196F3",
				"width": "95%"
			});
			jQuery(".skills:nth-of-type(2) .bar-color").css({
				"width": "80%"
			});
			jQuery(".skills:nth-of-type(3) .bar-color").css({
				"width": "70%"
			});
			jQuery(".skills:nth-of-type(4) .bar-color").css({
				"width": "55%"
			});
		});
	</script>
</body>

</html>
<!--
**sonkelly/sonkelly** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
