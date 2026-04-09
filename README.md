# TingLi (听力) - Chinese Language Learning App 🇨🇳📱

TingLi (which translates to "Listening" in Chinese) is an iOS application designed to make learning Chinese engaging and interactive. Developed as a project during the Apple Developer Academy Foundation training, the app focuses heavily on the listening aspect of language acquisition.

## 🌟 Features

* **Interactive Audio Gameplay:** Users listen to Chinese vocabulary and tap the corresponding objects in a visual scene (e.g., finding the map, teacher, and book in a classroom).
* **Level Progression System:** Players start at Level 1 (Classroom) and must successfully complete listening challenges to unlock subsequent levels (like Level 2: Restaurant).
* **Native Audio Integration:** Powered by `AVFoundation`, the app provides clear, authentic pronunciation for phrases, vocabulary, and interactive feedback.
* **Hanzi & Pinyin Support:** Displays traditional/simplified Chinese characters alongside Pinyin to help users associate sounds with written forms.
* **Custom UI Components:** Features a custom horizontal scrolling interface with snap-to-item mechanics for level and tutorial selection.

## 🛠️ Tech Stack

* **Language:** Swift
* **Framework:** SwiftUI
* **Audio:** AVFoundation
* **Custom Fonts:** MaShanZheng-Regular, Lato-Regular

## 📱 App Flow

1. **Splash Screen:** Greets the user with a randomized, fully voiced Chinese phrase (e.g., "好久不见" - Long time no see, "我们开始吧！" - Let's begin!).
2. **Home Dashboard:** A clean segmented menu allowing users to choose between "Levels" and "Tutorials".
3. **Level Selection:** A horizontally scrollable grid highlighting the user's unlocked levels and teasing locked stages. 
4. **Core Gameplay:** An interactive view where users are prompted to "Listen and tap the object!". Correct taps reward the user with audio feedback and progress checkmarks.

## 🚀 Getting Started

### Prerequisites
* Mac computer running macOS.
* Xcode 14.0 or later installed.
* iOS 16.0+ simulator or physical device.
