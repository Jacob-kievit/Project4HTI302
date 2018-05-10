# Styleguide options

### Head

	<meta name='viewport' content='width-device-width, initial-scale-1' />
	<script src='https://cdn.rawgit.com/styledown/styledown/v1.0.2/data/styledown.js'></script>
	<link rel='stylesheet' href='https://cdn.rawgit.com/styledown/styledown/v1.0.2/data/styledown.css' />
	<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
	<link rel='stylesheet' href='styles.css'>
	<style>
	body {
		margin: 0;
		min-width:750px;
		font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif !important;
	}
	.navigation {
		padding-top: 69px;
	}
	.navigation ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		min-width: 165px;
		width: 25%;
		background-color: #f1f1f1;
		height: 100%; /* Full height */
		position: fixed; /* Make it stick, even on scroll */
		overflow: auto; /* Enable scrolling if the sidenav has too much content */
	}
	.indented {
		padding-left: 12px;
	}
	.navigation ul li {
		display: block;
		height: auto;
	}
	.navigation li a {
		display: block;
		color: #000;
		padding: 8px 16px;
		text-decoration: none;
		font-size: 15px;
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
	<h1 style='position: fixed; width: 100%; background-color: #105934; color: white; margin: 0; padding-left: 10px; min-width: 750px; z-index: 1;font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif !important;'>Share Economy Inc. Style Guide</h1>
	<div class='navigation'>
		<ul>
			<li><a href='#styleguide-purpose-and-philosophy'>Styleguide Purpose and Philosophy</a></li>
			<li><a href='#grid-layout'>Page Layout</a></li>
			<li><a href='#color-palette'>Color Palette</a></li>
			<li><a href='#typography'>Typography</a></li>
			<li><a href='#headings'>Headings</a></li>
			<li><a href='#paragraphs'>Paragraphs</a></li>
			<li><a href='#links'>Links</a></li>
			<li><a href='#buttons'>Buttons</a></li>
			<li><a href='#images'>Images</a></li>
			<li><a href='#lists'>Lists</a></li>
			<li><a href='#data-tables'>Tables</a></li>
			<li><a href='#navmenu'>Navigation</a></li>
			<li><a href='#form-elements'>Form Elements</a></li>
					<li class='indented'><a href='#text-fields'>Text Fields</a></li>
					<li class='indented'><a href='#text-areas'>Text Areas</a></li>
					<li class='indented'><a href='#checkboxes'>Checkboxes</a></li>
					<li class='indented'><a href='#radio-buttons'>Radio Buttons</a></li>
					<li class='indented'><a href='#dropdown-menus'>Dropdown Menus</a></li>
			<li><a href='#alerts'>Alerts</a></li>
			<li><a href='#popups'>Popups</a></li>
		</ul>
	</div>
	<div style='margin-left:25%;padding:1px 16px;height:1000px;' class='sg-container' sg-content></div>
