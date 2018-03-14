# Install

cordova plugin add https://github.com/FWiner/cordova-qdc-baidu-location --variable API_KEY="key"



# Usage:


    baidu_location.getCurrentPosition(
    function(data){
          console.log("success");
          alert(JSON.stringify(data));
          console.log(JSON.stringify(data));
      }, function(data){
        console.log("fail");
        console.log(data);
        alert(JSON.stringify(data));
    });
                
                
