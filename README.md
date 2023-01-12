# Array-object-filtering
 
var young = people.filter((obj) => {
 var flag = false;
 Object.values(obj).forEach((val) => {
 if(String(val).indexOf("J") > -1) {
 flag = true;
 return;
 } 
 });
 if(flag) return obj;
});
