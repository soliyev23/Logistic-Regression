Loyihaning nomi: Logistik Regressiya va ROC Egri Analizi
Loyihaga umumiy nuqtai
Ushbu loyiha ikkilik tasniflash modelini qurish va uni baholashga qaratilgan. Model sifatida Logistik Regressiya tanlangan bo‘lib, u ma'lum ma'lumotlar asosida natijaning ikki xil bo'lish ehtimolini bashorat qilish uchun ishlatiladi. Loyiha davomida, modelning samaradorligini baholash uchun ROC (Receiver Operating Characteristic) egrisi va AUC (Area Under the Curve) dan foydalaniladi.

Loyihaning tarkibi
Asosiy Jupyter daftar fayli: exam_2.ipynb fayli. Ushbu daftar quyidagi asosiy bosqichlardan iborat:
Ma'lumotlarni tayyorlash va trening hamda test to'plamlariga bo'lish.
Logistik regressiya modeli yordamida trening (o'rgatish).
Model yordamida bashorat qilish va ehtimolliklarni hisoblash.
Modelning ishlashini vizual baholash uchun ROC egrisini chizish.
Loyihada ko'rib chiqilgan asosiy tushunchalar
Logistik Regressiya: Ushbu algoritm ikkilik tasniflashda qo'llaniladi. U natijaning muayyan sinfga tegishli bo'lish ehtimolini bashorat qiladi.

ROC Egrisi: Bu grafik ko'rinishda modelning haqiqiy ijobiy stavka (True Positive Rate) va yolg‘on ijobiy stavka (False Positive Rate) o‘rtasidagi bog‘liqlikni ko'rsatadi. Egrining ostidagi maydon (AUC) modelning barcha klassifikatsiya chegaralari bo'yicha umumiy samaradorligini o'lchaydi.