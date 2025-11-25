.skip-link {
  position: absolute;
  left: -9999px;
  top: auto;
  width: 1px;
  height: 1px;
  overflow: hidden;
}
.skip-link:focus,
.skip-link:active {
  position: static;
  left: 1rem;
  top: 1rem;
  padding: 0.5rem 1rem;
  background: #000;
  color: #fff;
  text-decoration: none;
  border-radius: 4px;
  z-index: 1000;
}

nav {
  display: inline-block;
  width: 80%;
  background: #eee;
  padding: 1rem;
}
nav img {
  width: 10%;
  height: auto;
}

.grid {
  display: grid;
  grid-template-columns: 40% 40%;
  justify-content: center;
  align-items: center;
  column-gap: 3%;
  row-gap: 2rem;
  padding: 1rem;
}
.grid img {
  width: 100%;
  height: auto;
}

.flex {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 1rem;
  padding: 1rem;
}
.flex img {
  width: 200px;
  height: auto;
}

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
header {
  padding: 1rem;
  background: #ddd;
}
main {
  padding: 1rem;
}
footer {
  padding: 1rem;
  background: #ccc;
  text-align: center;
}
