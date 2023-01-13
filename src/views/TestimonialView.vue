<template>
    <div class="testimonial">
        <!-- flipcard -->
        <div class="card-container">
            <div class="card-box">
                <div class="front">
                    <div class="imgContainer">
                        <img class="cardfront" src="https://i.postimg.cc/HW05c2FN/card-front.png" alt="">
                    </div>
                    <div class="back">
                        <img class="cardback" src="https://i.postimg.cc/Y965BZjk/card-back.png" alt="">
                        <div>
                            <h3> name surname</h3>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<!-- <style>
.front {
    min-height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
.container {
    transform-style: preserve-3d;
}
.container .card-box {
    position: relative;
    width: 300px;

    margin: 20px;
    transform-style: preserve-3d;
    perspective: 1000px;
    cursor: pointer;
}
.container .card-box .front .cardfront {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform-style: preserve-3d;
    transition: 0.9s ease;
}
.container .card-box .front .cardfront .imgContainer{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform-style: preserve-3d;
}
.container .card-box .front .cardfront .imgContainer{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.container .card-box .front .cardfront .back .cardback{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #333;
    backface-visibility: hidden;
    transform-style: preserve-3d;
    transform: rotateY(180deg);
}
</style> -->

<script>
import Testimonial from '@/views/TestimonialView.vue'
export default{
  views:{
    Testimonial
  }
}
</script>