# nodesjs-backend-creation-adopteundefaut
Création d'un backend en nodejs et d'une bdd

MCD du projet:


<?xml version="1.0" standalone="no"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN"
"http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">

<svg width="331" height="321" view_box="0 0 331 321"
xmlns="http://www.w3.org/2000/svg"
xmlns:link="http://www.w3.org/1999/xlink">\n\n<desc>Généré par Mocodo 2.3.7 le Sat, 02 Jan 2021 08:12:26</desc>

<rect id="frame" x="0" y="0" width="331" height="321" fill="#ffffbf" stroke="none" stroke-width="0"/>

<!-- Association CAN LIKE -->
<path d="M154 169 C 196.666666667 237.0 196.666666667 276.333333333 154 287" fill="none" stroke="#f46d43" stroke-width="2"/>
<text x="157.0" y="254" fill="#1a9850" font-family="Verdana" font-size="12">0,N</text>
<path d="M154 169 C 111.333333333 237.0 111.333333333 276.333333333 154 287" fill="none" stroke="#f46d43" stroke-width="2"/>
<text x="129.0" y="254" fill="#1a9850" font-family="Verdana" font-size="12">0,N</text>
<g id="association-CAN LIKE">
	<path d="M 176 262 a 14 14 90 0 1 14 14 V 287 h -72 V 276 a 14 14 90 0 1 14 -14" fill="#fdae61" stroke="#fdae61" stroke-width="0"/>
	<path d="M 190 287.0 v 11 a 14 14 90 0 1 -14 14 H 132 a 14 14 90 0 1 -14 -14 V 287.0 H 72" fill="#fee08b" stroke="#fee08b" stroke-width="0"/>
	<rect x="118" y="262" width="72" height="50" fill="none" rx="14" stroke="#f46d43" stroke-width="2"/>
	<line x1="118" y1="287" x2="190" y2="287" stroke="#f46d43" stroke-width="1"/>
	<text x="125" y="279.7" fill="#000000" font-family="Verdana" font-size="12">CAN LIKE</text>
</g>

<!-- Association BELONGS TO -->
<line x1="274" y1="51" x2="274" y2="169" stroke="#f46d43" stroke-width="2"/>
<text x="279.0" y="102" fill="#1a9850" font-family="Verdana" font-size="12">0,N</text>
<line x1="154" y1="169" x2="274" y2="169" stroke="#f46d43" stroke-width="2"/>
<text x="199" y="186.0" fill="#1a9850" font-family="Verdana" font-size="12">1,1</text>
<g id="association-BELONGS TO">
	<path d="M 308 144 a 14 14 90 0 1 14 14 V 169 h -96 V 158 a 14 14 90 0 1 14 -14" fill="#fdae61" stroke="#fdae61" stroke-width="0"/>
	<path d="M 322 169.0 v 11 a 14 14 90 0 1 -14 14 H 240 a 14 14 90 0 1 -14 -14 V 169.0 H 96" fill="#fee08b" stroke="#fee08b" stroke-width="0"/>
	<rect x="226" y="144" width="96" height="50" fill="none" rx="14" stroke="#f46d43" stroke-width="2"/>
	<line x1="226" y1="169" x2="322" y2="169" stroke="#f46d43" stroke-width="1"/>
	<text x="233" y="161.7" fill="#000000" font-family="Verdana" font-size="12">BELONGS TO</text>
</g>

<!-- Association HAVE -->
<line x1="45" y1="51" x2="45" y2="169" stroke="#f46d43" stroke-width="2"/>
<text x="50.0" y="110" fill="#1a9850" font-family="Verdana" font-size="12">0,N</text>
<line x1="154" y1="169" x2="45" y2="169" stroke="#f46d43" stroke-width="2"/>
<text x="87" y="186.0" fill="#1a9850" font-family="Verdana" font-size="12">1,N</text>
<g id="association-HAVE">
	<path d="M 55 144 a 14 14 90 0 1 14 14 V 169 h -48 V 158 a 14 14 90 0 1 14 -14" fill="#fdae61" stroke="#fdae61" stroke-width="0"/>
	<path d="M 69 169.0 v 11 a 14 14 90 0 1 -14 14 H 35 a 14 14 90 0 1 -14 -14 V 169.0 H 48" fill="#fee08b" stroke="#fee08b" stroke-width="0"/>
	<rect x="21" y="144" width="48" height="50" fill="none" rx="14" stroke="#f46d43" stroke-width="2"/>
	<line x1="21" y1="169" x2="69" y2="169" stroke="#f46d43" stroke-width="1"/>
	<text x="28" y="161.7" fill="#000000" font-family="Verdana" font-size="12">HAVE</text>
</g>

<!-- Association RESEARCH -->
<line x1="154" y1="169" x2="154" y2="51" stroke="#f46d43" stroke-width="2"/>
<text x="159.0" y="93" fill="#1a9850" font-family="Verdana" font-size="12">1,N</text>
<line x1="274" y1="51" x2="154" y2="51" stroke="#f46d43" stroke-width="2"/>
<text x="207" y="68.0" fill="#1a9850" font-family="Verdana" font-size="12">0,N</text>
<line x1="45" y1="51" x2="154" y2="51" stroke="#f46d43" stroke-width="2"/>
<text x="86" y="68.0" fill="#1a9850" font-family="Verdana" font-size="12">0,N</text>
<g id="association-RESEARCH">
	<path d="M 181 26 a 14 14 90 0 1 14 14 V 51 h -82 V 40 a 14 14 90 0 1 14 -14" fill="#fdae61" stroke="#fdae61" stroke-width="0"/>
	<path d="M 195 51.0 v 11 a 14 14 90 0 1 -14 14 H 127 a 14 14 90 0 1 -14 -14 V 51.0 H 82" fill="#fee08b" stroke="#fee08b" stroke-width="0"/>
	<rect x="113" y="26" width="82" height="50" fill="none" rx="14" stroke="#f46d43" stroke-width="2"/>
	<line x1="113" y1="51" x2="195" y2="51" stroke="#f46d43" stroke-width="1"/>
	<text x="120" y="43.7" fill="#000000" font-family="Verdana" font-size="12">RESEARCH</text>
</g>

<!-- Entity DEFAULT -->
<g id="entity-DEFAULT">
	<g id="frame-DEFAULT">
		<rect x="9" y="9" width="72" height="25" fill="#a6d96a" stroke="#a6d96a" stroke-width="0"/>
		<rect x="9" y="34.0" width="72" height="59" fill="#d9ef8b" stroke="#d9ef8b" stroke-width="0"/>
		<rect x="9" y="9" width="72" height="84" fill="none" stroke="#66bd63" stroke-width="2"/>
		<line x1="9" y1="34" x2="81" y2="34" stroke="#66bd63" stroke-width="1"/>
	</g>
	<text x="17" y="26.7" fill="#000000" font-family="Verdana" font-size="12">DEFAULT</text>
	<text x="14" y="51.8" fill="#000000" font-family="Verdana" font-size="12">Name</text>
	<line x1="14" y1="54" x2="50" y2="54" stroke="#000000" stroke-width="1"/>
	<text x="14" y="68.8" fill="#000000" font-family="Verdana" font-size="12">Decription</text>
	<text x="14" y="85.8" fill="#000000" font-family="Verdana" font-size="12">Image</text>
</g>

<!-- Entity GENDER -->
<g id="entity-GENDER">
	<g id="frame-GENDER">
		<rect x="234" y="17" width="80" height="25" fill="#a6d96a" stroke="#a6d96a" stroke-width="0"/>
		<rect x="234" y="42.0" width="80" height="43" fill="#d9ef8b" stroke="#d9ef8b" stroke-width="0"/>
		<rect x="234" y="17" width="80" height="68" fill="none" stroke="#66bd63" stroke-width="2"/>
		<line x1="234" y1="42" x2="314" y2="42" stroke="#66bd63" stroke-width="1"/>
	</g>
	<text x="248" y="34.7" fill="#000000" font-family="Verdana" font-size="12">GENDER</text>
	<text x="239" y="59.8" fill="#000000" font-family="Verdana" font-size="12">Name</text>
	<line x1="239" y1="62" x2="275" y2="62" stroke="#000000" stroke-width="1"/>
	<text x="239" y="76.8" fill="#000000" font-family="Verdana" font-size="12">Description</text>
</g>

<!-- Entity USER -->
<g id="entity-USER">
	<g id="frame-USER">
		<rect x="114" y="101" width="80" height="25" fill="#a6d96a" stroke="#a6d96a" stroke-width="0"/>
		<rect x="114" y="126.0" width="80" height="111" fill="#d9ef8b" stroke="#d9ef8b" stroke-width="0"/>
		<rect x="114" y="101" width="80" height="136" fill="none" stroke="#66bd63" stroke-width="2"/>
		<line x1="114" y1="126" x2="194" y2="126" stroke="#66bd63" stroke-width="1"/>
	</g>
	<text x="137" y="118.7" fill="#000000" font-family="Verdana" font-size="12">USER</text>
	<text x="119" y="143.7" fill="#000000" font-family="Verdana" font-size="12">Username</text>
	<line x1="119" y1="146" x2="181" y2="146" stroke="#000000" stroke-width="1"/>
	<text x="119" y="160.7" fill="#000000" font-family="Verdana" font-size="12">Firstname</text>
	<text x="119" y="177.8" fill="#000000" font-family="Verdana" font-size="12">Lastname</text>
	<text x="119" y="194.8" fill="#000000" font-family="Verdana" font-size="12">Age</text>
	<text x="119" y="211.8" fill="#000000" font-family="Verdana" font-size="12">Description</text>
	<text x="119" y="228.8" fill="#000000" font-family="Verdana" font-size="12">UserImage</text>
</g>
</svg>
