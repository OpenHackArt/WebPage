<template>
  <div class="root">
    <Demo />
    <h1>Open Hack Art</h1>
    <div class="main">
      <div>Welcome to my site.</div>
      <div>
        This is the personal site Open Hack Art by Yuqing Chen, dedicated to
        creating art with programming.
      </div>
      <div>
        I am a crazy computer graphics enthusiast, also interested in game
        programming, creative programming, and front-end.
      </div>
      <div>
        I currently live in Beijing and graphics programming is my lifelong
        pursuit.
      </div>
      <div>If you want to contact me, don't hesitate to send me an email.</div>

      <div class="outsite">
        <ul>
          <li>
            Email:
            <a href="mailto:chenyuqing0429@foxmail.com"
              >chenyuqing0429@foxmail.com</a
            >
          </li>
          <li>
            GitHub:
            <a href="https://github.com/scyq">https://github.com/scyq</a>
          </li>
          <li>
            itch.io: <a href="https://scyq.itch.io/">https://scyq.itch.io/</a>
          </li>
          <li>
            zhihu:
            <a href="https://www.zhihu.com/column/c_1279104020465152000"
              >https://www.zhihu.com/column/c_1279104020465152000</a
            >
          </li>
          <li>
            Blog (no more update):
            <a href="https://www.cnblogs.com/scyq/"
              >https://www.cnblogs.com/scyq/</a
            >
          </li>
        </ul>
      </div>
    </div>
    <div class="footer">
      Open Hack Art 2021 Yuqing Chen. All rights reserved.
    </div>
    <!-- <img src="https://picsum.photos/1920/200" /> -->
  </div>
</template>

<script>
import Demo from "./Demo";
export default {
  name: "HelloWorld",
  components: {
    Demo,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  margin-top: 30px;
}

.root {
  display: flex;
  flex-direction: column;
  align-content: center;
}

.main {
  font-size: 24px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin: 0 30px 30px 30px;
}

.outsite {
  margin: 20px 0 0 0;
  font-size: 20px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

h1 {
  font-size: 40px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
li {
  display: block;
  list-style: none;
  text-align: start;
}
a {
  color: #42b983;
}
</style>
