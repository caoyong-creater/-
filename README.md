/*周几的获取*/

<script>     
  var time = new Date();    
  console.log(time); // 获取最新日期，年月日，时分秒     // 获取周几     
  var week = time.getDay() ;   // 0-6七个数字      console.log( week )      
  // if 三元运算符，范围条件判断 1-100,精确条件判断    
  switch (week){    
  case 1:            
  week = '星期一';           
  break;        
  case 2:          
  week = '星期二';          
  break;         
  case 3:          
  week = '星期三';          
  break;        
  case 4:          
  week = '星期四';      
  break;      
  case 5:         
  week = '星期五';       
  break;   // 符合条件后中断执行，跳出循环      
  case 6:            
  week = '星期六';        
  break;        
  case 0:         
  week = '星期天'     }   
  console.log( week ) 
</script>
