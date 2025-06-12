---
title: "Flutter Quiz Game"
date: "2024-11-19"
category: [Projects, Showcase]
tag: [mobile, flutter, dart]
description: A simple quiz game using Flutter and Dart
pin: true
image:
  path: /assets/img/screenshots/flutter-quiz-heading-02.png
#   alt: First screen of the app - the quiz selection screen
---
## [<i class="fab fa-github"></i> GitHub Repo](https://github.com/DBerry07/Flutter_QuizGame)

## Overview
Written in Dart and using the Flutter framework, this app is a quiz app.

### Control Flow
1. User selects which quiz to do
2. User answers each question as it comes up from a list of multiple choices
3. After each answer select, a popup dialouge show giving some information about the question topic
4. At the end of the quiz, the user is presented with the number of questions they answered correctly
5. The user can then restart the quiz or return to the initial screen to select another quiz

### Features
+ The app picks ten random questions from the selected quiz topic each time the user starts a new quiz.
+ The order of appearance of the questions is randomized each time the user starts a new quiz.
+ The user can return to the initial screen (the quiz selection screen) by clicking the home icon in the app bar.
+ Each question has multiple choices, ranging from one choice to four choices.
+ Answering a question displays a pop-up indicating whether the chosen answer was correct or incorrect.
+ Each question has an optional blurb that explains the correct answer. This is shown after the user makes an answer selection.
+ Each quiz topic has a dedicated JSON file with all of the questions and answers in the ```assets``` folder.
+ A developer can easily add another quiz topic by creating a JSON file (using the same template as the other quiz topics) and adding it to the ```quizzes.dart``` ```quizzes``` map.

## Screenshots
<div class="screenshots">
    <img src="/assets/img/screenshots/flutter-quiz-android-00.png" width="200" />
    <img src="/assets/img/screenshots/flutter-quiz-android-question.png" width="200" />
    <img src="/assets/img/screenshots/flutter-quiz-android-results.png" width="200" />
</div>
<div class ="screenshots">
    <img src="/assets/img/screenshots/flutter-quiz-android-correct.png" width="200" />
    <img src="/assets/img/screenshots/flutter-quiz-android-incorrect.png" width="200" />
</div>

