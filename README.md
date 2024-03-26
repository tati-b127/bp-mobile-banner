# Тестовое задание "IPHONE БАННЕР"

## Задача

> Необходимо сверстать полноэкранную веб-страницу (баннер) для мобильных устройств iPhone SE, 8+, 11 pro, 14, 14 plus, 14 pro max. 

### Требования:
> все в портретной ориентации 
> на 6 языках (языковые строки в архиве). 

#### Для iPhone SE, 8+ использовать макет 🎨 Arta_8iphone_1. Пропорционально увеличить, для 8+.

<img width="200px" src="/src/images/Arta_8iphone_1.png" alt="Arta_8iphone"/>

#### Для iPhone 11 pro, 14, 14 plus, 14 pro max использовать макет 🎨 Arta_13iphone_1. Пропорционально уменьшить для iPhone 11 pro и увеличить для 14 plus, 14 pro max.

<img width="200px" src="/src/images/Arta_13iphone_1.png" alt="Arta_13iphone"/>

* Язык должен выбираться исходя из языка системы, а также должно осуществляться переключение путем передачи параметра 'lang' в строке запроса (?lang=en). Значение параметра 'lang' - строка, двухсимвольный код языка. Если системный язык не входит в 6 указанных языков, должна отображаться страница на английском. Обработка параметра lang должна осуществляться на стороне клиента (в JavaScript). 
* Языковые строки могут занимать больше пространства, чем в исходном английском варианте (в макете). Перенос строки разрешается только в заголовке и ячейках с описанием свойств продукта. Часть языков будет нуждаться в уменьшении шрифта для размещения в соответствующих контейнерах. Файлы с языковыми строками не следует править вручную - подключать “как есть”, либо обрабатывать в сборщике.
* Изображения страницы должны быть оптимизированы под мобильные retina экраны и иметь оптимальный размер. При отрисовке баннера на экране не должно быть полос прокрутки.
* Технологии: HTML5, CSS3, нативный JavaScript. Сборщик Webpack (Gulp, Vite).

#### Информация по макету: 
> В макете используются шрифты группы SF Pro (системные шрифты iOS). Крестик, Restore, Terms of Use, Privacy Policy являются ссылками, укажите атрибут href='#' При нажатии на кнопку "Continue" происходит переход по ссылке. Каждой ячейке в панели выбора соответствуют ссылки, сверху вниз: 
● https://apple.com/ 
● https://google.com/ 


## Использованы технологии

![Gulp](https://img.shields.io/badge/GULP-%23CF4647.svg?style=for-the-badge&logo=gulp&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
