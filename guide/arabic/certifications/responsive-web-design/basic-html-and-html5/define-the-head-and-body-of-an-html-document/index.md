---
title: Define the Head and Body of an HTML Document
localeTitle: حدد رأس ونص مستند HTML
---
## حدد رأس ونص مستند HTML

يتم استخدام عنصر `head` لتجميع كل بيانات التعريف الخاصة بالمستند ، `body` لعرض محتوى المستند.

في `head` يمكنك العثور على أي نوع من العلامات المستخدمة _لوصف_ الوثيقة: ما هي اللغة التي ستستخدمها ، ما هي قواعد الأنماط (من خلال وصلة الأنماط) ، عنوانها ، الوصف الحرفي ، ...  
على أي حال ، لن يتم تقديم أي شيء داخل عنصر `head` إلى الصفحة: يمكنك رؤية العنوان والرمز عادة في علامة تبويب المتصفح أو في شريط الإشارات ولكن هذه ليست _الصفحة_ ، إنه عنصر المتصفح المرتبط بها.

`body` على العكس يحتوي على كل شيء يتم تقديمه في الصفحة: ربما ليس هذا فقط ، ولكن بالتأكيد كل ذلك.

التحدي يتيح لك وصفحة HTML بسيطة ويطلب منك إدخال `head` و `body` عناصر HTML في المكان المناسب. في كلمة أخرى ، يجب أن تلتف بعلامة `<body></body>` جميع العناصر التي يمكنك رؤيتها عند عرضها على الجانب الأيمن من الصفحة والتفاف مع العلامة `<head></head>` كل شيء وصفي.

تذكر أن كلا من `head` `body` يجب أن يكونا من أطفال العنصر `<html>` .

حظا طيبا وفقك الله!