# Interactive-SD-map
 An html page showing data about the states of Sudan

## Get Started
go to line 60 and modifie it to your data
```js
const cityData = [ // Replace with your actual city data
      { key: "SD_DC", value: 3, color: "blue" }, // Custom color provided
      { key: "SD_DE", value: 6 },
      { key: "SD_DN", value: 5 },
      { key: "SD_DS", value: 0 },
      { key: "SD_DW", value: 0 },
      { key: "SD_GD", value: 0 },
      { key: "SD_GK", value: 0 },
      { key: "SD_GZ", value: 0 },
      { key: "SD_KA", value: 0 },
      { key: "SD_KH", value: 0 },
      { key: "SD_KN", value: 0 },
      { key: "SD_KS", value: 0 },
      { key: "SD_NB", value: 0 },
      { key: "SD_NO", value: 0 },
      { key: "SD_NR", value: 0 },
      { key: "SD_NW", value: 0 },
      { key: "SD_RS", value: 0 },
      { key: "SD_SI", value: 0 },
      // ... (other city data)
    ];
```
if No color field found then the color will be red for value < 0, gray for value === 0 and green for value > 0
