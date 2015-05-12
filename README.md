# stockthai
Client api for stock exchang of thailand
client api  สำหรับ ดึงข้อมูลราคาหุ้นไทย

### Installing 
      
      npm install stockthai

### How to use
```js
var stockthai = require("stockthai");

var options = {stock_quotes: 'mint' };
stockthai.get(options,function(quote,result){

  console.log( "Current Price of  "+quote+" is ---->"+result.price);
  
  //see other fields  
  console.log(JSON.stringify(result));

});
```     
      
### Return object example
    {"name":"MINT","price":"31.75","company":"MINOR INTERNATIONAL PUBLIC COMPANY LIMITED ","prior":"31.00","open":"31.00","valume":"4,914,162","value":"154,433.18","pervalue":"1.00","height":"31.75","low":"31.00","ave  rage_price":"31.40","ceiling":"40.25","floor":"21.70"}
    
*Get data from settrade.com


