# ChatGPT, Flask va EC2 yordamida Telegram Chatbot💬 yaratilingan 
## Umumiy koʻrinish

Ushbu loyiha ChatGPT, Flask va EC2 yordamida Telegram chatbotini qanday yaratishni ko'rsatadi. Quyidagi texnologiyalar va xizmatlar qo'llaniladi:

- Ngrok va Flask server sifatida.
- Telegram BOT tokeni "BotFather" dan olingan.
- Javoblarni yaratish uchun ChatGPT API.
- Flask ilovasi so'rov/javob modeli uchun API sifatida.
- Joylashtirish uchun AWS EC2 (24/7 ishlaydi).

Ushbu loyihadan foydalanish uchun:

1. Repozitariyni klonlash.

2. Ishchi katalogda terminalni oching.

3. Kerakli bog'liqliklarni o'rnatish uchun quyidagi buyruqni bajaring:

    ```
    pip install -r requirements.txt
    ```

4. `telegram_bot.py` - chatbotning so'rovi/javobini boshqaradigan Flask API.
5. Quyidagi buyruq bilan skriptni ishga tushiring:

    ```
    python3 telegram_bot.py
    ```

6. Webhukni sozlash uchun quyidagi formatdan foydalaning:

    ```
    https://api.telegram.org/bot<Your Bot Token>/setWebhook?url=<URL of App>
    ```


