# Right-Click-Php
A WorkingPlace WebDevelopment and App Making

<!DOCTYPE html> 
<html> 
 
<head> 
 <meta name="viewport" content="width=device-width, initial-scale=1.0" /> 
 
 <style> 
  .name { 
   color: green; 
   font-size: 25px; 
  } 
   
  .mark { 
   color: red; 
   font-size: 20px; 
  } 
 </style> 
 
</head> 
 
<body> 
 
 
 <?php 
$name="RightClick Results";
 $name="Tshepo Limba"; 
 $mark1=90; 
 $mark2=89; 
 $mark3=197; 
 ?> 
 
  <div> 
   
   <span class="name">Name  :</span> 
   <?php echo $name; ?> 
   <br> 
   <br> 
   <span class="mark">Mark 1 :</span> 
   <?php  
  
 if($mark1<70) 
   echo "Fail"; 
 else if($mark1>=70 && $mark1<=89) 
   echo "Just pass"; 
 else if($mark1>89 && $mark1<=120) 
   echo "Good"; 
 else if($mark1>120 && $mark1<=150) 
   echo "Very good"; 
 else if($mark1>150 && $mark1<=200) 
   echo "Excelent"; 
?> 
 
 
   <br> 
   <span class="mark">Mark 2 : </span> 
   <?php  
  
 if($mark2<70) 
   echo "Fail"; 
 else if($mark2>70 && $mark2<=89) 
   echo "Just pass"; 
 else if($mark2>89 && $mark2<=120) 
   echo "Good"; 
 else if($mark2>120 && $mark2<=150) 
   echo "Very good"; 
 else if($mark2>150 && $mark2<=200) 
   echo "Excelent"; 
?> 
 
 
   <br> 
   <span class="mark">Mark 3 : </span> 
   <?php  
  
 if($mark3<70) 
   echo "Fail"; 
 else if($mark3>70 && $mark3<=89) 
   echo "Just pass"; 
 else if($mark3>89 && $mark3<=120) 
   echo "Good"; 
 else if($mark3>120 && $mark3<=150) 
   echo "Very good"; 
 else if($mark3>150 && $mark3<=200) 
   echo "Excelent"; 
?> 
 
  </div> 
 
</body> 
 
</html>
