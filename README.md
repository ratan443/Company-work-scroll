<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Auto Scrolling Logos</title>
<style>
  body {
    margin: 0;
    background: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 150px;
  }
  .slider {
    width: 80%;
    overflow: hidden;
    border: 1px solid #ddd;
    background: white;
    border-radius: 8px;
  }
  .slider-track {
    display: flex;
    width: max-content;
    animation: scroll-left 20s linear infinite;
  }
  .slider-track:hover {
    animation-play-state: paused;
  }
  .slider-track img {
    height: 100px;
    margin: 0 20px;
    user-select: none;
  }

  @keyframes scroll-left {
    0% {
      transform: translateX(0);
    }
    100% {
      transform: translateX(-50%);
    }
  }
</style>
</head>
<body>
  <div class="slider">
    <div class="slider-track" id="sliderTrack">
      <!-- Logos - add your own image URLs -->
      <img src="https://media.licdn.com/dms/image/v2/C4E0BAQHpQCGDze1ugw/company-logo_200_200/company-logo_200_200/0/1630635988434/civil_guru_ji_logo?e=2147483647&v=beta&t=hh_uBi9zf7wh0voD5a0iRdFjte--diQA1m9YjMjkW7E" alt="Civil Guruji" />
      <img src="https://socialseller.in/assets/logo-pF4RzNNw.png" alt="Socialseller" />
      <img src="https://www.bizgurukul.com/biz/img/biz_logo.svg?v=1.0" alt="Bizgurukul" />
      <img src="https://www.kreatorbee.com/web/image/website/1/logo/Kreator%20Bee?unique=956a759" alt="Creator Bee" />
      <img src="https://houmeindia.com/wp-content/uploads/2023/08/LOGO--140x47.jpg" alt="Houme" />
      

</body>
</html>
