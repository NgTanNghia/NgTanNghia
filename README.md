# 👋 Xin chào, mình là Nguyễn Tấn Nghĩa

```python
import sys
from dataclasses import dataclass, field

@dataclass
class Developer:
    name: str = "Nguyễn Tấn Nghĩa"
    alias: str = "Tnghia"
    year: int = 2009
    origin: str = "Gia Lai · Bình Định cũ"
    languages: list = field(default_factory=lambda: ["Python", "Java"])
    interests: list = field(default_factory=lambda: ["Coding", "Gaming", "Music", "Chill"])

    def display(self):
        bar = "─" * 38
        print(f"\n  {bar}")
        print(f"  tng@dev  ~  profile.py")
        print(f"  {bar}")
        print(f"\n  {'name':<12} {self.name}")
        print(f"  {'alias':<12} {self.alias}")
        print(f"  {'born':<12} {self.year}")
        print(f"  {'origin':<12} {self.origin}")
        print(f"\n  [languages]  {' · '.join(self.languages)}")
        print(f"  [interests]  {' · '.join(self.interests)}")
        print(f"\n  {bar}")
        print(f"  ∞  still learning · building things · having fun _\n")

Developer().display()
```

## 🌈 Về mình

🎓 **Học sinh — sinh năm 2009**

📍 **Quê quán:** Gia Lai, Bình Định cũ

💻 **Ngôn ngữ:** `PYTHON` · `JAVA`

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NgTanNghia&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF6EC7&icon_color=00E5FF&text_color=FFFFFF" alt="GitHub Stats">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NgTanNghia&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF6EC7&text_color=FFFFFF" alt="Top Languages">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=NgTanNghia&theme=radical&hide_border=true&background=0D1117&ring=FF6EC7&fire=00E5FF&currStreakLabel=FFFFFF" alt="GitHub Streak">
</p>

---

## 🌈 Rainbow Divider

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=header&text=Thanks%20for%20visiting!&fontSize=30&fontColor=ffffff" alt="Rainbow Divider">
</p>

---

## 🐍 Snake ăn contribution

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake">
</p>

---

### 💬 Quote

> **"Code không khó, chỉ cần kiên nhẫn + 1 ly trà sữa"** 🧋

---

<p align="center">
  <b>Thanks for visiting my profile! ❤️</b>
</p>
