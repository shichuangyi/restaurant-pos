# 饭店点餐记账 · Restaurant POS

A local-first Android app for small restaurants: table ordering, checkout, dish management and expense bookkeeping. **No cloud, no account — every record stays on the phone.**

## Features

- 🪑 12 tables: open table, add/remove dishes, hold orders
- 💰 Checkout with cash / WeChat Pay / Alipay, editable received amount
- 🍜 Dish management by category (add, edit, delete)
- 📒 Expense bookkeeping: ingredients, rent, utilities, wages, other
- 📈 Today / month revenue, expenses and net at a glance
- 🔒 4-digit PIN lock screen
- 💾 One-tap JSON backup export & import

## Tech

Single-file offline web app (HTML/CSS/JS, localStorage) inside a thin Android WebView shell. Built automatically by GitHub Actions (Gradle 8.7, AGP 8.5.2, JDK 17).

## Install

Download the APK from the latest successful Actions run's artifact, allow "install unknown apps", and install. Android 7.0+.
