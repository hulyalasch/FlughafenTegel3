# FlughafenTegel3
<head>
<meta charset="utf-8">
<style>
  body {
  position: absolute;
  top: 0px;
  left: 0px;
  right: 0px;
  bottom: 0px;
}
.header {
  border-radius: 25px;
  height: 14%;
  width: 100%;
}
img.nav-action-image {
  width: 14px;
  height: auto;
}
nav a {
  display: inline;
  text-decoration: none;
  float: left;
  color: #d1e231;
  padding: 14px 16px;
  border-right: 1px solid #bbb;
}
nav a:hover {
  color: #bff000;
}
nav a.active {
  display: inline;
  background-color: #bab86c;
  color: #37412a;
}
.navigation-bar {
  position: absolute;
  padding: 0;
  width: 100%;
  margin-top: 5px;
  border-radius: 7px;
}
.action-block {
  height: 80%;
  width: 20%;
  margin-top: 40px;
}
</style>
</head>
<body>
<nav>
<a href="kepler.gl.html" target="iframe">Karte 1</a>
<a href="hello.html" target="iframe">Karte 2</a>
</nav>
<iframe name="iframe" src="kepler.gl.html" width="1455px" height="818px">
</iframe>
</body>