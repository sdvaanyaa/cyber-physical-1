### Запуск

**1. Создать виртуальное окружение и установить зависимости:**

```bash
python -m venv .venv
source .venv/bin/activate        # Для Linux / macOS
# .venv\Scripts\activate         # Для Windows

pip install -r requirements.txt
```
**2. Запустить ноутбук:**

```bash
jupyter notebook cyber-physical-1.ipynb
```

Примечание для Google Colab:
Если вы запускаете ноутбук в среде Colab, шаг с установкой requirements.txt можно пропустить, так как основные библиотеки (torch, sklearn) там уже предустановлены. 