---
title: "Chess Trainer"
excerpt: "Static site for practicing chess: interactive chessboard with real-time commentary from Stockfish 18 Lite."
collection: projects
order: 5
---

*Chess Trainer* is a static web application built with HTML, CSS, and vanilla JavaScript, designed to help users improve their chess skills through real-time move analysis. The main goal of the project is to provide players with instant, professional-grade feedback on every move they make during a game, without relying on any backend or user account system. Game rules and state are handled by chess.js, imported as an ES module, while the board UI and drag-and-drop interactions are managed by chessboard.js. Move evaluation is powered by Stockfish 18 Lite, running in a dedicated Web Worker and communicating through the UCI protocol; centipawn scores are converted into win-probability estimates to classify each move (best, excellent, inaccuracy, mistake, blunder, etc.). The app also features an opening-recognition system based on a local EPD position database, along with custom-built annotation tools such as move-quality badges and on-board arrows, all implemented in vanilla JavaScript. This architecture allows the entire training experience — from rule enforcement to engine-level analysis — to run locally on the user's device, ensuring privacy and enabling offline use through a service worker and Progressive Web App configuration.

The app/site is available [here](https://wdaav.github.io/chess-trainer/).

For further information, please contact me via [email](mailto:davideverditto).