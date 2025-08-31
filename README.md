# Google AI Edge Gallery Accessibility Mod

*Описание по-русски ниже.*

---

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/google-ai-edge/gallery)](https://github.com/google-ai-edge/gallery/releases)

This is a modification of the original [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery) application. This version implements accessibility for TalkBack users.

**Original App Description:**

**Explore, Experience, and Evaluate the Future of On-Device Generative AI with Google AI Edge.**

The Google AI Edge Gallery is an experimental app that puts the power of cutting-edge Generative AI models directly into your hands, running entirely on your Android *(available now)* and iOS *(coming soon)* devices. Dive into a world of creative and practical AI use cases, all running locally, without needing an internet connection once the model is loaded. Experiment with different models, chat, ask questions with images and audio clip, explore prompts, and more!

## Build from Source

### Requirements
*   Java Development Kit (JDK)

### Build Process

The project includes a Gradle Wrapper, which will automatically download the correct Gradle version.

1.  **Build the project:**
    *   For macOS/Linux, run in your terminal:
        ```shell
        ./gradlew assembleDebug
        ```
    *   For Windows, run in your command prompt:
        ```shell
        gradlew.bat assembleDebug
        ```

2.  **Find the APK:**
    After a successful build, the `app-debug.apk` installation file will be located in the `app/build/outputs/apk/debug/` directory.

---

# Google AI Edge Gallery Accessibility Mod (Описание по-русски)

Это модификация оригинального приложения [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery). В этой версии реализована доступность для пользователей TalkBack.

**Описание оригинального приложения:**

**Исследуйте, испытайте и оцените будущее генеративного ИИ на устройствах с помощью Google AI Edge.**

Google AI Edge Gallery — это экспериментальное приложение, которое дает вам в руки всю мощь передовых моделей генеративного ИИ, работающих полностью на ваших устройствах Android *(доступно сейчас)* и iOS *(скоро)*. Погрузитесь в мир творческих и практических применений ИИ, которые работают локально и не требуют подключения к Интернету после загрузки модели. Экспериментируйте с различными моделями, общайтесь в чате, задавайте вопросы с помощью изображений и аудиоклипов, исследуйте подсказки и многое другое!

## Сборка из исходного кода

### Требования
*   Java Development Kit (JDK)

### Процесс сборки

Проект включает в себя Gradle Wrapper, который автоматически загрузит нужную версию Gradle.

1.  **Соберите проект:**
    *   Для macOS/Linux выполните в терминале:
        ```shell
        ./gradlew assembleDebug
        ```
    *   Для Windows выполните в командной строке:
        ```shell
        gradlew.bat assembleDebug
        ```

2.  **Найдите APK:**
    После успешной сборки установочный файл `app-debug.apk` будет находиться в директории `app/build/outputs/apk/debug/`.
