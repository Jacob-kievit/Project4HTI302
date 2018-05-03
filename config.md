# Styleguide options

### Head

	<meta name='viewport' content='width-device-width, initial-scale-1' />
	<script src='https://cdn.rawgit.com/styledown/styledown/v1.0.2/data/styledown.js'></script>
	<link rel='stylesheet' href='https://cdn.rawgit.com/styledown/styledown/v1.0.2/data/styledown.css' />
	<link rel='stylesheet' href='styles.css' />
	<style>
	body {
		margin: 0;
	}
	.navigation {
		padding-top: 69px;
	}
	.navigation ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		width: 25%;
		background-color: #f1f1f1;
		height: 100%; /* Full height */
		position: fixed; /* Make it stick, even on scroll */
		overflow: auto; /* Enable scrolling if the sidenav has too much content */
	}
	.navigation li a {
		display: block;
		color: #000;
		padding: 8px 16px;
		text-decoration: none;
	}

	.navigation li a.active {
		background-color: #4CAF50;
		color: white;
	}

	.navigation li a:hover:not(.active) {
		background-color: #555;
		color: white;
	}
	</style>
	
### Body
	<h1 style='position: fixed; width: 100%; background-color: #105934; color: white; margin: 0; padding-left: 10px;'>Share Economy Inc. Style Guide</h1>
	<div class='navigation'>
		<ul>
			<li><a href='#typography'>Typography</a></li>
			<li><a href='#buttons'>Buttons</a></li>
			<li><a href='#image'>Images</a></li>
			<li><a href='#list'>Lists</a></li>
			<li><a href='#data-table'>Tables</a></li>
			<li><a href='#navmenu'>Navigation</a></li>
			<li><a href='#text-field'>Text Fields</a></li>
			<li><a href='#checkbox-buttons'>Checkboxes</a></li>
			<li><a href='#'></a></li>
			<li><a href='#'></a></li>
			<li><a href='#'></a></li>
			<li><a href='#'></a></li><li>
		</ul>
	</div>
	<div style='margin-left:25%;padding:1px 16px;height:1000px;' class='sg-container' sg-content></div>