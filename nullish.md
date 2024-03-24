                           Nullish

Nullish operatore chaptan o'ngga qarab oqiydi. null yoki undifinedga tekshiradi.
birinchi kelgan true qiymatni qaytaradi, agar true qiymat bolmasa ohirgisini qaytaradi

let m;
let n = null;
let c = 2;
let a;
console.log(m ?? n ?? c ?? a); (c)

let m;
let n = null;
let a;
console.log(m ?? n ?? a);   (a)
