                        Function (decloration)

<!--
    function showMessage() {
         alert( 'Hello everyone!' );
    }
 -->

function kalit sozi yoziladi, orqasidan function nomi () qavs ochiladi va jingalak qavslar ochilib functionning tana qismi yoziladi.

funcksiya biz chaqirishimizni kutib yotadi. funcsiyalar oz nomi bilan chaqiriladi.

<!--
    function showMessage() {
        alert( 'Hello everyone!' );
    }

    showMessage();
 -->

Funktsiya ichida e'lon qilingan o'zgaruvchi faqat shu funktsiya ichida ko'rinadi.

Masalan:

<!--
    function showMessage() {
      let message = "Hello, I'm JavaScript!"; // local variable

        alert( message );
    }

    showMessage(); // Hello, I'm JavaScript!

    alert( message ); // <-- Error! The variable is local to the function
 -->

Funktsiya ichida e'lon qilingan o'zgaruvchi faqat shu funktsiya ichida ko'rinadi.

Masalan:

<!--
    function showMessage() {
    let message = "Hello, I'm JavaScript!"; // local variable

        alert( message );
    }

    showMessage(); // Hello, I'm JavaScript!

    alert( message ); // <-- Error! The variable is local to the function
 -->

parametrlar yordamida funcsiyalarga malumot otkazishimiz mumkun

<!--
    function showMessage(from, text) { // parameters: from, text
        alert(from + ': ' + text);
    }

    showMessage('Ann', 'Hello!'); // Ann: Hello! (*)
    showMessage('Ann', "What's up?"); // Ann: What's up? (**)
 -->
