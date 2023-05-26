<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ
РОССИЙСКОЙ ФЕДЕРАЦИИ
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center"> Институт естественных наук и техносферной безопасности <br> Кафедра информатики <br> Пашаян Самвел Алексанович </p>
<br><br><br>
<p align = "center"> Лабораторная работа №1 <br> «Первое Android-приложение» <br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right"> Научный руководитель <br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center"> г. Южно-Сахалинск <br> 2023г.</p>
***
# <p align = "center"> ЗАДАНИЕ </p>
Измените уведомление так, чтобы оно отображалось в верхней, а не в нижней части экрана. Для изменения способа отображения уведомления воспользуйтесь функцией setGravity класса Toast. Выберите режим Gravity.TOP. 
***
# <p align = "center"> РЕШЕНИЕ </p>
            true_button.setOnClickListener {
                val toast = Toast.makeText(this,R.string.correct_toast,Toast.LENGTH_SHORT)
                toast.setGravity(Gravity.TOP,0,0)
                toast.show()
            }

            false_button.setOnClickListener {
                val toast = Toast.makeText(this,R.string.incorrect_toast,Toast.LENGTH_SHORT)
                toast.setGravity(Gravity.TOP,0,0)
                toast.show()
            }
## <p align = "center"> ВЫВОД </p>      
Итогом работы стало создание своего первого Android приложения и знакомство с интерфейсом Android Studio. По заданию мы поработали с уведомлением и нужно было его изменить так, чтобы оно отображалось в верхней, а не в нижней части экрана. Это позволяет сделать вывод, что цель данной лабораторной работы успешно достигнута
***  
![](LAB1.png)
 