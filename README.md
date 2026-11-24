# 🔐 LocknKey – Progressive Lockout Simulator

### ⚡ Interactive Cybersecurity-Based Authentication & Intrusion Defense Simulation

## 🛡️ Project Overview

**LocknKey** is a futuristic, terminal-inspired authentication security simulator designed to demonstrate how login systems defend against repeated unauthorized access attempts.

The project simulates a progressive account lockout mechanism that detects repeated failed login attempts, applies increasing cooldown periods, and maintains a security audit trail. With a cyber-themed interface, real-time threat indicators, countdown timers, and audio alerts, LocknKey turns authentication security concepts into an interactive experience.

## ✨ Key Features

- 🔑 **Login Authentication:** Validates user credentials.
- 🚨 **Progressive Lockout:** Triggers a temporary lockout after three failed login attempts.
- ⏳ **Tier-Based Cooldowns:** Applies increasing lockout durations of 30 and 120 seconds.
- 📋 **Security Audit Trail:** Records successful and failed login attempts.
- 🌐 **IP & Region Lookup:** Retrieves IP address and region information for failed attempts.
- 💾 **Persistent Storage:** Uses browser Local Storage to retain lockout state and audit history.
- 🔊 **Audio Alerts:** Plays sound effects for successful logins, failed attempts, and lockouts.
- 🎨 **Cyber-Themed Interface:** Features animated threat indicators and a futuristic terminal-style design.

## 🧰 Technologies Used

- HTML
- CSS
- JavaScript
- Browser Local Storage
- Fetch API
- Web Audio API
- GitHub Pages

## ⚙️ How It Works

1. Enter the login credentials.
2. The system validates the submitted credentials.
3. Repeated failed attempts are recorded in the security audit trail.
4. After three failed attempts, the system activates a temporary lockout.
5. The lockout duration increases with subsequent lockout tiers.
6. Once the countdown ends, login access is restored.

## 🚀 Live Demo

[Launch LocknKey](https://krishnapriyasworld2020-lang.github.io/locknkey/)

## 💻 GitHub Repository

[View Source Code](https://github.com/krishnapriyasworld2020-lang/locknkey)

## 🎯 Project Objective

To explore authentication security concepts, progressive lockout mechanisms, client-side state management, and basic intrusion-defense simulations through a practical web development project.

---

*Built as a hands-on project to explore cybersecurity and web development.*
