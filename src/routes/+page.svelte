<script>
	import logo from '$lib/images/logo.png'
	import ZeMadCoder from '$lib/images/ZeMadCoder.jpg'
</script>

<div class="homepage">
	<h1>Salut les geeks !</h1>
	<h2>
		Bienvenue au club informatique du lycée Voltaire
	</h2>
	<img alt="logo club informatique" width="250px" src={logo} />

	Avec:
	<ul>
	<li><img alt="ZeMadCoder" width="50px" src={ZeMadCoder} />ZeMadCoder</li>
	</ul>
</div>


<style>
	.homepage {
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
