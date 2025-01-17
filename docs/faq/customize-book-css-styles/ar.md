---
layout: main
---

# تشفير CSS مخصص

> بالنسبة لعرض الكتب ، يأخذ **Librera** عادةً الأنماط من ملف .css للكتاب ويطبق أيضًا إعداداتك من نافذة **التفضيلات**. ويمكن أيضا الاستفادة من واحدة أو أخرى على حدة. لكن في بعض الأحيان لا يكفي. تحتوي بعض الكتب على كود CSS غريب جدًا بحيث لا يوجد لديك خيار آخر سوى تحرير ملفات .css لتحسين قابلية القراءة. على الرغم من ذلك ، يمنحك **Librera** خيارًا آخر: إضافة رمز CSS مخصص مؤقتًا يمكن إزالته بسهولة بمجرد الانتهاء من كتاب التحدي.

ثلاثة **أنماط** مدعومة:

1. المستند + المعرفة من قبل المستخدم (يأخذ الأشياء الجيدة من العالمين)
2. المستند (يستخدم فقط إعدادات .css للكتاب)
3. معرف من قبل المستخدم (يستخدم فقط إعداد المستخدم المحدد في علامات تبويب نافذة **التفضيلات**)

* يمكن للمستخدم التبديل بين الأوضاع عبر قائمة منسدلة تم استدعاءها عند النقر على الرابط بجوار _Styles_.
* اضغط على الرمز المجاور لقائمة _Styles_ لفتح نافذة **Custom CSS Code** وانتقل إليها.

|1|2|3|
|-|-|-|
|![](1.png)|![](2.png)|![](3.png)|

يتم تمكين وضع المستند + المعرفة من قبل المستخدم بشكل افتراضي

المثال في الشكل 3 مأخوذ من الحياة الحقيقية.

{white-space: pre-line;}
متسلسلات المساحة البيضاء تنهار. يتم كسر الخطوط في أحرف السطر الجديد ، في <br> ، وعند الضرورة لملء مربعات الخط.

{white-space: pre;}
يتم الحفاظ على تسلسل مساحة بيضاء. يتم كسر الخطوط فقط في أحرف السطر الجديد في المصدر وفي <br> عناصر.

span {display: block}
p&gt; span {display: inline}
يزيل الأسطر الفارغة المزعجة للغاية بين الصفحات (تصحيح عيوب muPDF).
