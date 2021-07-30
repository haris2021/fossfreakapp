<template>
   
    <div class="hello">
                     
                      <h1>{{msg}}</h1>
                      <h4>
                            Fossfreaks Private Limited is a Private incorporated on 24 May 2020. It is classified as Non-govt company and is registered at Registrar of Companies, Chennai.
                            <br> Its authorized share capital is Rs. 100,000 and its paid up capital is Rs. 100,000. It is inolved in Other computer related activities.
                      </h4>

                      <h3>Directors of Fossfreaks Private Limited are <b> Muthukumaraswami, Prabakaran and Mageshbabu Kasimani. </b> </h3>

                      <h5>Address: 316, SENGAZHANIYAMMAN KOIL ST,MANAMPATHY VILLAGE AND POST Kancheepuram Kancheepuram TN 603105 India </h5>

                      <div class="links">
                                    
                                    <h2>Contact us :</h2>
                                    <h3>Linkedin - <a href="https://www.linkedin.com/company/fossfreaks/" >Fossfreaks private limited</a></h3>
                                    <h3>Email ID: prabakarangthd@gmail.com</h3>
                      </div>

                    <div class="content">

                      <h2>The best way to predict future is to CREATE IT</h2>

                    </div>

                      <div class="images">
                                   
                                   
                                   <div id="one">
                                        <img src="https://media-exp3.licdn.com/dms/image/C5103AQEI2DZO8QAXwQ/profile-displayphoto-shrink_100_100/0/1570250100949?e=2159024400&v=beta&t=kB-KNybikd29Qq_PwJwga5d3yDHUmPjVL9VExQeeQY4">
                                   </div>
                                   
                                   <div id="two">
                                             <img src="https://media-exp1.licdn.com/dms/image/C5603AQFaGVCRRMGWEQ/profile-displayphoto-shrink_100_100/0/1619513865012?e=2159024400&v=beta&t=9ABEcZRkZCn4204qDGlxetZTFu1ShfSe4UtxFoopyOE">
                                   </div>

                                   <div id="three">
                                                <img src="https://media-exp3.licdn.com/dms/image/C5603AQFZLfrCMEGANA/profile-displayphoto-shrink_100_100/0/1622193058669?e=2159024400&v=beta&t=VmAH-87RPLyKd3k76CjqDe8nIcR3Niw-jvGVkDfeNqo">
                                   </div>
                      </div>

                      <div class="logo">
                              <img src="https://media-exp1.licdn.com/dms/image/C561BAQHsNgZL-PZKAA/company-background_10000/0/1595768191532?e=2159024400&v=beta&t=iJZUJrVh_-IOVt9cAlsxmOpdjnLxis5BFDDg2Jpz0Sw">
                      </div>

    </div>

    
</template>

 <script>

 export default {
   name: 'HelloWorld',
   props: {
     msg: String
   }
 }

 </script>

<style scoped>
                  
                  .links{
                        text-align: left;
                        margin-left: 50px;
                        margin-top:60px;
                        color:black;
                  }

                  .hello{

                     background-color: antiquewhite;
                      padding-top:20px;
                      padding-bottom: 50px;
                  }

                  .images{
                          
                          display: flex;
                          justify-content: center;    
                          margin-top:20px;
                  }

                  #one{
                     padding-right: 50px;
                  }
                  #two{
                     padding-right: 50px;
                  }

                  #thre{
                     padding-right: 50px;
                  }

                  .logo{
                       
                          display: flex;
                          justify-content: center;    
                          margin-top:20px;
                          width: 300px;
                          height: 150px;      
                          margin-left: 600px;
                  }

                  .content{
                    margin-top:80px;
                  }
</style>