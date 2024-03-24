                           Variables (o'zgaruvchilar)
Javascriptda 3 ta o'zgaruvchi mavjud, ular: let, var, const;

var - function-scope. hostingda ishlaydi lekin undifined qaytaradi.
bir hil nom bilan qayta elon qilinsa ishlaydi.

let - block scope hoistingda ishaydi error qaytaradi

const - hoistingda ishlaydi lekin error qaytaradi.

var va letga qiymat berib uni ozgartirsa boladi.
lekin constga berilgan qiymatni o'zgartirib bolmaydi.

masalan:

let a = 50;
let b;
console.log(b = a) 
<!-- javob (50) -->

const name = 'Aziz';
const name2;
console.log(name2 = name)
<!-- SyntaxError qaytaradi -->
chunki const o'zgarmas boladi

<!-- o'zgaruvchilarni tog'ri nomlash kerak -->

masalan: 
let name:

<!-- notog'ri nomlab bolmaydi  -->

masalan: 
var 1user:
boshida raqam bilan yozib bolmaydi.

agar bir nechta soz qatnashgan bolsa camelcase uselida yoziladi
const userName:

<!-- O'zgaruvchining nomi u saqlaydigan ma'lumotlarni tavsiflovchi toza, aniq ma'noga ega bo'lishi kerak. -->