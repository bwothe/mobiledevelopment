# mobiledevelopment
Mobile Development Course Project

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>jQuery Mobile Web App</title>
<meta name="viewport" content="width=device-width,initial-scale=1" />
<link href="styles/custom.css" rel="stylesheet" type="text/css">
<link rel="stylesheet" href="themes/main.min.css" />
<link rel="stylesheet" href="themes/jquery.mobile.icons.min.css" />
<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile.structure-1.4.5.min.css" />
<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>


</head>
<body>

<div id="page" data-role="page" data-theme="a">
	<div data-role="header" data-theme="a">
	  <div class="logo"><img src="logo.png"></div>
		<h1>My Favorite Games</h1>
		<a href="#myPanel" class="ui-btn ui-btn-inline">Menu</a>
	</div>

	<div data-role="panel" id="myPanel">
		<h3>Menu</h3>
		<ul data-role="listview" data-theme="c">
		<li class="menu"><a href="#xenogears">Xenogears</a></li>
		<li class="menu"><a href="#ff7">Final Fantasy 7</a></li>
		<li class="menu"><a href="#fft">Final Fantasy Tactics</a></li>
		<li class="menu"><a href="#sor">Streets of Rage</a></li>
		<li class="menu"><a href="#ac2">Assassin's Creed 2</a></li>
		<li class="menu"><a href="#gsh">Gunstar Heroes</a></li>
		<li class="menu"><a href="#yourFavorites">Submit Your Favorites</a></li>
		</ul>
	</div>

<div data-role="content">
  <p><center>This is a site filled with my favorite games. As a child of the late 80's and 90's<br>
    many of the games will come from that era. These games shaped my love and taste for games.<br>
    Each page will consist of a brief story synopsis, characters, and setting. Other aspects of <br>
    the game such as battle system and music will be discussed as well.</center></p>

	<!-- <div data-role="content">
		<ul data-role="listview" data-theme="c">
			<li><a href="#xenogears">Xenogears</a></li>
			<li><a href="#ff7">Final Fantasy 7</a></li>
			<li><a href="#fft">Final Fantasy Tactics</a></li>
      <li><a href="#sor">Streets of Rage</a></li>
      <li><a href="#ac2">Assassin's Creed 2</a></li>
      <li><a href="#gsh">Gunstar Heroes</a></li>
      <li><a href="#yourFavorites">Submit Your Favorites</a></li>
		</ul> -->

		<div class="ui-grid-b">
	    <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:400px"><img src="xenogearsCover.png"></div></div>
	    <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:400px"><img src="ff7CoverArt.png"></div></div>
	    <div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:400px"><img src="fftCoverArt.png"></div></div>
			<div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:400px"><img src="sor2.png"></div></div>
	    <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:400px"><img src="gsh.png"></div></div>
	    <div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:400px"><img src="ac2.png"></div></div>
		</div><!-- /grid-b -->
	</div>

	<div data-role="footer" data-theme="a">
	  <h4>Favorite Games &copy; 2018</h4>
	</div>
</div>


<div id="xenogears" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="b" data-add-back-btn="true">
	    <h1><font size="36">Xenogears</font></h1>
  </div>

  <p>Xenogears is a in a world wear Earth has died and humans have traveled through space. They crash land on a hospitable planet.
    The game takes place 10,000 years after these events and follows the story of Fei Fong Wong and Elly Van Houtnen.</p>
	<div data-role="content">
	  <h3>Main Characters</h3>
		<div data-role="content">
			<ul data-role="listview">
				<li>Fei Fong Wong</li>
				<li>Elly Van Houten</li>
				<li>Citan Uzuki</li>
				<li>Bart Fatima</li>
				<li>Rico Banderas</li>
        <li>Billy Lee Black</li>
        <li>Maria Balthasar</li>
        <li>Chu-Chu</li>
        <li>Emeralda Kasim</li>
			</ul>
	   </div>
   </div>
    <h3>Main Antagonists</h3>
    <div data-role="content">
      <ul data-role="listview" data-theme="c">
        <li>Deus</li>
        <li>Grahf</li>
        <li>Id</li>
        <li>Ramsus</li>
        <li>Miang</li>
	</div>
  <h3>Sound Track</h3>
  <h5>Disc One:</h5>
  <div data-role="content">
    <ol data-role="listview" data-filter="true">
      <li>Dark Dawn</li>
      <li>Stars of Tears</li>
      <li>Ties of Sea and Flames</li>
      <li>Our Village is Number One</li>
      <li>Valley from Where the Wind is Born</li>
      <li>Distant Promise</li>
      <li>Steel Giant</li>
      <li>Black Moon Forest</li>
      <li>Where the Eggs of Dreams Hatch</li>
      <li>Slumber (Short Version)</li>
      <li>Dazil, Town of Scorching Sands</li>
      <li>Longing</li>
      <li>Grahf, Dark Conqueror</li>
      <li>Fuse</li>
      <li>Traces Left from Warriors' Dreams"</li>
      <li>Gem Which Cannot Be Stolen</li>
      <li>Aveh, Ancient Dance</li>
      <li>Invasion</li>
      <li>Dance of Death</li>
      <li>In a Dark Sleep...</li>
      <li>The Gentle Wind Sings</li>
      <li>We, the Wounded Shall Advance into the Light</li>
      <li>Lost...Broken Shard</li>
      <li>Thames, the Spirit of a Man of the Sea</li>
      <li>Blue Traveller</li>
    </ol>
  </div>

  <div data-role="content">
    <h5>Disc Two:</h5>
    <ol data-role="listview" data-filter="true">
      <li>In a Prison of Remorse and Contentment</li>
      <li>Jaws of Ice</li>
      <li>Crimson Knight</li>
      <li>October Mermaid</li>
      <li>The Wind is Calling, Shevat of the Azure Sky</li>
      <li>The Heavens, Clouds and You</li>
      <li>Gathering Stars in the Night Sky</li>
      <li>A Star's Tears, a Man's Sentiments</li>
      <li>Soaring the Skies</li>
      <li>Wings</li>
      <li>Solaris, Heaven's Paradise</li>
      <li>Slumber (Long Version)</li>
      <li>The One Who Is Torn Apart</li>
      <li>Prayer, the Happiness People Wish for</li>
      <li>Premonnition</li>
      <li>Awakening</li>
      <li>The One Who Bares Fangs at God</li>
      <li>The Beginning and the End</li>
      <li>Small Two of Pieces ~Screeching Shards~</li>
    </ol>
  </div>
</div>

<div id="ff7" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="b" data-add-back-btn="true">
	    <h1><font size="36">Final Fantasy 7</font></h1>
  </div>

  <p>Final Fantasy takes place on an Earth like planet. It follows Cloud and the group called Avalanche as they try to stop a meteor from hitting the planet.</p>
	<div data-role="content">
	  <h3>Main Characters</h3>
		<div data-role="content">
			<ul data-role="listview">
				<li>Cloud Strife</li>
				<li>Barret Wallace</li>
				<li>Tifa Lockheart</li>
				<li>Aeris Gainsborough</li>
				<li>Red XIII</li>
        <li>Cait Sith</li>
        <li>Cid Highwind</li>
        <li>Vincent Valentine</li>
        <li>Yuffie Kisaragi</li>
			</ul>
	   </div>
   </div>
    <h3>Main Antagonists</h3>
    <div data-role="content">
      <ul data-role="listview">
        <li>Sephiroth</li>
        <li>Professor Hojo</li>
        <li>Shinra</li>
        <li>Jenova</li>
      </ul>
	   </div>
  <h3>Sound Track</h3>
  <h5>Disc One:</h5>
  <div data-role="content">
    <ol data-role="listview" data-filter="true">
      <li>The Prelude</li>
      <li>Opening-Bombing Mission</li>
      <li>Mako Reactor</li>
      <li>Anxiety</li>
      <li>Tifa's Theme</li>
      <li>Barret's theme</li>
      <li>Hurry!</li>
      <li>Lurking in the Darkness</li>
      <li>Shinra Inc.</li>
      <li>Let the Battles Begin!</li>
      <li>Fanfare</li>
      <li>Flowers Blooming in the Church</li>
      <li>Turks' Theme</li>
      <li>Under the Rotting Pizza</li>
      <li>The Oppressed</li>
      <li>Honeybee Inn</li>
      <li>Who...Are You?</li>
      <li>Don of the Slums</li>
      <li>Infiltrating Shinra</li>
      <li>Fight On!</li>
      <li>Red XIII's Theme</li>
      <li>The Chase</li>
      <li>Dear to the Heart</li>
    </ol>
  </div>

  <div data-role="content">
    <h5>Disc Two:</h5>
    <ol data-role="listview"  data-filter="true">
      <li>Main Theme of Final Fantasy VII</li>
      <li>On Our Way</li>
      <li>Good Night, Until Tomorrow</li>
      <li>On That Day, Five Years Ago</li>
      <li>Farm Boy</li>
      <li>Waltz de Chocobo</li>
      <li>Electric de Chocobo</li>
      <li>Cinco de Chocobo</li>
      <li>In Search of the Man in Black</li>
      <li>Fort Condor</li>
      <li>Rufus' Welcoming Ceremony</li>
      <li>It's Hard to Stand on Both Feet</li>
      <li>Trail of Blood</li>
      <li>J-E-N-O-V-A</li>
      <li>Continue</li>
      <li>Costa del Sol</li>
      <li>Mark of a Traitor</li>
      <li>Mining Town</li>
      <li>Gold Saucer</li>
      <li>Cait Sith's Theme</li>
      <li>Desert Wasteland</li>
    </ol>
  </div>

  <div data-role="content">
    <h5>Disc Three:</h5>
    <ol data-role="listview" data-filter="true">
      <li>Cosmo Canyon</li>
      <li>Lifestream</li>
      <li>The Great Warrior</li>
      <li>Descendant of Shinobi</li>
      <li>Those Chosen by the Planet</li>
      <li>The Nightmare Begins</li>
      <li>Cid's Theme</li>
      <li>Steal the Tiny Bronco</li>
      <li>Wutai</li>
      <li>Stolen Materia</li>
      <li>Win/ Place/ Show Chocobo!</li>
      <li>Fiddle de Chocobo</li>
      <li>Jackpot!</li>
      <li>Tango of Tears</li>
      <li>Debut</li>
      <li>Words Drowned by Fireworks</li>
      <li>Forested Temple</li>
      <li>Listen to the Cries of the Planet</li>
      <li>Aeris's Theme</li>
      <li>Buried in Snow</li>
      <li>The North Cave</li>
      <li>Reunion</li>
      <li>Who....Am I?</li>
    </ol>
  </div>

  <div data-role="content">
    <h5>Disc Four:</h5>
    <ol data-role="listview" data-filter="true">
      <li>Shinra's Full-Scale Assault</li>
      <li>Attack of the Weapon</li>
      <li>The Highwind</li>
      <li>Secret of the Deep Sea</li>
      <li>Provincial Town</li>
      <li>From the Edge of Despair</li>
      <li>Other side of the Mountain</li>
      <li>Hurry Up!</li>
      <li>Launching a Dream into Space</li>
      <li>Countdown</li>
      <li>Open Your Heart</li>
      <li>Mako Cannon - The Destruction of Shinra</li>
      <li>Judgement Day</li>
      <li>Jenova Complete</li>
      <li>Birth of a God</li>
      <li>One-Winged Angel</li>
      <li>The Planet's Crisis</li>
      <li>Ending Credits</li>
    </ol>
  </div>
</div>

<div id="yourFavorites" data-role="page" data-theme="c" data-add-back-btn="true">
	<div data-role="header" data-theme="c" data-add-back-btn="true">
	    <h1>Your Favorites</h1>
  </div>

  <div data-role="content">
    <form action="form.php" method="post">
        <label for="title">Name of Game:</label>
        <input class="localStorage" name="title" id="title" data-clear-btn="true">
        <input type="reset" value="Reset Button">
        <input type="submit" value="Submit Button">
    </form>
  </div>
	<div data-role="footer">
	  <h4>Favorite Games &copy; 2018</h4>
	</div>
</div>

<script>

(function()
	{
		var title = document.querySelector('.localstorage');
		function supportsLocalStorage()
			{
				return typeof(Storage)!== 'undefined';
			}

		if (!supportsLocalStorage())
			{
			title.value = 'Your browser does not support localStorage.';
			}
		else
				{
				try
					{
						setInterval(function()
							{
								localStorage.setItem('autosave', title.value);
							}
						, 1000);
					}
				catch (e)
					{
						if (e == QUOTA_EXCEEDED_ERR)
						{
							alert('Quota exceeded!');
						}
					}
				if (localStorage.getItem('autosave'))
					{
						title.value = localStorage.getItem('autosave');
					}
				document.querySelector('.clear').onclick = function()
					{
						title.value = '';
						localStorage.removeItem('autosave');
					};
				document.querySelector('.empty').onclick = function()
					{
						title.value = '';
						localStorage.clear();
					};
				}
			})();
		</script>
</html>
