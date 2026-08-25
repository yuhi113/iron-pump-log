![preview](https://raw.githubusercontent.com/yuhi113/iron-pump-log/main/frame_c5408.svg)
[![Download](https://raw.githubusercontent.com/yuhi113/iron-pump-log/main/run_96c76.svg)](https://yuhi113.github.io/iron-pump-log/)

# 🏋️‍♂️ Gymnasium Forge — Your Personal Biomechanical Training Architect

Welcome to **Gymnasium Forge**, a living, breathing repository that evolves with every rep you take. This isn't just another workout tracker; it's a personalized biomechanical architect designed exclusively for my own fitness journey — a digital blacksmith that forges steel-strong habits, tailored routines, and data-driven progress. Unlike cookie-cutter fitness apps that treat every body like a blank template, this project adapts like a chameleon, learning from your daily inputs, recovery patterns, and performance plateaus to sculpt a training regimen as unique as your fingerprint.

Why did I build this? Because generic "one-size-fits-all" programs left me feeling like a square peg in a round hole. My joints, my schedule, my energy rhythms — they deserve a blueprint that listens. This repo is that blueprint, constantly rewritten by the data I feed it. Whether you're a weekend warrior, a desk-bound professional reclaiming your strength, or a seasoned lifter chasing new personal records, the core philosophy here is straightforward: **your body whispers; this system amplifies those whispers into actionable intelligence.**

---

## ✨ Feature Arsenal — More Than Just Sets and Reps

This project is a constellation of interlocking capabilities, each star designed to illuminate a different corner of your training universe. Here's what powers the forge:

- **🧬 Adaptive Workout Matrix** — The heart of the system. It doesn't just log your workouts; it analyzes your historical performance, sleep quality, and subjective energy scores to dynamically adjust volume, intensity, and exercise selection for the next session. If your deadlift is stalling, the matrix might swap in a deficit pull or adjust your rep tempo to spark new adaptation.
- **📊 Progress Telemetry Dashboard** — A beautiful, mobile-responsive visual dashboard that transforms raw numbers into insightful charts. Track one-rep max trends, muscle group balance, cumulative tonnage, and even forecasted plateaus. The dashboard speaks the language of data, but its heart beats in motivation.
- **🗣️ Multilingual Form Coach** — Exercise cue reminders and feedback are delivered in your preferred language. From English to Spanish to Japanese, the forge speaks your native tongue, ensuring no nuance is lost in translation. This isn't a simple translation; it's localized motivational phrasing that resonates with your cultural context.
- **⏰ Adaptive Rest Timer** — Forget static rest periods. This intelligent timer calculates optimal inter-set recovery based on heart rate zone projections, exercise complexity, and your personal recovery curve. It keeps your sessions efficient without sacrificing intensity.
- **📝 Mind-Muscle Connection Journal** — A dedicated space to jot down micro-feedback: "felt left shoulder instability on press," "bicep peak activated during curl." This qualitative data is integrated into the AI analysis, providing context that quantitative metrics alone can't capture.
- **🌍 24/7 Support Constellation** — While this is a personal project, the architecture includes a detailed issue template and a community-wiki construction guide. For questions or feature suggestions, open a discussion thread, and expect a focused response from the maintainer (me) within 24 hours. *We're in this together.*
- **🔐 Local-First Privacy Vault** — Your HRV scores, body weight, and gym notes are your business. This project operates on a local-first principle, storing data directly on your machine. No cloud, no telemetry, no corporate surveillance. Your progress is a private conversation between you and your code.
- **🔄 Configurable Micro-Cycles** — Not everyone follows a traditional 4-week mesocycle. The forge allows you to define custom micro-cycle lengths, whether it's based on your menstrual cycle, shift work patterns, or peak vacation weeks. The system aligns its deloads and intensification waves to your actual life.

---

## 🚀 Why This Forge is Different (The Origin Story)

After years of following influencers and generic PDF programs, I hit a relentless wall. My progress wasn't linear; it was a chaotic squiggle with occasional peaks. I realized the missing ingredient wasn't more grit, but more **contextual awareness**. A program designed by a world champion powerlifter fails when you're sleep-deprived and stressed from a 9-to-5 job.

Gymnasium Forge was born from that frustration. It’s a proactive software companion that asks, "How did you *really* feel about that last set?" and then uses that answer to rewrite tomorrow's prescription. It’s the difference between following a map drawn in 1990 and using a real-time GPS that navigates around traffic and road closures. This project is the GPS for your muscle growth.

---

## 🛠️ Core Architectural Pillars

This repository is structured for maintainability and scalability, even as a solo project. It is built with a modular philosophy, allowing you to disable features you don't use.

- **`core/`** — Contains the primary logic engine, including the Adaptive Workout Matrix algorithms and the data preprocessing pipelines.
- **`ui/`** — The responsive front-end interface. Built to look perfect on a phone at the gym, a tablet on the couch, or a desktop monitor.
- **`data/`** — Handles data persistence, schema migrations, and the encryption layer for your private metrics.
- **`intel/`** — The AI/machine learning integration module. This is where the predictive plateau analysis and exercise variation suggestions live.
- **`docs/`** — This comprehensive documentation, including the philosophical guide and advanced tuning manuals.

---

## 📚 Getting Started: Forging Your First Session

This is where you choose your path. The essence of the forge is its adaptability to your technical comfort level.

**The Gentle Path (No-Code Setup):**
The easiest way to ignite the forge is to use the pre-configured executable binary provided in the Releases section (look for the [![Download](https://raw.githubusercontent.com/yuhi113/iron-pump-log/main/run_96c76.svg)](https://yuhi113.github.io/iron-pump-log/) button). Download, double-click, and the local server auto-launches in your browser. The interface will guide you through your first profile creation, asking about your goals, available equipment, and weekly rhythm. You don't need to touch a line of code to benefit from its intelligence.

**The Tinkerer's Path (Source Build):**
For the curious and the control enthusiasts, clone this repository to your local workspace. The project utilizes a standard Python environment. You will need to ensure you have the dependencies listed in `enviroment.yml`. After setting up a virtual environment, run the `run_forge.py` script to initiate the server and the initial configuration wizard. The modular structure makes it easy to customize the UX or add new data points to the telemetry dashboard.

---

## 🎛️ Configuration & Customization

The real magic of this tool lies in its ability to be tuned to your specific nuance.

- **The `forge_config.yaml` File:** Here, you can set your training split preferences (e.g., Upper/Lower, Push/Pull/Legs), define your maximum recoverable volume per muscle group, and even adjust the "aggressiveness" of the AI's progression algorithm. This file is the steering wheel of your training vehicle.
- **Custom Exercise Database:** The system comes equipped with a robust library of over 500 exercises, each tagged with primary and secondary muscles, equipment type, and difficulty rating. You can easily add your own obscure gym machinery or rehabilitation movements.
- **Integration with Wearables:** You can extract your health data from brands like FitBit or Apple Health via their exported CSV files. The forge recognizes this data and automatically connects it to your subjective energy journal entries, creating a rich tapestry of context.

---

## 🗺️ Roadmap: The Future of the Forge

The journey doesn't end here. The following features are on the anvil for the 2026 release cycle:

- **Smart Periodization Engine v3.0:** An overhaul to include conjugate method templates and block periodization logic.
- **Social Comparison Sandbox:** An anonymous mechanism to compare your progression stats against aggregate community data (with strict privacy controls).
- **Voice Command Integration:** "Hey Forge, log 5 reps of 225 on bench press." The system will transcribe and log instantly.
- **Advanced Injury Prevention Radar:** Utilizes asymmetry detection algorithms to flag potential overuse imbalances before they become painful.

---

## 🤝 Contributing to the Forge

This is a solo project, but the road is smoother with company. While I am the most active contributor, I welcome suggestions from anyone discovering this repository. If you have a clever algorithm for detecting staleness or a beautiful CSS theme, please fork the repository and submit a pull request.

**Contribution Guidelines:**
1.  Ensure your code is commented and follows the existing PEP-8 style where applicable.
2.  If adding a new feature, please update the corresponding documentation.
3.  For major changes, open a discussion first to align on the scope.

---

## 📜 License

This project is open-sourced under the MIT License, offering you the freedom to use, modify, and distribute this software. It is a gift to the fitness and DIY-tech community.

[Licensed under the MIT License](LICENSE).

---

## ⚠️ Disclaimer & Health Responsibility

This software is a powerful organizational tool, but it is **not** a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or another qualified health provider with any questions you may have regarding a medical condition.

- **Use at Your Own Risk:** The creators and maintainers (me) disclaim any liability for injury, loss, or damage resulting from the use of this software.
- **Training Limitations:** The algorithms provide suggestions, not mandates. Always listen to your body. If an exercise causes pain, stop immediately.
- **Data Accuracy:** The quality of the AI's advice is directly proportional to the quality of the input data. Garbage in, garbage out. Be honest with your journal entries.

---

## 🧰 Support & Community

For help with technical issues, questions about specific features, or just to share your progress story, please utilize the **GitHub Issues** section.

- **Bug Reports:** Clearly outline the steps to reproduce the issue and the expected outcome.
- **Feature Requests:** Use the dedicated template. Explain *why* the feature would be useful to your training.
- **General Q&A:** Use the Discussions tab for unstructured conversations about training philosophies and code.

I commit to providing **24/7 support** for pressing matters, typically responding within a single business day.

---

## 🧭 Final Words: The Repetition of Life

Gymnasium Forge is not merely a repository of code; it's a repository of willpower. It represents the belief that the path to strength is not through blind obedience, but through intelligent observation and thoughtful adaptation. I invite you to explore the code, challenge the logic, and forge your strongest self.

*"The weight you lift is a measure of your past; the way you lift it is a blueprint for your future."* — The Logbook of Forge v1.0.