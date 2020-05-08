<template>
  <div class="portfolios-wrapper">
    <h2>Portforlios</h2>
        
        <ul class="portfolios">

          <li class="card">
            <img class="card-img" src="../assets/images/kanto-hamachacha_card.jpg"  alt="関東ハマチャチャ同好会キャプチャ">
            <div class="card-content">
              <h1 class="card-title jp">所属ダンスチーム公式サイト</h1>
              <p class="card-text">Webマーケティングからの観点も組み込む。</p>
              <p class="card-lang">Languages : HTML, CSS, JavaScript, PHP</p>
              <br>
              <a href="https://www.kanto-hamachacha.com/" class="card-link">Website</a>
              <a href="https://github.com/chibahiro0514/kanto-hamachacha" class="card-link github-link">Github</a>
            </div>
          </li>

          <li class="card">
            <img class="card-img" src="../assets/images/chibahiroportfolio2.png"  alt="ここにはポートフォリオ入れたい">
            <div class="card-content">
              <h1 class="card-title jp">ポートフォリオサイト</h1>
              <p class="card-text">こちらのサイト、Vue.jsを用いて作成。</p>
              <p class="card-lang">Languages : HTML, CSS, JavaScript(Vue.js)</p>
              <br>
              <a href="https://github.com/chibahiro0514/myportfolio" class="card-link github-link">Github</a>
            </div>
          </li>

        </ul>

  </div>
</template>

<style>
.portfolios-wrapper{
  text-align:center;
}

.portfolios{
  list-style-type: none;
  padding-left: 0;
  padding-left: 5%;
  padding-right: 5%;
  text-align:center;
}

.jp{
  font-weight: 100;
}

.card-lang{
  font-weight: 500;
}

.card {
  display: inline-block;
  margin: 30px 45px;
  width: 350px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
}

.card-img {
  border-radius: 5px 5px 0 0;
  width: 100%;
  height: auto;
  border-bottom: solid 1px #ccc;
}

.card-content {
  padding: 20px;
}

.card-title {
  font-size: 20px;
  margin-bottom: 20px;
  text-align: center;
  color: #333;
}

.card-text {
  color: #777;
  font-size: 14px;
  line-height: 1.5;
}

.card-link{
  border: 1px solid #00aaff;
  text-decoration: none;
  color: #00aaff;
  margin: 0 10px;
  padding: 5px 10px;
  border-radius: 5px;
}

.card-link:hover {
  font-weight: 700;
}

.github-link{
  border-color: #171515;
  color: #171515;
}

@media (max-width: 1020px) and (min-width: 768px) { }

@media (max-width: 767px) { 

  .card {
    margin: 30px 0px;
    width: 320px;
}

}


</style>