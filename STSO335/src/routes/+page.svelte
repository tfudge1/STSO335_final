<script lang="ts">
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcomeFallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>


	<h1>
		Frederick Law Olmsted’s Urban Design Philosophy from inception to today
	</h1>

	<p>The United States experienced a fast-paced transformation into an urban nation during the nineteenth century while industrial development accompanied this urban growth. The combination of industrial production facilities and human population growth with air pollution caused serious doubts about  the ability of urban areas to sustain life. Frederick Law Olmsted entered this stressful environment to introduce urban planning concepts which would transform both physical spaces and civic social structures. The work of Olmsted went beyond landscape architecture since he functioned as a social reformer and writer and managerial visionary who used parks to create healthy environments with fair distribution of resources and facilitate social organization. His landscape work across the United States including Rochester New York demonstrates how his principles led to practical landscape implementation. Although it may look different today than it did in Olmsted’s time, the green urban philosophy created by Olmsted for promoting moral improvement, environmental awareness and public democratic areas continues to guide contemporary urban planning to this day.</p>

	<p>Cities in the nineteenth century dealt with multiple significant problems including air pollution and social breakdowns together with extreme population density as a result of increasing industrialization. Modern sustainability concerns echo the difficulties which existed during the nineteenth century, although their causes may be different. <a href="https://thesolutionsjournal.com/frederick-law-olmsted-nature-sustainable-communities/">The creation of the metropolis created "a problem which the experience of mankind offers little or no help in solving" as Adam Rome observes (Rome, 2017).</a> Olmsted recognized cities as potential, if not ongoing, disasters yet in them he saw the possibility of creating better social justice and health standards for people.</p>

	<p>Before his work as a park designer Olmsted operated as both a social reformer and a journalist. Through his studies on slavery in the South as well as his time with the U.S. Sanitary Commission during the Civil War and further through his management of the Mariposa mining company in California. Olmsted acquired a deep understanding of the conditions of American social injustices. <a href="https://thesolutionsjournal.com/frederick-law-olmsted-nature-sustainable-communities/">According to Rome, Olmsted kept asking himself about the basic needs of  a community that could maintain itself (Rome, 2017).</a> His solution manifested through parks that  functioned as active components for public welfare rather than pure decorative elements for the wealthy. Olmsted believed nature exposure could help reduce urban social problems. <a href="https://www.jstor.org/stable/23209954?searchText=frederick+law+olmsted&searchUri=%2Faction%2FdoBasicSearch%3FQuery%3Dfrederick%2Blaw%2Bolmsted%26so%3Drel&ab_segments=0%2Fbasic_search_gsv2%2Fcontrol&refreqid=fastly-default%3Ad03b114470cefc9416cab604d04d3892&seq=1">Through his designs Olmsted sought to uplift people according to Colin Fisher who reports that the architect believed "beautiful sylvan scenes" during leisure would lead to work  becoming "more methodical and regular" (Fisher, 2011, p.  2).</a> <a href="https://www.jstor.org/stable/1903842?searchText=frederick+law+olmsted&searchUri=%2Faction%2FdoBasicSearch%3FQuery%3Dfrederick%2Blaw%2Bolmsted%26so%3Drel&ab_segments=0%2Fbasic_search_gsv2%2Fcontrol&refreqid=fastly-default%3Aa22e04b974dd0715b5bf2a770339b043&seq=1">According to Geoffrey Blodgett Olmsted embraced "conservative reform" as his philosophical approach  because he trusted in democratic principles led by educated leadership. Within this conceptual framework parks operated as active tools for moral instruction.</a></p>

	<p>To Olmsted, the park functioned as a remedy against contemporary urban problems by providing spaces for relaxation alongside nature. <a href="https://www.jstor.org/stable/23209954?searchText=frederick+law+olmsted&searchUri=%2Faction%2FdoBasicSearch%3FQuery%3Dfrederick%2Blaw%2Bolmsted%26so%3Drel&ab_segments=0%2Fbasic_search_gsv2%2Fcontrol&refreqid=fastly-default%3Ad03b114470cefc9416cab604d04d3892&seq=1">But this nature was not natural, instead the parks dreamt by Olmsted were highly manicured. His most famous work, Central Park, exists as a human-designed landscape instead of natural wilderness since its creators shaped it to create the illusion of organic beauty (Fisher, 2011, p. 2).</a> The artificial natural  environment played a fundamental role in achieving his design objectives. It presented both visual appeal and serenity alongside providing the community with a free to access forum to promote social ideals. The parks aimed to extract people out of immoral or socially repressive settings, such as saloons or tenement environments and lead them toward a collective civic experience. <a href="https://thesolutionsjournal.com/frederick-law-olmsted-nature-sustainable-communities/">The park served Olmsted as a democratic space according to Rome because it allowed people from different social classes to interact with each other.</a></p>

	<p>Olmsted discovered in Rochester an audience which accepted his ideas although they showed restraint toward them. The city achieved the status of being one of only four places to receive an entire Olmsted park system. Highland Park together with Seneca Park and Genesee Valley Park followed his design approach by incorporating pastoral elements with accessible routes and open fields as well as water access points. The city of Rochester became the first metropolitan area of its class to develop such an extensive park planning initiative. Olmsted commended Rochester leaders for establishing public domains despite operating with limited financial resources.<a href="https://www.libraryweb.org/~rochhist/v75_2013/v75i2.pdf"> The city leaders who in  1888 hired the nation's premier expert in park design... decided to make public space their top priority  (Comeau, 2013, p. 1).</a> The city of Rochester provided more  than financial support by embracing a developing social movement dedicated to enhancing urban living conditions for city inhabitants.</p>

	<iframe title="Highland Park" frameborder="0" class="juxtapose" width="100vw" height="auto" src="https://cdn.knightlab.com/libs/juxtapose/latest/embed/index.html?uid=0a121954-1e07-11f0-bb23-0936e1cb08fb"></iframe>


</section>

<style>
iframe{
	min-width: 100vw;
	min-height:100vh;
}

	#juxtapose-embed{
		min-width: 75vw;
		min-height: 75vh;
		padding-left: 12vw;
		padding-right: 12vw;
	}

	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
	p{
		text-indent: 10vw;
		margin-bottom: 1.5em;
	}

	h1 {
		width: 100%;
		margin-bottom: 2em;
	}
	a{
		color:black;
		font-weight: bold;
	}
	a:hover{
		font-size:1.1em;
	}

</style>
