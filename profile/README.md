This is dedicated to the development repository of the digital Javanese Calendar.

[Javanese Calendar Library](https://github.com/kalenderjawa/pustaka)

**Pustaka** is a JavaScript library for the Javanese Calendar.

> The Javanese Calendar is a lunar-based calendar system. Javanese people have used it for many purposes in daily life up to the present day since the 14th century.

**Mathematical Formula of the Javanese Calendar**

The Javanese Calendar is based on mathematics and has been preserved from generation to generation through mathematical formulas. Ironically, not many of the younger generation know or are aware of this knowledge.

![Mathematical Formula of the Javanese Calendar](https://assets.caknun.com/media/2019/01/20190102-menek-kalender-4.jpg)

[(*image source*)](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat)

## **API**

This API is easy to use. For example, if you want to find the mathematical formula for the month `romadon` in the Javanese year 1952:

```javascript
KalenderJawa.cariRumusAbadiAwalBulanTahunJawa('romadon', 1952).then(data => {

console.log(`${data.rumus.wulan.wulan}_${data.rumus.dino}_${data.rumus.pasaran}`)

// romadon_7_4 (don tu pat)

})
```

