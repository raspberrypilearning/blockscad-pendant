## أضف المزيد من الأطواق

يستخدم التصميم ستة أطواق متقاطعة ، ويتم نقل كل حلقة من المركز وتدويرها بعدد مختلف من الزوايا.

--- task ---

في التصميم النهائي ، لا يوجد طوق مركزي: حيث يتم نقل جميع الأطواق خارج المركز.

أولاً ، ترجمة ` ` {: class = "blockscadtransforms"} (تحريك) الحلقة الأولى في الموضع.

![screenshot](images/pendant-translate.png)

الآن الطوق قليلا خارج المركز.

--- /task --- --- task ---

تحتاج إلى نسخ متعددة من هذا الطوق ، تدور حول المركز. أولاً ، قم بإنشاء ثلاث أطواق متساوية المسافات:

أضف حلقة `العد `{:class="blockscadloops"} لإنشاء ثلاث أطواق. لمسافة الاطواق ، أضف كتلة `تدوير `{:class="blockscadtransforms"} بين الحلقة `العد` والكتلة `ترجمة `. `العد ` يضبط المتغير `i` من 1 إلى 3. `تدوير ` ينقل كل حلقة بمقدار `120 × i` درجات، بحيث توزع هذه الحلقات الثلاث بالتساوي حول 360 درجة من الدائرة (360 / 3 = 120).

![screenshot](images/pendant-3-hoops.png)

انظر إلى التعليمة البرمجية وتأكد من فهمك لكيفية عملها.

--- /task --- --- task ---

التصميم النهائي يحتوي على ستة اطواق بدلا من ثلاثة أطواق. قم بتغيير التعليمات البرمجية الخاص بك بحيث يقوم بإنشاء ستة أطواق متساوية المسافات.

--- hints --- --- hint ---

Change the `count`{:class="blockscadloops"} loop so that it runs six times instead of three. The six hoops will need to be equally spaced around 360 degrees.

--- /hint --- --- hint ---

You need to change the loop to run from 1 to 6 and move in multiples of 60 degrees (360 / 6 = 60):

--- /hint --- --- hint ---

Your code should look like this:

![screenshot](images/pendant-6-hoops.png)

--- /hint --- --- /hints --- --- /task ---	
	
