# MovementSwapper
Movement Swap on DEXs Razzor, YUZU
# Movement Swapper
---

## 🔧 Запуск готовой сборки

1. Запустите приложение:
   - **Windows**:
     ```
     movement_swapper.exe
     ```
---
## 🔧 Настройка аккаунтов data/accounts.json
- ```
  {
    "1": [
        "146.XXX.XXX.XXX",
        "89XX",
        "borodXXXX",
        "118XXXXXXXXX",
        "0xc1b2XXXXXXXXXXXXXXXXXXX",
        "rigid wealth XXXXXXXXXXXX",
        "empty_seed",
        "empty_cookies",
        "1"
    ],
    "2": [
        "146.XXX.XXX.XXX",
        "89XX",
        "borodXXXX",
        "118XXXXXXXXX",
        "0xc1b2XXXXXXXXXXXXXXXXXXX",
        "rigid wealth XXXXXXXXXXX",
        "empty_seed",
        "empty_cookies",
        "2"
    ]
      ...
  }
## 🔧 data/accounts.json:
    - "146.XXX.XXX.XXX" - host (IP адрес или домен)
    - "89XX" - порт
    - "borodXXXX" - логин
    - "118XXXXXXXXX" - пароль
    - "0xc1b" - адрес кошелька (начинается с 0xc1b)
    - "rigid wealth XXXXXX" - фраза восстановления (seed/mnemonic)
    - "1" - номер аккаунта либо любой тег (для идентификации, будет отображаться в логах)
## data/active_accs.json
    - "+" - отработка акка
    - "-" - пропуск акка
---
## 🔧 Общие настройки .env
        - INFINITY_MODE=True # Включает бесконечный режим
        - INFINITY_MODE_SLEEP_FROM=15 # Задержка перед началом работы в бесконечном режиме (в секундах)
        - INFINITY_MODE_SLEEP_TO=30 # Максимальная задержка перед началом работы в бесконечном режиме (в секундах)
        - SHUFFLE_ACCOUNTS=True # Перемешивать аккаунты перед началом работы
        - ACCOUNT_REPEAT_COUNT=2 # Количество повторов для каждого аккаунта
---
## 📁 Что входит в сборку
- `movement_swapper.exe` — исполняемый файл
- `data/` — директория с ресурсами (иконки, конфиги и т.п.)
- `chromium/` — кастомный браузер для автоматизации (если используется)
---
## 📁 README.md — этот файл с инструкциями
- README.md — содержит инструкции по запуску и настройке
## 📞 Любые вопросы 3 0 7
- https://t.me/bizzzonnn
- https://t.me/borodovyi
