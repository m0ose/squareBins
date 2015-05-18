# squareBins
put 2d data into square bins

simple library to bin 2d data into equally sized bins. 

Example
```
var bins = new squareBins({minX:-107, maxX:-105, minY:34, maxY:38, width:10, height:10})
bins.addPoint(-106.84, 35.6, "almost a city")
bins.addPoint(-106.83, 35.6, "a house")
bins.forEachBin_zigzag( function(bin) {
  if( bin.length > 0 ) {
    console.log('going into bin')
    bin.forEach(function(v){ 
      console.log(v.x, v.y, v.val)
    })
  }
})
```


        
