<h1 align="center"> Hi there, I'm Ariel Aprielyullah</h1>
<h3 align="center">Fullstack Developer | Python & PHP </h3>

<p align="center">
  <a href="https://github.com/lemzhr">
    <img src="https://komarev.com/ghpvc/?username=lemzhr&label=Profile%20views&color=blueviolet&style=flat" alt="lemzhr" />
  </a>
  <a href="https://github.com/lemzhr?tab=followers">
    <img src="https://img.shields.io/github/followers/lemzhr?label=Followers&style=social" />
  </a>
</p>

<p align="center">
  <img src="https://developer-life.vercel.app/banner.svg" alt="Developer Life Banner"/>
</p>

---

## About Me
- 🔭 I'm currently building **web** using `Next.js` + `Python`
- 🌱 I’m learning advanced backend topics: `FastAPI`, `Prisma`, `Microservices`
- 💬 Ask me about: `Python`, `PHP`, `Next.js`, `MySQL`, `Tailwind`, `REST APIs`
- 📧 Reach me: **ariefox46461@gmail.com**
- 🎨 I love turning ideas into responsive, animated user experiences

---

## 🛠️ Languages & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,nextjs,react,php,js,html,css,mysql,tailwind,bootstrap,github,figma" />
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lemzhr&show_icons=true&theme=tokyonight&border_radius=10&hide_border=true" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=lemzhr&theme=tokyonight&hide_border=true" width="48%"/>
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lemzhr&layout=compact&langs_count=10&theme=tokyonight&hide_border=true" width="48%"/>
</p>


---

## Connect With Me

<p align="center">
  <a href="mailto:ariefox46461@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://instagram.com/lemzhr"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
  <a href="https://github.com/lemzhr"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://linkedin.com/in/ariel-aprielyullah-687243352"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

---

##  Fun Fact
```python
import time
import sys
import os
from colorama import init, Fore, Style

init(autoreset=True)

def ketik(teks, warna=Fore.WHITE, delay=0.04):
    for huruf in teks:
        sys.stdout.write(warna + huruf + Style.RESET_ALL)
        sys.stdout.flush()
        time.sleep(delay)
    print()

def garis(panjang=60):
    print(Fore.CYAN + "-" * panjang)

def bersihkan_layar():
    os.system('cls' if os.name == 'nt' else 'clear')

aktivitas = [
    (Fore.GREEN + "💻 Menulis baris kode...", 1.8),
    (Fore.YELLOW + "📚 Mempelajari dokumentasi...", 1.8),
    (Fore.BLUE + "😴 Tidur... (sebentar saja)", 1.5),
    (Fore.RED + "💥 Exception: Hidup tidak semudah itu!", 1.8),
    (Fore.MAGENTA + "☕ Membuat kopi untuk menyelamatkan hari...", 2),
    (Fore.CYAN + "🔁 Melanjutkan perjuangan ngoding...", 2)
]

def intro():
    bersihkan_layar()
    garis()
    ketik("🧠  Selamat datang di Simulasi Hidup Seorang Developer!", Fore.LIGHTBLUE_EX, 0.05)
    ketik("⌛  Bersiaplah untuk melihat siklus harian yang tak berujung...", Fore.LIGHTWHITE_EX)
    garis()
    time.sleep(2)

def outro():
    ketik("\n👨‍💻 Hidup developer memang keras, tapi komunitas membuatnya lebih ringan.", Fore.LIGHTMAGENTA_EX, 0.07)
    ketik("📌 Ingat: Jangan lupa istirahat dan minum air putih ya 💧", Fore.LIGHTGREEN_EX)
    ketik("👋 Sampai jumpa! Tetap semangat dan terus belajar 💡", Fore.LIGHTYELLOW_EX, 0.08)
    garis()

def mulai_simulasi(siklus=3):
    intro()
    for i in range(siklus):
        garis()
        ketik(f"🌐  Siklus ke-{i+1} dimulai...\n", Fore.LIGHTCYAN_EX)
        for aksi, jeda in aktivitas[:3]:
            ketik(aksi)
            time.sleep(jeda)
        for aksi, jeda in aktivitas[3:]:
            ketik(aksi)
            time.sleep(jeda)
        garis()
        ketik(f"✔️  Siklus ke-{i+1} selesai", Fore.LIGHTGREEN_EX)
        time.sleep(1)
    outro()

if __name__ == "__main__":
    mulai_simulasi()
