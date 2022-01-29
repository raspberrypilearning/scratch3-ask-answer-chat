
يمكنك استخدام لبنات `السؤال`{: class = "block3sensing"} و `الجواب`{: class = "block3sensing"} من قائمة لبنات`الاستشعار`{: class = "block3sensing"} لإجراء محادثة.

![سوال الحوار مع كلمة "نعم" او "yes" كمدخلات](images/ask-answer.png)

إضافة لبنات الى المقطع البرمجي للكائن الذي`سيسأل`{: فئة = "block3sensing"} سؤال:

```blocks3
ask [Did you find everything you wanted today?] and wait
if <(answer) = [yes]> then
say [That's fantastic!] for [2] seconds
else
say [Maybe I should add more items to my shop] for [2] seconds
end
```

**التصحيح:** تأكد من كتابة الخيارات بشكل صحيح في التعليمات البرمجية الخاصة بك وفي إجابتك. لا بأس إذا كنت تستخدم الأحرف الكبيرة في اللغة الانكليزية، لذا فإن "Yes" و "YES" سيتطابقان مع "yes" .

أضف أسئلة متعددة لإنشاء روبوت محادثة يمكنك التحدث إليها.

**نصيحة:** إذا قمت `بإخفاء`{: class = "إخفاء"} الكائن الذي يطرح سؤالاً ، فسيظهر السؤال داخل مربع الإدخال بدلاً من فقاعة كلام.

![سوال الحوار مع السؤال في الداخل](images/ask-hidden-sprite.png)

