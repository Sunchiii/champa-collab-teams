<template>
  <div class="footer">
    <div class="btn-box">
      <div class="footer-top">
        <h1>Get in Touch With Us</h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut,
          cupiditate.<br />Hi barcelona
        </p>
        <input
          type="text"
          placeholder="Search Google or type a URL"
          class="input"
        />
        <a href="" class="button">Search</a>
      </div>
      <div class="footer-bottom">
        <div class="box">
          <div class="menu-1">
            <h1>Compareoffers</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel,
              repellendus nobis eius soluta doloribus accusantium vitae beatae
              laudantium debitis commodi asperiores eaque.
            </p>
          </div>
          <div class="box-menu">
            <div class="menu-2">
              <h1>Company</h1>
              <p>About</p>
              <p>Blog</p>
              <p>News</p>
              <p>Press Releases</p>
              <p>Contact Us</p>
            </div>
            <div class="menu-2">
              <h1>Learn more</h1>
              <p>Support</p>
              <p>Developers</p>
              <p>Referral Program</p>
              <p>Affiliate Program</p>
              <p>Reseller Program</p>
            </div>
            <div class="menu-2">
              <h1>Follow</h1>
              <p>Facebook</p>
              <p>Instagram</p>
              <p>Twitter</p>
              <p>You Tube</p>
            </div>
          </div>
        </div>
      </div>
      <div class="flex-string">
        <div class="string">
          <p>Mydev@2336gmail.com</p>
          <p>Phonesavang</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.footer {
  height: auto;
  width: 100%;
  background-color: #1978d1;
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
}
.btn-box {
  padding-top: 2rem;
  padding-bottom: 3rem;
}
.footer-top {
  text-align: center;
}
.footer-top h1 {
  font-size: 30px;
}
.footer-top p {
  margin-top: 0.5rem;
  margin-bottom: 12px;
}
.input {
  margin-top: 1.5rem;
  width: 350px;
  height: 30px;
  outline: none;
  border: none;
  border-radius: 4px;
  padding-left: 2rem;
  background-color: #fff;
  color: #000;
  font-size: 12px;
}
.button {
  padding: 7px 10px;
  border-radius: 4px;
  margin-left: 1rem;
  background-color: #dc143c;
  transition: 0.3s;
}
.button:hover {
  box-shadow: 3px 3px 8px #333;
}
.footer-bottom {
  margin-top: 2rem;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  /* border: 1px solid red; */
}
.box {
  display: flex;
  width: 70%;
  height: auto;
  padding: 2rem 0;
  border-top: 1px solid #fff;
  border-bottom: 1px solid #fff;
}
.menu-1 {
  max-width: 100%;
  width: 300px;
  height: auto;
  /* overflow: hidden; */
}
.box-menu {
  display: flex;
  justify-content: space-evenly;
  width: 90%;
  /* border: 1px solid red; */
}
.menu-2 {
  cursor: pointer;
}
.menu-1 h1,
.menu-2 h1 {
  margin-bottom: 1rem;
  font-size: 25px;
}
.menu-2 p {
  margin-top: 5px;
  transition: 0.3s;
}
.menu-2 p:hover {
  opacity: 0.5;
}
.flex-string {
  display: flex;
  justify-content: center;
}
.string {
  width: 70%;
  margin-top: 1rem;
  display: flex;
  justify-content: space-between;
}
.string p {
  cursor: pointer;
}
</style>

