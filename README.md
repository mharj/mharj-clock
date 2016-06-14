# mharj-clock
Polymer web Element

### Bower setup
```json
  "dependencies": {
    
    "mharj-clock": "https://github.com/mharj/mharj-clock.git"

  }
```
### Options
```javascript
  element.shadow = 173; // shadow angle
  // use i.e. with SunCalc
  var pos = SunCalc.getPosition(new Date(), 60.3, 23.1);
  element.shadow = (pos.azimuth*180/Math.PI);
```
