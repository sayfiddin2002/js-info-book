                        Objects (obyektlar)

obyectga ozgaruvchi beriladi keyin key jingalak qavslar ochilib ichida shu key haqida malumot berilgan key va valuedan tashkil topgan malumotlar boladi. biz obyect ichidagi malumotlarni vergul bilan ajratamiz

let user = {
    name: 'John',
    age: 20,
    job: 'student'
}

Ob'ektda user uchta xususiyat mavjud:

1. Birinchi xususiyat nomi "name"va qiymatiga ega "John".
2. Ikkinchisining nomi "age"va qiymati bor 30.
3. Uchinchisining nome "job" va qiymati "student".

biz istalgan vaqt undan malumot o'qishimiz, qoshishimiz va o'chirishimiz mumkun.

qiymatlarni nuqta bilan olishimiz mumkun

alert( user.name ); // John
alert( user.age ); // 30




let user = {
    name: 'John',
    age: 20,
    job: 'student'
}

malumotni ochirish uchun esa 

delete user.job

let user = {
    name: 'John',
    age: 20,
}



malumot qoshish uchun:

let user = {
    name: 'John',
    age: 20,
}

user.weight = '65kg'

let user = {
    name: 'John',
    age: 20,
    weight: '65kg'
}