# WhatLoll.Encoder - JavaScript библиотека

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

##  О проекте

**WhatLoll.Encoder** - это легковесная библиотека для шифрования и дешифрования текста с использованием уникальных таблиц замен WhatLoll. Идеально подходит для:

-  **Игр и квестов** - создавайте зашифрованные подсказки
-  **Обучения** - покажите пример простого шифрования
-  **Личных записок** - скрывайте текст от случайных глаз
-  **Развлечения** - отправляйте друзьям "секретные" сообщения

> [!WARNING]
>  Это **НЕ криптографически стойкое шифрование**! Это простая замена символов для развлечения и обучения. Расшифровка не 100%

# Установка
| HTML | Java Script |
|------|-------------|
| ```<script src="https://cdn.jsdelivr.net/gh/xachapyri-dev/WhatLoll-Encoder-JavaScript@main/WhatLoll.Encoder/WhatLoll.Encoder.min.js"></script>``` | ```import whatloll from 'https://cdn.jsdelivr.net/gh/xachapyri-dev/WhatLoll-Encoder-JavaScript@main/WhatLoll.Encoder/WhatLoll.Encoder.min.js';``` |

# Пример кода
``` html
<script src="https://cdn.jsdelivr.net/gh/xachapyri-dev/WhatLoll-Encoder-JavaScript@main/WhatLoll.Encoder/WhatLoll.Encoder.min.js"></script>
<script>
    const text = whatloll.encryptV2('Hello World');
    console.log(text);
</script>
```

# API
| Метод | Описание |
|-------|----------|
| ```encryptV1(text)``` |	Шифрование V1 |
| ```encryptV2(text)``` |	Шифрование V2 |
| ```decryptV1(text)``` |	Дешифрование V1 |
| ```decryptV2(text)``` |	Дешифрование V2 |
| ```decryptAuto(text)``` |	Автоопределение версии |
| ```getEncryptionTable(version)``` |	Таблица шифрования |
