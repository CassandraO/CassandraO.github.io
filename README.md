# CassandraO.github.io
<! cited sources : 
1) Lightbox:
  1) Lighbox concept borrowed from Gregory Schier (http://codepen.io/gschier/pen/HCoqh/).
  2) Thumbnail overlay borrowed from P. Colin Manikoth (http://codepen.io/manikoth/pen/wGwjKm/)
/* Thumbnail overlay borrowed from P. Colin Manikoth (http://codepen.io/manikoth/pen/wGwjKm/) */
figure {
 
  
  border-radius: 5%;
  background: #FE92B9;
  height: 200px;
  position: relative;
  overflow: hidden;
  width: 300px;
  display: inline-block;
  
}

figcaption {
  font-family: 'Rokkitt', serif;
  color: #AA5DA3;
  background: #FFDED6;
  bottom: 0;
  padding: 10px;
  position: absolute;
  width: 280px;
}

/* First Frame  */
figure figcaption {
  opacity: 1;
  bottom: -116px;
  transition: all 1s;
}

/* Last Frame */
figure:hover figcaption {
  bottom: 0;
  opacity: 1;
}

/* Lighbox concept borrowed from Gregory Schier (http://codepen.io/gschier/pen/HCoqh/). */

.lightbox {
	/** Default lightbox to hidden */
	display: none;

	/** Position and style */
	position: fixed;
	z-index: 999;
	width: 100%;
	height: 100%;
	text-align: center;
	top: 0;
	left: 0;
	background: rgba(254, 146, 185, 0.68);
}

.lightbox img {
	/** Pad the lightbox image */
width: auto;
	max-height: 90%;
	margin-top: 2%;
}

.lightbox:target {
	/** Remove default browser outline */
	outline: none;

	/** Unhide lightbox **/
	display: block;
}---->
