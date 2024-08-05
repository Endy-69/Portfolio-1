.skills{
    min-height: auto;
    padding-bottom: 7rem;
    background: var(--bg-color);
    max-width: 70vw;
    align-items: center;
    margin-left: 10rem;
    justify-content: center;
    
   
  }
 .skills .skills-row{
    display: flex;
    flex-wrap: wrap;
    gap: 5rem;
    
 }
 .skills-row .skills-column{
    flex: 1 1 40rem;
    
    
 }
 .skills-column .title{
    font-size: 2.5rem;
    margin: 0 0 1.5rem;
 }
 .skills-box .skills-content{
    position: relative;
    border: .2rem solid var(--main-color);
    border-radius: .6rem;
    padding: .5rem 1.5rem;
    
 }
 .skills-content .progress{
   padding: 1rem 0;

 }
 .skills-content .progress h3 {
    font-size: 1.7rem;
    display: flex;
    justify-content: space-between;

 }
 .skills-content .progress h3 span {
    color: var(--text-color);

 }
 .skills-content .progress .bar{
   height: 2.5rem;
   border-radius: .6rem;
   border: .2rem solid var(--main-color);
   padding: .5rem;
   margin: 1rem 0;
  }
  .skills-content .progress .bar span{
    display: block;
    height: 100%;
    border-radius: .3rem;
    background: var(--main-color);
   }
   .skills-column:nth-child(1) .skills-content .progress:nth-child(1) .bar span{
    width: 70%;
   }
   .skills-column:nth-child(1) .skills-content .progress:nth-child(2) .bar span{
    width: 60%;
   }
   .skills-column:nth-child(1) .skills-content .progress:nth-child(3) .bar span{
    width: 40%;
   }
   .skills-column:nth-child(1) .skills-content .progress:nth-child(4) .bar span{
    width: 40%;
   }
   .skills-column:nth-child(1) .skills-content .progress:nth-child(5) .bar span{
    width: 50%;
   }

   .skills-column:nth-child(2) .skills-content .progress:nth-child(1) .bar span{
    width: 85%;
   }
   .skills-column:nth-child(2) .skills-content .progress:nth-child(2) .bar span{
    width: 90%;
   }
   .skills-column:nth-child(2) .skills-content .progress:nth-child(3) .bar span{
    width: 100%;
   }
   .skills-column:nth-child(2) .skills-content .progress:nth-child(4) .bar span{
    width: 90%;
   }
   .skills-column:nth-child(2) .skills-content .progress:nth-child(5) .bar span{
    width: 85%;
   }

   
 
       


.about-img img {
    width: 35vw;
}
 .about-img img {
        width: 70vw;
        margin-top: -2rem;
 }
 @media (max-width: 365px) {
    .about-img img {
        width: 90vw;
    }
}
.about-img{
    position: relative;
    width: 40rem;
    height: 40rem;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    }
