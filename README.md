<!--
README.md для профиля GitHub.
Как использовать:
1) Создай репозиторий с названием ровно как твой username (например: isac-asimov/isac-asimov)
2) Добавь этот README.md в корень
3) Замени плейсхолдеры: <...>
-->

<div align="center">

# Isac Asimov
### ML / Deep Learning • Research Engineer (Applied) • Quality & Training Recipes

<!-- Бейджи (замени ссылки при желании) -->
<p>
  <a href="https://www.linkedin.com/in/<your-linkedin>/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"/></a>
  <a href="https://scholar.google.com/citations?user=<your-scholar-id>"><img alt="Google Scholar" src="https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=white"/></a>
  <a href="mailto:<your-email>"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white"/></a>
</p>

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/>
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white"/>
  <img alt="CUDA" src="https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white"/>
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"/>
</p>

</div>

---

## 👋 About
Я инженер-исследователь в ML/DL: **улучшаю качество моделей через training recipes, data-centric подходы и строгую оценку**.
Люблю задачи, где нужно не просто “натюнить”, а **доказать**, что улучшение настоящее: абляции, повторяемость, устойчивость к сдвигу.

- 🔭 Фокус: **качество / стабильность обучения / data-centric improvements / evaluation**
- 🧪 Подход: **reproducible experiments → ablations → robust eval → clean report**
- 🎯 Интерес: Vision & NLP/LLM (fine-tuning / small-LM training), robustness, calibration

---

## 🧠 Core Competencies
**ML Research Engineering**
- Design of experiments: baselines, ablations, seeds, статистическая устойчивость
- Training recipes: optimizer/scheduler, regularization, augmentations, EMA, stabilization
- Data-centric: sampling, filtering, hard examples, noise handling, curriculum
- Evaluation: robust metrics, calibration (ECE), stress tests, distribution shift

**Engineering**
- PyTorch (custom train loop), mixed precision, checkpointing, profiling
- Datasets & pipelines, configs (Hydra/argparse), experiment tracking (W&B/MLflow)
- Packaging: clean repos, reproducible runs, CI sanity checks

---

## 🧰 Tech Stack
- **Languages:** Python, (немного C++/CUDA при необходимости)
- **DL:** PyTorch, torchvision, 🤗 Transformers (и собственные лупы)
- **Tracking:** Weights & Biases / MLflow
- **Infra:** Docker, Linux, GitHub Actions
- **Data:** numpy/pandas, parquet, webdataset (опционально)

---

## ⭐ Featured Projects (приколи сюда “пиннутые” репозитории)
> Ниже — структура, которую удобно масштабировать. Замени на реальные ссылки.

### 1) Training Recipe Bench — Vision
**Repo:** `vision-recipe-bench` → https://github.com/<username>/vision-recipe-bench  
**Что сделал:** воспроизвел baseline, провел 20+ абляций, собрал “best recipe” и оценил robustness.  
**Highlights:**
- ✅ Baseline + multi-seed eval
- ✅ Таблица абляций (LR, WD, aug, mixup/cutmix, EMA, warmup/cosine)
- ✅ Robustness suite: corruption/noise/shift
- ✅ Отчёт: что и почему работает

**Key Results (пример):**
| Model | Dataset | Baseline | Best Recipe | Δ |
|------|---------|----------|-------------|---|
| ViT-Tiny | Imagenette | 0.XX | 0.XX | +X.X |

---

### 2) NLP Fine-tuning Discipline
**Repo:** `nlp-ft-discipline` → https://github.com/<username>/nlp-ft-discipline  
**Что сделал:** построил строгий пайплайн fine-tuning + калибровка + оценка стабильности по seed’ам.  
**Highlights:**
- ✅ Layer-wise LR decay, warmup, regularization
- ✅ Calibration (temperature scaling), ECE
- ✅ Error analysis: confusion, slice eval

---

### 3) Small LM Training (mini foundation-style)
**Repo:** `small-lm-lab` → https://github.com/<username>/small-lm-lab  
**Что сделал:** обучил небольшой transformer LM, сравнил токенизацию/packing/schedules, улучшил perplexity.  
**Highlights:**
- ✅ Custom training loop + eval perplexity
- ✅ Data filtering/dedup + curriculum (опционально)
- ✅ Reproducible configs + logs + report

---

## 📊 Reproducibility & Experimental Standards
**Я считаю “готовым” эксперимент только если:**
- Baseline описан и воспроизводится командой `python train.py ...`
- Есть **абляции** (одна переменная за раз)
- Есть **multi-seed** (хотя бы для ключевых сравнений)
- Есть корректная валидация без утечек
- Есть короткий отчёт: *что пробовал, что не сработало, почему так думаю*

---

## 🧪 Results & Reports
- 📄 `results/` — таблицы абляций, графики обучения, robustness & calibration
- 🧾 `reports/` — краткие “mini-paper” README: motivation → setup → results → takeaways
- 🧩 `configs/` — все конфиги экспериментов (версии и параметры)

---

## 🧩 Open Source Contributions
- PRs: https://github.com/<username>?tab=pulls  
- Issues/Discussions: https://github.com/<username>?tab=issues  

*(Добавь 2–3 самых сильных PR с кратким описанием “что улучшил и зачем”.)*

---

## 🏆 Highlights (коротко)
- **Ablation-first mindset:** “сначала доказать прирост, потом усложнять”
- **Data-centric improvements:** качество данных > магия архитектуры
- **Robust evaluation:** устойчивость важнее одной метрики на clean split

---

## 📚 Reading / Notes (опционально, выглядит “по-взрослому”)
**Repo:** `ml-notes` → https://github.com/<username>/ml-notes  
- конспекты статей + реплики экспериментов
- списки “что проверить, когда обучение нестабильно”
- шаблоны отчётов абляций

---

## 📫 Contact
- Email: <your-email>
- LinkedIn: https://www.linkedin.com/in/<your-linkedin>/
- Telegram: https://t.me/<your-handle> (опционально)

---

## 🧾 Quick Links
- CV (PDF): <link-to-cv>
- Portfolio index: https://github.com/<username>?tab=repositories

---

<details>
<summary>📝 README Changelog / Notes</summary>

- Версия README: v1
- Принцип: меньше маркетинга, больше доказуемых результатов
- Обновляй “Featured Projects” и “Key Results” каждые 1–2 месяца

</details>
