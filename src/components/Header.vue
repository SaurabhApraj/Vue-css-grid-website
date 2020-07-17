<template>
  <div class="header">
    <div class="logo">
      <p>Logo</p>
    </div>
    <nav>
      <ul>
        <li>
          <a href="#">Home</a>
        </li>
        <li>
          <a href="#">Gallery</a>
        </li>
        <li>
          <a href="#">Service</a>
        </li>
        <li>
          <a href="#">Contact</a>
        </li>
      </ul>
    </nav>
    <div class="btnarea">
      <button>Login</button>
    </div>
  </div>
</template>
<style scoped>
.header {
  background-color: #542c85;
  display: flex;
  justify-content: space-between;
}
.logo p {
  font-size: 1.5rem;
  margin: 15px;
  font-weight: 600;
  color: #fff;
}
.logo p:hover {
  color: #d6c6ec;
  cursor: pointer;
}
nav ul {
  display: flex;
}
nav ul li {
  list-style: none;
  margin: 13px;
  padding: 7px 15px;
}
nav ul li a {
  text-decoration: none;
  color: #fff;
}
nav ul li a:hover {
  color: #f2f2f2;
  cursor: pointer;
  transition: 0.1s;
  border-bottom: 2px solid #fff;
}
.btnarea button {
  margin: 15px;
  padding: 7px;
  width: 80px;
  font-size: 0.9rem;
  border: none;
  color: #444;
  background-color: #fff;
  border-radius: 5px;
}
.btnarea button:hover {
  cursor: pointer;
}
</style>