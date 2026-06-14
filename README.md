# Hi, I'm Sovithyea Prach 

>  AI student @ Swinburne University of Technology based in Melbourne, Australia 🇦🇺

I write code that occasionally does what I want. Currently studying a Bachelor's of Computer Science, Majoring in Artificial Intelligence and building things that combine machine learning, data, and the sports I actually care about.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**ML & Data Science**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

**Web & Frameworks**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Room DB](https://img.shields.io/badge/Room_DB-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Material Design](https://img.shields.io/badge/Material_Design_3-757575?style=for-the-badge&logo=material-design&logoColor=white)

**Cloud & Tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---
## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sovithyea&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Sovithyea's GitHub Stats" height="165"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sovithyea&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&hide=jupyter%20notebook" alt="Top Languages" height="165"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sovithyea&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

## Featured Projects

### [World Cup 2026 Winner Predictor](https://github.com/sovithyea/2026_worldcup_prediction)
> *Because someone has to do the maths before the tournament.*

A full ML pipeline that predicts tournament win probabilities for all 48 World Cup 2026 nations — without picking one deterministic winner, because football doesn't work like that.

- **How it works:** Trains an XGBoost classifier on 49,000+ historical international matches (1994–present) to predict individual match outcomes (win/draw/loss), then simulates the entire tournament 10,000 times via Monte Carlo to produce win probabilities
- **Why it's interesting:** Uses dynamic ELO ratings (not FIFA rankings) that update after every match and weight tournament fixtures higher than friendlies. TimeSeriesSplit cross-validation ensures the model never "peeks" at future results
- **Results:** ~57% accuracy on held-out matches vs a 48.5% naive baseline
- **Tech:** `Python` `XGBoost` `Pandas` `NumPy` `scikit-learn`

---

### [2026 F1 Race Predictor](https://github.com/sovithyea/2026_f1_prediction) (Still Updating)
> *Predicting who DNFs so you don't have to.*

A live-updating machine learning system that predicts race finishing positions for every round of the 2026 Formula 1 season, trained on real FastF1 telemetry data as the season unfolds.

- **How it works:** A Gradient Boosting Regressor trains incrementally on completed 2026 race rounds, using qualifying gaps, FP1/FP2/FP3 session deltas, and team performance scores as features. Predictions auto-update as new session data becomes available each race weekend
- **Why it's interesting:** The model adapts in real-time across a live season — it gets smarter after every GP. FP2 long-run pace is weighted most heavily as the strongest race-pace signal, with graceful fallback for sprint weekends (no FP3)
- **Currently tracking:** 7 rounds complete, season accuracy logged via `tracker.py`
- **Tech:** `Python` `scikit-learn` `FastF1` `Pandas` `Matplotlib`

---

### [Instagram Stats Tracker](https://github.com/sovithyea/instagram_stats_tracker) (In Progress)
> *Find out who unfollowed you. No third-party app required.*

A privacy-first web dashboard that parses your official Instagram data export and gives you a complete breakdown of your social graph — who follows you, who doesn't follow back, unfollowers, and full account history. Runs entirely in your browser; no data leaves your device.

- **How it works:** Reads Instagram's JSON export format, computes set differences between followers and following lists, and renders a clean dashboard with filterable tables and history views
- **Why it's interesting:** No scraping, no Instagram API, no privacy concerns. Supports multiple accounts with PIN protection so housemates can't snoop
- **Tech:** `JavaScript` `HTML` `CSS`

---

### [Claude API in Python](https://github.com/sovithyea/claude_api_in_python)
> *Beyond the chat window.*

A clean Python integration layer for calling Anthropic's Claude models directly from code — for when the chat interface isn't enough.

- **Tech:** `Python` `Anthropic SDK`

---

### [Ktis Cafe Website](https://github.com/sovithyea/st287_ktiscafe_website)
> *Made with love for my mum's cafe.*

A hand-coded cafe website built from scratch — no frameworks, no templates. Just HTML, CSS, and the motivation of making something nice for someone who matters.

- **Tech:** `HTML` `CSS`

---

### [CRUD Note App — Android](https://github.com/sovithyea/crud_note_app)
> *Notes. On your phone. Offline. That's it.*

A modern Android notes app built in Kotlin with full CRUD functionality, local Room Database persistence, live search, pinned notes, and a usability-tested UI — backed by a formal study comparing toolbar icons vs pill buttons (pill buttons won: 26.3s avg vs 37.2s).

- **Tech:** `Kotlin` `Android` `Room DB` `Kotlin Coroutines` `Material Design 3` `RecyclerView`

---
 
## Coding Activity 
 
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=sovithyea&theme=tokyonight&hide_border=true&layout=compact" alt="WakaTime Stats"/>
</p>

---

## Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN-HERE)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sovithyea)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](prachsovithyea11@gmail.com)

> *Open to internship opportunities in software engineering, data, and ML — Melbourne or remote.*

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sovithyea&color=6366f1&style=flat-square&label=profile+views" alt="Profile views"/>
</p>
