This is dedicated repository for the development of digital Javanese Calendar. 

[Pustaka Kalender Jawa](https://github.com/kalenderjawa/pustaka)

**Pustaka** is JavaScript library for Javanese Calendar.

> Javanese calendar is a moon-based calendar system. Javanese using it for many purposes in daily life till these days since the 14th century.

 
**Javanese Calendar Math Formula**

Javanese calendar is an arithmetic-based calendar and passed from generation to the next generation by math formulas. Ironically not so many new generations know or are aware of the knowledge.

![Javanese Calendar Math Formula](https://cdn.caknun.com/media/2019/01/20190102-menek-kalender-4.jpg)
[(*sumber gambar*)](https://www.caknun.com/2019/kalender-jowo-digowo-kalender-arab-digarap-kalender-barat-diruwat)

API

The API is easy to use for example if you want to know what the math formula month of `romadon` on javanese year 1952,

```javascript
KalenderJawa.cariRumusAbadiAwalBulanTahunJawa('romadon', 1952).then(data => {
  console.log(`${data.rumus.wulan.wulan}_${data.rumus.dino}_${data.rumus.pasaran}`)
  // romadon_7_4 (don tu pat)
})
```

Please go to [official website of kalender jawa](https://kalenderjawa.dev/api/) for other API usage and documentation.
