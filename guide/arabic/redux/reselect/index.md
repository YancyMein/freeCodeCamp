---
title: Reselect
localeTitle: إختار من جديد
---
## إختار من جديد

Reselect هو مكتبة محدد بسيطة لـ Redux. لماذا نحتاج المختارين؟ تصف المستندات الرسمية هذه الطريقة:

*   يمكن أن يقوم المحللون بحساب البيانات المشتقة ، مما يسمح لـ Redux بتخزين الحد الأدنى من الحالات الممكنة.
*   الاختيارات هي فعالة. لا يتم إعادة حساب المحدد ما لم يتغير أحد وسيطاتها.
*   الاختيارات قابلة للتركيب. يمكن استخدامها كمدخل إلى محددات أخرى.

قد يبدو الأمر معقدًا ، إلا أن slectors تسمح للتطبيق بالعمل بشكل أسرع عن طريق تقليل العرض (الاستدعاءات) بدون داعٍ. يسمى عادة `mapStateToProps` كل مرة يتم فيها أي تغيير في `store` . `mapStateToProps` بربط قيم المتجر للتفاعل. حتى تتمكن من استخدام `PureComponents` قد يتسبب في إعادة تجميع المكون على الرغم من أنه غير مطلوب.

#### معلومات اكثر:

*   [إختار من جديد](https://github.com/reduxjs/reselect)
*   [رد ، حدد و Redux](https://medium.com/@parkerdan/react-reselect-and-redux-b34017f8194c)