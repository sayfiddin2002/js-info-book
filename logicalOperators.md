                                Logical operatosr

Javascriptda 4 ta mantiqiy aperator mavjud.

ular:

|| - yoki;
&& - va;
! - bolmasa;
?? - nullish;

|| - chapdan ongga qarab oqiydi bironta true kelsa shuni qaytaradi agar hammasi false bolsa oxirdagisini qaytaradi

alert( true || true ); // true
alert( false || true ); // true
alert( true || false ); // true
alert( false || false ); // false

<!--
alert( 1 || 0 ); // 1 (1 is truthy)

alert( null || 1 ); // 1 (1 is the first truthy value)
alert( null || 0 || 1 ); // 1 (the first truthy value)

alert( undefined || null || 0 ); // 0 (all falsy, returns the last value)
 -->


&& - ikkala tarafdan ham true chiqsa ishlaydi 
chaodan ongga qarab tekshiradi agar false chqib qolsa anashu qiymatni qaytaradi. agar hammasi true bolsa ohirdagini qaytaradi

<!-- 
alert( true && true );   // true
alert( false && true );  // false
alert( true && false );  // false
alert( false && false ); // false
 -->
