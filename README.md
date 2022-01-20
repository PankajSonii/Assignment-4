# Assignment-4

var xhr = new XMLHttpRequest();

xhr.open("GET","http://api.countrylayer.com/v2/all?access_key=edd0cff317f397fa95cb23c13a3fa45d");

xhr.onload=function(){
  if(xhr.status >= 200 && xhr.status <300){
    var data=JSON.parse(xhr.responseText);
    console.log(data)

  }
}
xhr.send() 

OUTPUT

![image](https://user-images.githubusercontent.com/93160517/150324741-24769408-e50d-475b-a7fd-285b89f1ab28.png)

