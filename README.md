
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2340,100:70A5FD&height=220&section=header&text=Hi%20there%2C%20I'm%20Bala%20%F0%9F%91%8B&fontSize=40&fontColor=fff&animation=fadeIn&fontAlignY=34&desc=AI%20%26%20Data%20Science%20Engineer%20%C2%B7%20Building%20intelligent%2C%20data-driven%20systems&descAlignY=52&descSize=17&stroke=70A5FD&strokeWidth=1" width="100%"/>
</p>

<!-- 2. TYPING HEADER -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1200&color=70A5FD&center=true&vCenter=true&width=800&height=45&lines=B.Tech+AI+%26+Data+Science+Student;Machine+Learning+Engineer+Intern+%40+CubeAI+Solutions;Building+AI+Voice+Agents+%7C+STT+%2B+LLMs+%2B+TTS;Exploring+Computer+Vision+%26+Cloud+Systems" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:balamurugan250604@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/balamurugan2506"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=balamurugan2506&label=Profile%20Views&color=70a5fd&style=for-the-badge" alt="profile views" />
  <img src="https://img.shields.io/badge/Location-Coimbatore%2C%20India-70A5FD?style=for-the-badge&logo=googlemaps&logoColor=white"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</p>

---

### 💻 About Me

<img align="right" width="380" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

```python
from dataclasses import dataclass, field
from enum import Enum, auto
from functools import cached_property


class Focus(Enum):
    AI_ML = auto()
    COMPUTER_VISION = auto()
    CLOUD_SYSTEMS = auto()


@dataclass(frozen=True, slots=True)
class Engineer:
    name: str = "Bala Murugan M"
    location: str = "Coimbatore, Tamil Nadu, India"
    degree: str = "B.Tech · AI & Data Science"
    college: str = "PSG Institute of Technology and Applied Research"

    stack: dict[str, list[str]] = field(default_factory=lambda: {
        "languages": ["Python", "HTML", "CSS"],
        "ai_ml": ["Machine Learning", "LLMs", "NLP", "BERT",
                  "Sentence Transformers", "LangChain", "OpenAI API"],
        "frameworks": ["Streamlit", "Pygame"],
        "cloud": ["Oracle Cloud Infrastructure (OCI)"],
    })

    focus_areas: tuple[Focus, ...] = (
        Focus.AI_ML, Focus.COMPUTER_VISION, Focus.CLOUD_SYSTEMS,
    )

    fun_fact: str = "Coordinated a hackathon with 1,400+ participants!"

    @cached_property
    def all_skills(self) -> list[str]:
        return [skill for group in self.stack.values() for skill in group]

    def __str__(self) -> str:
        return f"Turning data into decisions, one model at a time. 🚀"


if __name__ == "__main__":
    me = Engineer()
    print(me)
```



- 🎓 Currently pursuing **B.Tech in AI & Data Science** at PSG Institute of Technology and Applied Research
- 🧠 Machine Learning Engineer Intern at **CubeAI Solutions**
- 🗣️ Building an **AI Voice Agent System** (STT → LLM → TTS pipeline)
- 🏆 2nd Place, Project Expo – Department of AI & DS
- ☁️ Oracle Cloud Infrastructure 2025 Certified AI
- 📫 Reach me at **balamurugan250604@gmail.com**

<br clear="right"/>

---

### 🛠️ Tech Stack

<p align="center"><b>Languages</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

<p align="center"><b>AI · ML · NLP</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/BERT-FFB000?style=for-the-badge&logo=googlescholar&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Sentence%20Transformers-8A2BE2?style=for-the-badge&logo=huggingface&logoColor=white"/>
</p>

<p align="center"><b>Frameworks & Tools</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pygame-00B140?style=for-the-badge&logo=python&logoColor=white"/>
</p>

<p align="center"><b>Cloud & DevOps</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Oracle%20Cloud%20Infrastructure-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
</p>

---

### 📊 GitHub Stats

<div align="center">
  <a href="https://github.com/balamurugan2506">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=balamurugan2506&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=70a5fd&icon_color=bf91f3&text_color=c9d1d9&border_radius=10"/>
  </a>
  <a href="https://github.com/balamurugan2506">
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=balamurugan2506&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=70a5fd&text_color=c9d1d9&langs_count=8&border_radius=10"/>
  </a>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=balamurugan2506&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=38BDAE&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0D1117&border_radius=10"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=balamurugan2506&theme=tokyo-night&bg_color=0d1117&color=70a5fd&line=bf91f3&point=38bdae&area=true&hide_border=true"/>
</div>

---

### 🏆 Trophy Wall

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=balamurugan2506&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=4"/>
</div>

---

### 💼 Work Experience

<details>
<summary><b>Machine Learning Engineer Intern @ CubeAI Solutions</b> — Nov 2025 – Feb 2026 | Tiruchengode, Tamil Nadu</summary>
<br>

> `Python` `LLMs` `Speech-to-Text` `Text-to-Speech` `AI Pipelines`

- Designed and built an **end-to-end AI Voice Agent System**, integrating STT, LLMs, and TTS into a single conversational pipeline.
- Architected the pipeline to handle real-time voice input, language model reasoning, and natural speech output.
- Collaborated within an ML engineering workflow to deliver a functional, production-oriented voice agent prototype.

</details>

---

### 🚀 Featured Projects

<div align="center">

| Project | Stack | Highlights |
|---|---|---|
| **[Atlas Protocol](#)** | Pygame · LangChain · OpenAI API | AI-powered RPG enabling players to interact with an evolving AI character through **dynamic quests and real-time conversations** |
| **[Fake News Detection System](#)** | Streamlit · BERT · Sentence Transformers | Real-time misinformation detection web app using **semantic similarity & text classification** with transformer models |
| **AI Voice Agent System** | STT · LLMs · TTS | End-to-end conversational voice pipeline built during ML internship at **CubeAI Solutions** |

</div>

---

### 🏅 Achievements

<div align="center">

| 🏆 | Achievement | Details |
|---|---|---|
| 🥈 | Project Expo — 2nd Place | Awarded by Department of AI & DS for outstanding performance, creativity, and dedication |
| ☁️ | Oracle Cloud Infrastructure 2025 Certified AI | Certified in AI/ML fundamentals, data science workflows & OCI AI services |
| 🎤 | Student Coordinator — ITech Summit Hackathon | Coordinated a 2-round hackathon with **410+ teams** and **1,400+ participants** |

</div>

---

### 🎓 Education

<div align="center">

| Degree | Institution | Year | Score |
|---|---|---|---|
| B.Tech, Artificial Intelligence & Data Science | PSG Institute of Technology and Applied Research, Coimbatore | 2024 – 2027 | In Progress |
| Diploma, Computer Science | Sankar Polytechnic College, Tamil Nadu | 2022 – 2024 | — |

</div>

### 📚 Currently Learning

```text
🧱 Computer Vision        → Image Processing, OpenCV, Deep Learning Models
🧱 Voice Agent Pipelines  → STT → LLM Reasoning → TTS
🧱 Cloud-Native AI        → Oracle Cloud AI Services, Deployment Pipelines
```

---

### 🤝 Let's Connect

<p align="center">
  <a href="mailto:balamurugan250604@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/balamurugan2506"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<p align="center"><i>💡 "Turning data into decisions, one model at a time."</i></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:70A5FD,50:1a2340,100:0d1117&height=140&section=footer&animation=fadeIn" width="100%"/>
</p>
