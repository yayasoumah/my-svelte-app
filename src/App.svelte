<script>
	const twitter = 'build/images/twitter.png';
	const instagram = 'build/images/instagram.png';
	const linkedin = 'build/images/linkedin-logo.png';
	const github = 'build/images/github-sign.png'; 

	const twitterLink = 'https://twitter.com/yayasoumah';
	const instagramLink = 'https://www.instagram.com/yayasoumah/';
	const linkedinLink = 'https://www.linkedin.com/in/yaya-soumah-46996b11a/';
	const githubLink = 'https://github.com/yayasoumah';

	const articleOne = 'https://avolab.substack.com/p/how-fashion-brands-are-making-245'; 
</script>

<header class='nav-bar'>
	<p><b>Yaya Soumah</b></p>
</header>

<main>
	<h1>Yaya Soumah</h1>
	<p>
		<b>Bio: </b>I'm a serial entrepreneur, 
		I'm specialized in the <strong>fashion</strong> industry, 
		and I'm building and investing in <strong>AI</strong>, 
		<strong>Web3</strong> and <strong>consumer apps</strong>.
	</p>
	
	<p>
		If you're building something in one of these domains 
		and you already have a working prototype, let's connect!
	</p>
	<ul>
		<li>
			<a href= { twitterLink } > 
			    <img src={ twitter } alt='Twitter' height=30px width="30px"> 
		    </a>
		</li>
        <li>
			<a href= { instagramLink } > 
			    <img src={ instagram } alt='Instagram' height=30px width="30px"> 
		    </a> 
		</li>
		<li>
			<a href= { linkedinLink } > 
			    <img src={ linkedin } alt='LinkedIn' height=30px width="30px"> 
		    </a>
		</li>
		<li>
			<a href= { githubLink } > 
			    <img src={ github } alt='GitHub' height=30px width="30px"> 
		    </a>
		</li>
	</ul>
	<p>You can also <a href='mailto:yayasoumah.xyz@gmail.com'>email </a>
	    me, or book a <a href='https://calendly.com/yayasoumah/quick-call'>call</a>. 
	
	</p>

    <hr>
	<p>
		<b>Fashion: </b>
		I founded 
		<a href='https://instagram.com/avisionof.eth?igshid=YmMyMTA2M2Y='>AVISIONOF</a>, 
		a made in Italy high-end streetwear brand, where we mix art with high quality fabrics. 
		We dressed some of the greatest artists in the world. Now I'm merging the fashion with 
		new technologies, like <b>Blockchain</b> and <b>virtual</b> and <b>augmented reality</b>. 
	</p>
	<p>
		<b>AI: </b>
		I'm using <b>large language models</b> and <b>generative models</b> 
		to build applications that can improve the way users intereact with user interfaces.
	</p>
	<p>
		<b>Web3: </b>focused on developing Web3 based technologies that are easier to use, 
		with <b>account abstraction </b>and <b>on / off ramp</b>. 
	</p>
	<p>
		<b>Consumer apps: </b>
		I'm building <a href='https://hackmd.io/F7bLEkjwRgSoDETffyOqSw'>Incentive</a>, 
		an all in one application to discover, pay and get recommendations on restaurants and new dishes.
	</p>
	
	<hr>
	<p><b>Stuff I wrote</b></p>
	<p>  
	    <a href= { articleOne } > 
			How fashion brands are making $245 million with NFTs. 
		</a>
	</p>
	
		
	
</main>



<style>
	main {
		text-align: justify;
		
		padding: 1em;
		margin: 0 auto;
	}
		
	
	h1 {
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
		text-align: center;
	}

	p { 
		font-size: 1.2em;
		font-weight: 100;
	}

	ul {
		text-align: center;
		list-style-type: none;
		display: flex; 
		gap: 3em;
		padding: 0;
		justify-content: center;
	}

	.nav-bar {
		padding: 1em;
	}
		
@media (max-width: 640px) {
  main {
    width: 90%;
  }
  h1 {
    font-size: 2em;
  }
  p {
    font-size: 1em;
	font-weight: 300;
  }
}

@media (min-width: 640px) {
  main {
    width: 65%;
  }
  h1 {
    font-size: 3em;
  }
  p {
    font-size: 1.3em;
	font-weight: 300;
  }
}

	
</style>