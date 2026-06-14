# Sovithyea Prach

**CS/IT Student · Melbourne, Australia **

I'm a Computer Science student with a strong interest in machine learning, data-driven problem solving, and building things that bridge software with the real world. I enjoy projects where the outcome is measurable — from predictive models with trackable accuracy to apps that solve a genuine personal need.

Currently open to **internship opportunities** in software engineering, data science, or ML — Melbourne or remote.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**ML & Data Science**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)

**Mobile & Tools**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Room DB](https://img.shields.io/badge/Room_DB-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Featured Projects

### [World Cup 2026 Winner Predictor](https://github.com/sovithyea/2026_worldcup_prediction)

A machine learning pipeline that forecasts tournament win probabilities for all 48 World Cup 2026 nations using historical match data, ELO ratings, and Monte Carlo simulation.

Rather than predicting a single winner, the model simulates the entire 48-team tournament 10,000 times to produce a probability distribution — a more statistically honest approach that respects the inherent randomness of knockout football.

**Highlights:**
- Trained on 49,000+ international match records (1872–present, filtered to 1994+)
- Dynamic ELO rating system that updates after every match and weights competitive fixtures over friendlies
- TimeSeriesSplit cross-validation to prevent data leakage across time
- Achieves ~57% accuracy on held-out matches vs 48.5% naive baseline

**Tech:** `Python` `XGBoost` `scikit-learn` `Pandas` `NumPy`

---

### [2026 F1 Race Predictor](https://github.com/sovithyea/2026_f1_prediction)

A live-updating race prediction system that forecasts finishing positions for every round of the 2026 Formula 1 World Championship, trained incrementally on real FastF1 telemetry data as the season progresses.

The model automatically fetches and integrates new session data each race weekend, using FP1/FP2/FP3 best-lap deltas and qualifying gaps as primary features — with FP2 long-run pace weighted most heavily as the strongest race-pace indicator.

**Highlights:**
- Gradient Boosting Regressor trained on all completed 2026 rounds, growing more accurate as the season unfolds
- 5-stage workflow per race weekend (FP1 → FP2 → FP3 → qualifying → result), with intelligent fallback for sprint weekends
- Automatic FastF1 API integration with local caching; season accuracy tracked via `tracker.py`
- Correctly predicts podium positions across 7 completed rounds

**Tech:** `Python` `scikit-learn` `FastF1` `Pandas` `Matplotlib`

---

### [Instagram Stats Tracker](https://github.com/sovithyea/instagram_stats_tracker) (In Progress)

A privacy-focused web dashboard for analysing your Instagram social graph using your official data export — no third-party services, no API access required.

Parses Instagram's JSON export, computes follower/following set differences, and presents a clean breakdown of followers, unfollowers, and account history. Supports multiple accounts with PIN-based access control. All processing runs client-side; no data leaves the browser.

**Tech:** `JavaScript` `HTML` `CSS`

---

### [Claude API in Python](https://github.com/sovithyea/claude_api_in_python)

A structured Python integration for calling Anthropic's Claude models programmatically — demonstrating clean API request handling, response parsing, and building AI-powered workflows beyond the chat interface.

**Tech:** `Python` `Anthropic SDK`

---

### [Ktis Cafe Website](https://github.com/sovithyea/st287_ktiscafe_website)

A hand-coded cafe website built from scratch for a personal project, demonstrating responsive layout, custom CSS styling, and clean semantic HTML — no frameworks or templates.

**Tech:** `HTML` `CSS`

---

### [CRUD Note App — Android](https://github.com/sovithyea/crud_note_app)

A modern Android notes application with full Create, Read, Update, and Delete functionality, built in Kotlin with Room database persistence and a clean DAO architecture for local, offline-first data management.

**Tech:** `Kotlin` `Android` `Room DB`

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sovithyea&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Sovithyea's GitHub Stats" height="165"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sovithyea&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sovithyea&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sovithyea-prach)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sovithyea)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sovithyea&color=6366f1&style=flat-square&label=profile+views" alt="Profile views"/>
</p>
