<link rel="stylesheet" href="https://unpkg.com/7.css">

<style>

/* --------------- crt effect */
.crt::before {
  content: " ";
  display: block;
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%), linear-gradient(90deg, rgba(255, 0, 0, 0.06), rgba(0, 255, 0, 0.02), rgba(0, 0, 255, 0.06));
  background-size: 100% 2px, 3px 100%;
  z-index: 9999;
  pointer-events: none;
}
/* --------------- */

/* --------------- stylistic */
.bodystyle {
  font-family: "MS gothic", monospace;
  font-size: 17px;
  color: black;
  link-color: #474747;
  link-color-hover: #828282;
}

.bodystylesmall {
  font-family: "MS gothic", monospace;
  font-size: 12px;
  color: black;
  link-color: #474747;
  link-color-hover: #828282;
}

.filter{
  filter: grayscale(90%) sepia(10%) hue-rotate(10deg) blur(1px);
}

.float-img {
  float: left;
  margin-right: 15px;
}

.gif{
  filter: grayscale(90%) sepia(10%) hue-rotate(10deg) blur(1px);
  float: left;
  margin-right: 15px;
}
/* --------------- */
  
</style>

<html>
<div class=crt></div>

<div class="background">
  <div class="window glass active" style="max-width: 100%; margin: 0 1.5em; --w7-w-bg: #646464;">
    <div class="title-bar">
      <div class="title-bar-text">⚞^. .^⚟</div>
      <div class="title-bar-controls">
        <button aria-label="Minimize"></button>
        <button aria-label="Close"></button>
      </div>
    </div>
    <div class="window-body has-space">
      <img src="https://media.tenor.com/beR4n2WOfGcAAAAM/jason-todd.gif" width= 170 height=170 class=gif>
      <span class=bodystyle>
      ㅤ            ﹒    <b>K N I G H T</b>  ﹕☆<br>
hihi, i'm knight. i like art and coding and music. i'm 16, a pisces, and a lesbian ˆ𐃷ˆ
      </span>
      <details>
  <summary><span class=bodystyle>interests</span></summary>
  <p class=bodystylesmall>-arkham trilogy<br>-dc comics<br>-mcu<br>-steven universe</p>
</details>
    </div>
  </div>
</div>

</html>
