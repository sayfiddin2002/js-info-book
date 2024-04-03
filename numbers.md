                            Numbers (Raqamlar)


Javascriptdagi oddiy raqamlar 64-bitli !EEE-754 formatida saqlanadi.

BigInt raqamlari ixtiyoriy uzunlikdagi butun sonni ifodalaydi.


<!-- Tasavvur qiling, biz 1 milliard yozishimiz kerak. Aniq yo'l: -->

let billion = 1000000000;

<!-- _Biz pastki chiziqni ajratuvchi sifatida ham ishlatishimiz mumkin : -->


let billion = 1_000_000_000;


<!-- let billion = 1e9;  // 1 billion, literally: 1 and 9 zeroes

alert( 7.3e9 );  // 7.3 billions (same as 7300000000 or 7_300_000_000) -->


Yaxlitlash

Raqamlar bilan ishlashda eng ko'p qo'llaniladigan operatsiyalardan biri yaxlitlashdir.

Yaxlitlash uchun bir nechta o'rnatilgan funktsiyalar mavjud:

Math.floor
Pastga yaxlitlanadi: 
<!-- console.log(Math.floor(2.3)) // (2) -->

Math.ceil
Yaxlitlanadi:
<!-- console.log(Math.ceil(2.3)) // (3) -->

Math.round
Eng yaqin butun songa yaxlitlanadi: 3.1 bo'ladi 3, 3.6 bo'ladi 4, o'rta kattalik: ham 3.5 yaxlitlanadi 4.