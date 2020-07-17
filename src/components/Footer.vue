<template>
  <div class="footer">
    <div class="logo">
      <p>Logo</p>
    </div>
    <div class="copyright">
      <p>&copy; Copyright 2020</p>
    </div>
    <div class="follow">
      <ul>
        <li>
          <a href="#">Github</a>&nbsp;
          <a href="#">Linkedin</a>
        </li>
      </ul>
    </div>
  </div>
</template>
<style scoped>
.footer {
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
ul {
  display: flex;
}
ul li {
  list-style: none;
  margin: 13px;
  padding: 7px 15px;
}
ul li a {
  text-decoration: none;
  color: #fff;
}
ul li a:hover {
  color: #f2f2f2;
}
.copyright {
  margin: 20px;
  color: #fff;
}
</style>