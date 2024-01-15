<template>
    <div class="Home">
        <div class="first">
            <div class="content">
                <content />
            </div>
            <div class="picture">
                <div class="img_style">
                    <img src="../assets/home_img1.png" alt="">
                </div>
            </div>    
        </div>
        
        <div style="border-bottom: 2px solid #DCE1E4; padding-top: 7%; width: 85%;  margin: auto; margin-bottom: 5%; "></div>

        <div class="second">
            <p style="color: #FF014F; margin-left: 3%; font-size: 20px;">FEATURES</p>
            <h1 style="margin-left: 3%;">
                What I Do
            </h1>

            <div style="display: flex; flex-wrap: wrap; justify-content: center;">
                <div class="second_content">
                    <img src="../assets/second_image_one.jpg" style="width: 100%; padding-top: 5%; padding-bottom: 8%;">
                    <h2 style="padding-bottom: 8%;">Strategy</h2>
                    <p id="p1">
                        Brand Strategy, Product Strategy, Research & Analysis, Service Design, Content Strategy
                    </p>
                    <!-- <img id="arrowimg" src="../assets/right-arrow.png" style="width: 8%; padding-top: 4%; padding-bottom: 4%; color: white;"> -->
                </div>

                <div class="second_content">
                    <img src="../assets/second_image_two.jpg" style="width: 100%; padding-top: 5%; padding-bottom: 8%;">
                    <h2 style="padding-bottom: 8%;">Research</h2>
                    <p id="p1">
                        Brand Strategy, Product Strategy, Research & Analysis, Service Design, Content Strategy
                    </p>
                </div>


                <div class="second_content">
                    <img src="../assets/second_image_three.jpg" style="width: 100%; padding-top: 5%; padding-bottom: 8%;">
                    <h2 style="padding-bottom: 8%;">Design</h2>
                    <p id="p1">
                        Brand Strategy, Product Strategy, Research & Analysis, Service Design, Content Strategy
                    </p>
                </div>

                <div class="second_content">
                    <img src="../assets/second_image_four.jpg" style="width: 100%; padding-top: 5%; padding-bottom: 8%;">
                    <h2 style="padding-bottom: 8%;">Growth</h2>
                    <p id="p1">
                        Brand Strategy, Product Strategy, Research & Analysis, Service Design, Content Strategy
                    </p>
                </div>


                <div class="second_content">
                    <img src="../assets/second_image_five.jpg" style="width: 100%; padding-top: 5%; padding-bottom: 8%;">
                    <h2 style="padding-bottom: 8%;">CEO Marketing</h2>
                    <p id="p1">
                        Brand Strategy, Product Strategy, Research & Analysis, Service Design, Content Strategy
                    </p>
                </div>


                <div class="second_content">
                    <img src="../assets/second_image_six.jpg" style="width: 100%; padding-top: 5%; padding-bottom: 8%;">
                    <h2 style="padding-bottom: 8%;">Performance</h2>
                    <p id="p1">
                        Brand Strategy, Product Strategy, Research & Analysis, Service Design, Content Strategy
                    </p>
                </div>

            </div>

            

        </div>
    </div>
</template>

<script>
import content from '../components/home/content.vue'

export default{
    components: {
        content
    }
}
</script>

<style scoped>
.first{   
    width: 100%;
    height: 100%;
    display: flex;
}
.content{
    width: 55%;
    height: 95vh;
}
.picture{
    width: 45%;
    padding-top: 35px;
    height: 100%;    
}
.img_style{
    width: 80%;
    border-radius: 10px;
    padding: 15px;
    background-color: #E3E9ED;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: auto;
    box-shadow: 4px 10px 9px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    /* box-shadow: #E3E9ED; */
}   
.second{
    width: 90%;
    height: 100%;
    /* border: 2px solid red; */
    margin: auto;
    /* margin-top: 15%; */
}
h1{
    font-size: 55px;
    margin-top: 2%;
    color: #3C3E41;
    margin-bottom: 3%;
}
.second_content{
    
    background-color: #EBEFF1;
    padding: 2.5% 3% 2% 2.5%;
    border-radius: 8px;
    box-shadow: 1px 1px 5px 1px rgba(0,0,0,0.2);
    width: 25%;
    height: 30%;
    margin: 10px;
    transition: 0.3s;
    
}

.second_content:hover{
    background-image: linear-gradient(120deg, #796AC8 , #E26881);
    color: white;
    transition-delay: 0.1s;
    /* transition: 1s; */
    padding: 1.5% 3% 2% 2.5%;
    
}
#p1{
    line-height: 25px; 
    color: #3C3E41; 
    font-size: 20px; 
    padding-bottom: 10%;
}
.second_content:hover #p1{
    color: white;
}

.second_content:hover #arrowimg{
    display: block;
}



</style>