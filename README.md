# hm9
## 1) Чтобы удалить все пустые строки, я использовал регулярное выражение \n+, поставив \0 в поле замены.
![](https://pp.userapi.com/c845221/v845221357/690e2/vEFJd8hqs7E.jpg)
## 2) Чтобы найти упоминания о князьях и городах, в которых есть "слав", я использовал регулярное выражение (^|\s)+[А-Я][а-я]*(слав). Было найдено 592 упоминания.
![](https://pp.userapi.com/c845221/v845221357/690c4/UdrrXadNNGc.jpg)
## 3) Чтобы найти все варианты города Новгород, я использовал регулярное выражение Нов[а-я]{0,1}город[а-я]{0,4}. Было найдено 33 упоминания.
![](https://pp.userapi.com/c845221/v845221357/690c4/UdrrXadNNGc.jpg)
