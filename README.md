# FlughafenTegel3
<head>
<meta charset="utf-8">
<style>
.container {
  position: relative;
  width: 100%;
  overflow: hidden;
  padding-top: 56.25%; 
}
.responsive-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 100%;
  border: none;
}
</style>
</head>
<body>
<nav>
<a href="kepler.gl.html" target="iframe">Karte 1</a>
<a href="hello.html" target="iframe">Karte 2</a>
</nav>
<iframe name="iframe" src="kepler.gl.html" width="1024px" height="800px">
<div class="container">
<iframe class="responsive-iframe" src="kepler.gl.html" ></iframe>
</div>
</iframe>
</body>