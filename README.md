# test2

<link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />

<div class="swiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide"><img src="https://dl.gitea.com/screenshots/home_timeline.png" alt="Photo 1" /></div>
    <div class="swiper-slide"><img src="https://dl.gitea.com/screenshots/user_profile.png)" alt="Photo 2" /></div>
    <div class="swiper-slide"><img src="https://dl.gitea.com/screenshots/global_issues.png" alt="Photo 3" /></div>
  </div>
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
</div>

<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
<script>
  const swiper = new Swiper('.swiper', {
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
    loop: true,
  });
</script>
