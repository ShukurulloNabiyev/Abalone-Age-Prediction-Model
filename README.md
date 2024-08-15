# Loyihaning nomi

Regressiya modellari taqqoslashi va stacking

## Loyihaning Umumiy Ko'rinishi

Ushbu Jupyter daftari turli regressiya modellari ishlashini taqqoslash va stacking regressorini qo'llab, bashoratlarning aniqligini oshirish uchun mo'ljallangan. Daftarda modellarning ishlashi O'rtacha Absolyut Xatolik (MAE) bo'yicha baholanadi va eng yaxshi modelning bashoratlari CSV faylga saqlanadi.

## Ishlatilgan Modellar

- **Chiziqli Regressiya**
- **Ridge Regressiya**
- **Lasso Regressiya**
- **Huber Regressori**
- **Theil-Sen Regressori**

## Stacking Regressor

Stacking regressori yuqoridagi modellarning bashoratlarini birlashtirish uchun amalga oshirilgan. Stacking yondashuvi yakuniy bashoratni amalga oshirish uchun foydalanuvchi tomonidan belgilangan modeldan foydalanadi.

## Baholash Mezoni

- **O'rtacha Absolyut Xatolik (MAE)**: Modellarni baholash va taqqoslash uchun ishlatiladi.

## Natijalar

Huber Regressori eng past MAE qiymatiga ega bo'lib, u berilgan datasetda eng yaxshi ishlovchi model ekanligi aniqlandi.

## Natijalar Yaratilishi

Yakuniy bashoratlar `imtihon.csv` nomli CSV faylga saqlanadi. Bashoratlar eng yaqin butun son qiymatiga yaqinlashtiriladi.