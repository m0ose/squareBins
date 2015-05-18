# squareBins
put 2d data into square bins

simple library to bin 2d data into equally sized bins. 

Example
```
 new squareBins({minX:-106.5, maxX:-105, minY:39, maxY:40, width:10, height:10})
 bins4.addPoint(-106.8, 35.6, "almost a city")
 bins4.addPoint(-106.83, 35.6, "a house")
 bins4.forEachBin_zigzag( function(bin) {
    if( bin.length > 0 ) {
      bin.forEach(function(v){ console.log(v.x, v.y, v.val})
    }
  })

```


        
