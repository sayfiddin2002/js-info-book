                                 Map and Sat

Map


Map - bu xuddi Object. Ammo asosiy farq shundaki, Map har qanday turdagi kalitlarga ruxsat beriladi.

Usullari va xususiyatlari quyidagilardir:

new Map()- mapni yaratadi.
map.set(key, value)– qiymatni kalit orqali saqlaydi.
map.get(key)undefined– agar key mapda mavjud bo‘lmasa , kalit orqali qiymatni qaytaradi .
map.has(key)true- agar key mavjud bo'lsa keyni qaytaradi , aks holda falseni.
map.delete(key)– elementni (kalit/qiymat juftligi) kalit yordamida olib tashlaydi.
map.clear()- mapdan hamma narsani olib tashlaydi.
map.size– joriy elementlar sonini qaytaradi.

Masalan; misol uchun:

let map = new Map();

map.set('1', 'str1'); // a string key
map.set(1, 'num1'); // a numeric key
map.set(true, 'bool1'); // a boolean key

alert( map.get(1) ); // 'num1'
alert( map.get('1') ); // 'str1'

alert( map.size ); // 3

/////////////////////////////////////////////////////////////////////////

map ustida takrorlash

map.keys()– kalitlar uchun iteratsiyani qaytaradi,
map.values()– qiymatlar uchun iteratsiyani qaytaradi,
map.entries()– yozuvlar uchun iteratsiyani qaytaradi [key, value], u sukut boʻyicha for..of.

Masalan; misol uchun:

let recipeMap = new Map([
['cucumber', 500],
['tomatoes', 350],
['onion', 50]
]);

<!-- iterate over keys (vegetables)
for (let vegetable of recipeMap.keys()) {
alert(vegetable); // cucumber, tomatoes, onion
}

iterate over values (amounts)
for (let amount of recipeMap.values()) {
alert(amount); // 500, 350, 50
}

iterate over [key, value] entries
for (let entry of recipeMap) { // the same as of recipeMap.entries()
alert(entry); // cucumber,500 (and so on)
} -->


//////////////////////////////////////////////////////////////////////////

Set 


Set- bu maxsus turdagi to'plam - "qiymatlar to'plami" (kalitlarsiz), unda har bir qiymat faqat bir marta bo'lishi mumkin.

Uning asosiy usullari quyidagilardir:

1. new Set([iterable])– to‘plamni yaratadi va agar iterableob’ekt taqdim etilsa (odatda massiv), undan qiymatlarni to‘plamga ko‘chiradi.
2. set.add(value)– qiymat qo‘shadi, to‘plamning o‘zini qaytaradi.
3. set.delete(value)– qiymatni olib tashlaydi, trueagar valueqo'ng'iroq paytida mavjud bo'lsa, qaytaradi, aks holda false.
4. set.has(value)true– qiymat to‘plamda mavjud bo‘lsa, qaytaradi , aks holda false.
5. set.clear()- to'plamdan hamma narsani olib tashlaydi.
6. set.size- elementlarni hisoblash.
7. Asosiy xususiyat shundaki, set.add(value)bir xil qiymatdagi takroriy qo'ng'iroqlar hech narsa qilmaydi. Shuning uchun har bir qiymat Setfaqat bir marta paydo bo'ladi.

Misol uchun, bizga tashrif buyuruvchilar bor va biz hammani eslashni xohlaymiz. Ammo takroriy tashriflar dublikatlarga olib kelmasligi kerak. Mehmon faqat bir marta "hisoblanishi" kerak.

Set Buning uchun to'g'ri narsa:

let set = new Set();

let john = { name: "John" };
let pete = { name: "Pete" };
let mary = { name: "Mary" };

// visits, some users come multiple times
set.add(john);
set.add(pete);
set.add(mary);
set.add(john);
set.add(mary);

// set keeps only unique values
alert( set.size ); // 3

for (let user of set) {
  alert(user.name); // John (then Pete and Mary)
}