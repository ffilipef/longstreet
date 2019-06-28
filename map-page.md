---
layout: default_map
title: Map Page
---
<div id="googleMap" style="width:100%;height:400px;"></div>

<script>
function myMap() {
var mapProp= {
  center:new google.maps.LatLng(39.91696377507728,-8.628558544377029),
  zoom:5,
};
var map = new google.maps.Map(document.getElementById("googleMap"),mapProp);
}
</script>

<script src="https://www.google.com/maps/d/u/0/embed?mid=1NJFHYqXvK5VEexmTJYwfweEcCDYy5ACB"></script>