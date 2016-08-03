# mharj-clock
Polymer web Element

![Clock](clock.png?raw=true "Clock")

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
### Html
```html
  <mharj-clock id='clock' style='width: 150px;height 150px'></mharj-clock>
```

