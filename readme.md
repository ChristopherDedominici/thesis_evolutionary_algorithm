<div align="center">
	<img src="img/logo_polito.png" alt="polito logo" height="250" width="250" />
</div>

<div align="center">
	<h4><i>Master Degree Thesis</i></h4>
	<br>
	<h1>Fantasy football forecasts</h1>
	<h3>an evolutionary algorithm</h3>
	<br>
	<p style="text-align: center;">SUMMARY</p>
</div>

<br>

<div align="left">
	<p>
	The aim of the thesis is to improve an already existing application used to forecast the best formation that a player (fantasy manager) can line up in the game of the fantasy football.
	<br> 
	<br>
	The work has been done in collaboration with the startup Teamies.
	<br>
	Teamies already had a fully working platform but the process on how they used to collect and manage the data was not so efficient and performing. 
	<br>
	So, they wanted to create the same system but in a more reliable way.
	<br>
	Moreover, they also wanted to increase the precision of their forecasts finding the best parameters to use in their algorithm in order to better combine and weigh the footballers and teams statistics used to generate these forecasts. 
	</p>
	<br>
	<p>
	The main tasks I had to do during my thesis were:
		<ul>
			<li>To redesign the database structure and its implementation</li>
			<li>To create several web scrapers to collect all the information needed to calculate the forecasts from different websites</li>
			<li>To create the scripts to insert/update the downloaded information inside the database</li>
			<li>To rewrite the original forecast algorithm in C++</li>
			<li>To evaluate the best parameters to use to improve the forecast results using an evolutionary algorithm</li>
		</ul>
	</p>
	<br>
	<p>
	The choice of using an evolutionary algorithm has been dictated from the fact that Teamies already had a proprietary algorithm to evaluate footballers performances and they just wanted to optimize specific parameters. 
	<br>
	So the need was to have a search technique to find exact or approximate solutions to optimize the search problems and the most suitable solution in this case was to use this type of approach.
	</p>
	<br>	
	<p>
	The main languages and environments used to develop the application are:
		<ul>
			<li>Database: MySQL relational database</li>
			<li>Scrapers: JavaScript scripts executed on the run-time environment Node.js with the npm package <a href="https://developers.google.com/web/tools/puppeteer/">Puppeteer</a> provided by Google</li>
			<li>Database scripts: JavaScript scripts executed on the run-time environment Node.js with the npm package <a href="https://www.npmjs.com/package/mysql">mysql</a></li>
			<li>Forecasts algorithm: C++</li>
			<li>Evolutionary algorithm: <a href="http://ugp3.sourceforge.net/">MicroGP evolutionary algorithm</a>, C++, bash scripts</li>
		</ul>
	</p>	
</div>






