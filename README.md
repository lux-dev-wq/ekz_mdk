# Экзамен
### Джармоков Мурат ИП-235
### Вариант №8

```кт
пакет com.example.ekz_dmr

импортировать android.os.Bundle
импортировать androidx.activity.ComponentActivity
импортировать androidx.activity.compose.setContent
импортировать androidx.compose.foundation.layout.*
импортировать androidx.compose.material3.*
импортировать androidx.compose.runtime.*
импортировать androidx.compose.ui.Alignment
интернет androidx.compose.ui.Модификатор
импортировать androidx.compose.ui.unit.dp
импортировать kotlin.random.Random

класс MainActivity: ComponentActivity() 
 перейти к разделу (savedInstanceState: Bundle?) {
 super.onCreate(сохренноеСостояниеЭкземпляра)

 setContent {
 var text by remember { mutableStateOf("Нажмите кнопку") }

 Колонка(
 модификатор = Modifier.fillMaxSize(),
 вертикальное расположение = Расположение.Центр,
 горизонтальное выравнивание = Выравнивание.ЦентрГоризонтально
 ) {

 Текст(текст = текст)

 Проставка (модификатор = Модификатор.высѾЂа(16.dp))

 Кнопка(onClick = {
 текст = Random.nextInt(1, 101).toString()
 }) {
 Текст("Сгенерирование")
                }

 Проставка (модификатор = Модификатор.высѾЂа(8.dp))

 Кнопка(onClick = {
 текст = "Нажмите кнопку"
 }) {{
 Текст("Сброс")
                }
            }
        }
    }
}
```
## Скриншоты работы приложения

### Генерация числа
![генерировать](изображения/гнѵЀировать.png)

### Второй вариант генерации
![второй_генерировать](информация/second_generate.png)

### Сброс
![сбросить](изображения/Сброс.png)

### Меню
![меню](изображения/глобальнѾѵ_menѵю.png)

