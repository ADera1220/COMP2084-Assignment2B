<h1>WatchTower Web App</h1>
<a href="https://watchtowerapp.azurewebsites.net/">LINK TO AZURE DEPLOYED SITE</a>
<h2>Project for COMP 2084 - Server-Sider Scripting with ASP.NET</h2>
<p>This web app will allow users to track their progress in television series across streaming services, cableTV or DVD/Blu-Ray Disc</p>

<h3>Assignment 1B</h3>
<p>The project has been created, scaffolded and stylized.</p>
<p>The 3 Tables are:</p>
<ul>
  <li><h5>Shows:</h5>The main focus of this App is to track the shows, how many episodes, and the current place in the series, this table does just that</li>  
  <li><h5>Services:</h5>Shows are found and watched in a variety of ways, tracking these servcies - be they physical or digital - is important to coordinating watching a show</li>  
  <li><h5>CoWatchers:</h5>People like to watch shows with friends/family, allowing them to track the people they watch shows with seems like a valuable feature</li>  
</ul>

<h3>Assignment 2A</h3>
<h4>User Profiles and Registration</h4>
<ol>
	<li>
		<h5>On Site User Login/Registration</h5>
		<p>Implemented registration and login functions in the app using the Identity scaffolding. Implementation was unproblematic</p>
	</li>
	<li>
		<h5>OAuth via Google and Facebook</h5>
		<p>Implemented the ability to register and login through external APIs from Google and Facebook. ClientIDs and Secrets were intitially stored as user secrets, however, when deploying the site to Azure, there were fatal errors preventing the website from functioning.</p>
	</li>
	<li>
		<h5>Fixing Deployment</h5>
		<p>As the deployed website functioned on localhost, and the previous Azure build was perfectly functional, the website must have been broken by OAuth implementation. This was because the App's user secrets were not uploaded to the live build. I was unable to solve this issue so I changed implementation to have the Client IDs and secrets in the appsettings.json file. The subsequent development worked flawlessly.</p>
	</li>
</ol>