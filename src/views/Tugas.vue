<template>

<div class="awal">
    <h1>Section1 <span>Section2</span></h1>
    <img alt="logo" src="../assets/Group 522.png">
</div>
<div class="aku1">
    
    <BCarousel ref="myCarousel" :interval="2500" controls indicators ride="carousel">
        <h1>hallo</h1>
    <BCarouselSlide img-src="https://picsum.photos/1024/480/?image=25" />
    <BCarouselSlide img-src="https://picsum.photos/1024/480/?image=26" />
    <BCarouselSlide img-src="https://picsum.photos/1024/480/?image=27" />
  </BCarousel>
  </div>
  <div class="page2">
    <h1>About</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae ab veritatis
         vitae aperiam ipsam iure voluptatibus qui error quis, molestiae id inventore 
         ratione eius, odit tenetur. Quisquam, quam sint nostrum laboriosam blanditiis 
         consectetur, aperiam explicabo placeat minima accusantium ea? Unde ad esse nesciunt neque iste ut, officia
         perferendis accusamus perspiciatis dolore alias fugit pariatur impedit earum iure, fuga nostrum.
          Repellat quisquam necessitatibus quia libero vero nihil sequi quo earum eligendi?</p>
  </div>
</template>

<script>
export default {
  name: 'MyComponent',
}
</script>
<style lang="scss">
/* Import file SCSS */
@import '../assets/sass/main.scss';
</style>