OGK – Personal Calories & Macros Tracker

OGK is a lightweight, local-first Progressive Web App (PWA) designed for seamless calorie and macronutrient tracking. Built with a mobile-first approach, it runs entirely in the browser without any traditional backend or external database.

English Version

Key Features
- 100% Local & Private: All food logs, daily progress, settings, and API keys are stored safely in your browser's localStorage.
- AI-Powered Food Recognition: Utilizes Google Gemini API for multimodal image analysis (food photos & nutrition labels) and text inputs.
- Interactive Clarification Modal: When you upload a food photo, the AI detects potential uncertainties (e.g., cooking oil, sour cream type) and prompts you for details before logging.
- Smart Performance: Built-in client-side image compression (Canvas/WebP) ensures fast responses even on mobile networks.
- PWA Support: Easily installable on iOS and Android ("Add to Home Screen") for a native app feel.
- Customizable UI: Clean Dark Mode with customizable accent colors.

Recommended Gemini Model
Based on practical testing, the best-performing model for OGK is: gemini-3.1-flash-lite
Note: Internal benchmarks and real-world usage show that gemini-3.1-flash-lite delivers accurate JSON nutrition outputs in approximately ~5 seconds, offering the best balance between speed and quality for mobile usage.

Tech Stack
- Frontend: Single-file HTML5, JavaScript (ES6+), Tailwind CSS
- Icons: Lucide Icons
- AI Integration: Google Gemini API
- Hosting: GitHub Pages

Wersja Polska

Glówne Cechy Aplikacji
- 100% Lokalność i Prywatność: Wszystkie posiłki, dzienny postęp, ustawienia oraz klucz API są zapisywane wyłącznie w pamięci przeglądarki (localStorage).
- Rozpoznawanie Posiłków przez AI: Wykorzystuje Google Gemini API do analizy zdjęć potraw, tabel wartości odżywczych oraz opisów słownych.
- Interaktywne Doprecyzowanie Posiłków: Po wgraniu zdjęcia jedzenia AI wykrywa niepewności (np. użyty olej, tłustość śmietany) i zadaje pytania doprecyzowujące przed zapisaniem.
- Wysoka Wydajność: Automatyczna kompresja zdjęć po stronie klienta (Canvas/WebP) zapewnia szybkie działanie nawet w sieciach mobilnych.
- Wsparcie dla PWA: Możliwość łatwego zainstalowania na ekranie głównym telefonu (iOS & Android) jak zwykła aplikacja mobilna.
- Personalizacja: Nowoczesny Dark Mode z możliwością wyboru koloru akcentu aplikacji.

Rekomendowany Model Gemini
Na podstawie przeprowadzonych testów praktycznych, najlepszym wyborem dla aplikacji OGK jest: gemini-3.1-flash-lite
Uwaga: Testy własne wykazały, że model gemini-3.1-flash-lite zwraca precyzyjne dane odżywcze w formacie JSON w czasie około 5 sekund, co zapewnia idealny balans pomiędzy szybkością odpowiedzi a dokładnością szacunków na telefonie.

Technologie
- Frontend: Jednoplikowy HTML5, JavaScript (ES6+), Tailwind CSS
- Ikony: Lucide Icons
- Sztuczna Inteligencja: Google Gemini API
- Hosting: GitHub Pages
