                                  Array methods

arreyda malumotlarni olib tashlash yokida qoshish usullari mavjud.

let arr = ["I", "go", "home"];

arr.push("dunyo")

<!--
console.log(["I", "go", "home", "dunyo"])
 -->

elementlarni oxiriga qo'shadi,

//////////////////////////////////////////////////////////////////////

arr.pop()

<!--
console.log(["I", "go", "home"])
 -->

elementni oxiridan chiqaradi,

/////////////////////////////////////////////////////////////

arr.shift()

<!--
console.log(["go", "home", "dunyo"])
 -->

elementni boshidan chiqaradi,

/////////////////////////////////////////////////////////////

arr.unshift("Abdug'ani")

<!--
console.log(["Abdug'ani", "I", "go", "home", "dunyo"])
 -->

boshiga elementlar qo‘shadi.

///////////////////////////////////////////////////////////

massivdan elementni ochirish

let arr = ["I", "go", "home"];

<!-- delete arr[1]; // remove "go"; -->

//////////////////////////////////////////////////////////////

arraydan malumotlarni ochirish uchun splice dan foydalanamiz

<!--
    let arr = ["I", "study", "JavaScript"];
    arr.splice(1, 1); // from index 1 remove 1 element
    alert( arr ); // ["I", "JavaScript"]
 -->

<!--
    let arr = ["I", "study", "JavaScript", "right", "now"];
    arr.splice(0, 3, "Let's", "dance");
    alert( arr ) // now ["Let's", "dance", "right", "now"]
 -->

////////////////////////////////////////////////////////////

splice orqali element qoshish uchun

<!--
    let arr = ["I", "study", "JavaScript"];
    then insert "complex" and "language"
    arr.splice(2, 0, "complex", "language");
    alert( arr );

    "I", "study", "complex", "language", "JavaScript"
 -->

//////////////////////////////////////////////////////////////

slice bilan massivdan elementlarni qirqib olamiz

arr.slice([start], [end])

<!--
    let arr = ["t", "e", "s", "t"];
    alert( arr.slice(1, 3) ); // e,s (copy from 1 to 3)
    alert( arr.slice(-2) ); // s,t (copy from -2 till the end)
 -->

////////////////////////////////////////////////////////////////////

let arr = [1, 0, false];

<!--
    alert( arr.indexOf(0) ); // 1
    alert( arr.indexOf(false) ); // 2
    alert( arr.indexOf(null) ); // -1
 -->

 indexOf massivdan qidiradi bolsa indexisini qaytaradi aks holda -1 qaytaradi
