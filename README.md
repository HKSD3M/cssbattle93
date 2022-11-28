<div a>

  <div b></div>
  
  <div c><div c2></div></div>
  <div c1></div>

  
  <div d><div d2></div></div>
    <div d1></div>

  
  <div e><div e2></div></div>
   <div e1></div>
  
  
</div>



<style>


  [c1]{
    background:var(--cl4);
    position:absolute;
    top:166;
    width:20;
    height:16;
    left:200;
    transform: skewY(-33deg);
     
  }

   [d2] ,[c2] ,[e2]{
    background:var(--cl3);
    position:relative;
   width:80;
    height:16;
    left:120;
    top:-13;

     
  }
 
    [d1]{
    background:var(--cl4);
    position:absolute;
    top:192;
    width:20;
    height:16;
    left:200;
    transform: skewY(-33deg);
     
  }
  
     [e1]{
    background:var(--cl4);
    position:absolute;
    top:217;
    width:20;
    height:16;
    left:200;
    transform: skewY(-33deg);
     
  }
body{
  margin:0;
  display:flex;
  justify-content:center;
  align-items:center;
    background:var(--cl1);
}
  :root{
    --cl1:#4F77FF;
    --cl2:#191919;
    --cl3:#F9E492;
    --cl4:#D6B73F;
  }
  [c]{
    background:var(--cl3);
    position:relative;
    top:82;
    width:100;
    height:16;
    
    
  }
  [d]{
      background:var(--cl3);
    position:relative;
    top:92;
    width:100;
    height:16;
  }
    [e]{
      background:var(--cl3);
    position:relative;
    top:102;
    width:100;
    height:16;
  }
  [b]{
    position:relative;
   top:40;
    left:40;
    background:var(--cl3);
    border-radius:100%;
    height:40;
    width:40;
   
  }
  [a]{
    background:var(--cl2);
    border-radius:100%;
    width:200;
    height:200;
    overflow:hidden;
  
  }
  
</style>

