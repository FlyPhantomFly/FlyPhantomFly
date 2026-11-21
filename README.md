<!-- ═══════════════════════════════════════════════════════════════════
     FlyPhantomFly, github profile readme

     github strips js and css from readmes, so the moving parts here
     are server rendered svg plus two github actions:

       - capsule-render: header fade in, blinking $ exit footer
       - readme-typing-svg: the typing loop
       - streak-stats: the animated ring
       - contribution snake: .github/workflows/snake.yml, pushed to
         the output branch
       - 3d wall: .github/workflows/profile-3d.yml, committed to
         profile-3d-contrib/

     the snake and the wall show up after the first workflow run.
     palette: #0D1117 dark, #059669 darker emerald, #172554 midnight navy
     ═══════════════════════════════════════════════════════════════════ -->

<div align="center">

<a href="https://github.com/FlyPhantomFly">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:172554,50:059669,100:172554&height=200&section=header&text=FlyPhantomFly&fontSize=45&fontColor=E6EDF3&animation=fadeIn&fontAlignY=35" width="100%" alt="FlyPhantomFly" />
</a>

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?lines=i+break+phones+on+purpose;parrot+os+is+my+daily+driver%2C+not+a+VM;asking+llms+questions+they%27d+rather+not+answer;reverse+engineering%3A+everything+confesses&font=JetBrains+Mono&size=22&color=059669&center=true&vCenter=true&width=700&height=45&duration=4000&pause=1000" alt="Typing SVG" />
</a>

<br/>
<br/>

<a href="https://github.com/FlyPhantomFly?tab=followers"><img src="https://img.shields.io/github/followers/FlyPhantomFly?label=Followers&style=flat-square&color=172554&labelColor=0D1117" alt="Followers" /></a>
<a href="https://github.com/PhantomThreads"><img src="https://img.shields.io/badge/My%20other%20shadow-PhantomThreads-059669?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="PhantomThreads" /></a>
<img src="https://komarev.com/ghpvc/?username=FlyPhantomFly&color=059669&style=flat-square&label=VISITORS" alt="Visitors" />
<img src="https://img.shields.io/badge/OS-Parrot%20Security-059669?style=for-the-badge&logo=linux&logoColor=white&labelColor=0D1117" alt="Parrot Security OS" />

</div>

<br/>

## `$ whoami`

```bash
phantom@parrot:~$ whoami
FlyPhantomFly. PhantomThreads is the one you don't see.

phantom@parrot:~$ cat ~/profile.md
i break android phones, mostly on purpose. i run parrot as a daily
driver and treat it like one. some days i fine tune small llms and
ask them questions they'd rather not answer. the rest of the time
something gets disassembled. carefully. mostly legally.

phantom@parrot:~$ ps aux | grep -i passion
USER              COMMAND
android           roms --kernels --kernelsu --adb-surgery --smali
parrot-linux      kde-desktop --pentest-toolbox
llm-research      ablation --evals --local-inference --token-burning
reverse-eng       apk --elf --firmware --everything-is-reversible

phantom@parrot:~$ history | tail -4
  101  adb shell su -c "curiosity > warranty"
  102  parrot-upgrade && echo "still flying"
  103  python ablation.py --model small --tokens too-many =]
  104  r2 -A target.bin   //read the disassembly, not the docs

phantom@parrot:~$ logout
Connection to github closed by phantom. [process exited 0]
```

<br/>

---

## android stuff

> my phone does what i tell it to. most days...

- custom roms and kernels, flashed irresponsibly
- KernelSU + Neozygisk + Vector.
- adb surgery and smali reading for when the source code lies
- my phone often hates me

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=androidstudio,kotlin,java,gradle,c,cpp" alt="Android skills" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/KernelSU-root-172554?style=for-the-badge&logo=kernelsu&logoColor=white&labelColor=0D1117" alt="KernelSU" />
  <img src="https://img.shields.io/badge/Termux-pocket%20linux-172554?style=for-the-badge&logo=termux&logoColor=white&labelColor=0D1117" alt="Termux" />
  <img src="https://img.shields.io/badge/LineageOS-ROMs-172554?style=for-the-badge&logo=lineageos&logoColor=white&labelColor=0D1117" alt="LineageOS" />
</p>

---

## the parrot setup

> full time Parrot Security OS. the toolbox is home. home is a toolbox.

- parrot security os, installed on metal. not a VM
- debian underneath, terminal on top
- somewhere there's a script that rebuilds all of this from a bare ISO, if only I could find it

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=linux,debian,bash,vim,git,githubactions,docker" alt="Parrot / Linux skills" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Debian-the%20base-059669?style=for-the-badge&logo=debian&logoColor=white&labelColor=0D1117" alt="Debian" />
  <img src="https://img.shields.io/badge/zsh-muscle%20memory-059669?style=for-the-badge&logo=zsh&logoColor=white&labelColor=0D1117" alt="zsh" />
</p>

---

## llm research

> small models, big questions, and hardware that wasn't supposed to do this.

- fine tuning small models on hardware that has no business running them
- evals over vibes. what the model does, not what the model claims
- ablation speaks louder ;)
- prompt injection, jailbreak taxonomy, and defenses that actually hold

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,vscode" alt="AI / ML skills" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hugging%20Face-models-172554?style=for-the-badge&logo=huggingface&logoColor=white&labelColor=0D1117" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Ollama-local%20LLM-172554?style=for-the-badge&logo=ollama&logoColor=white&labelColor=0D1117" alt="Ollama" />
</p>

---

## reverse engineering

> APKs, ELFs, firmware. sooner or later everything confesses.

- jadx, ida and frida for apks.
- radare2, ida assist, unicorn and edbg for binaries, plus packers that fight back
- binwalk, dissect and volatility for firmware and memory forensics
- wireshark, mitm and burp for traffic. the network never lies for long

<p align="center">
  <img src="https://img.shields.io/badge/Ghidra-SRE-059669?style=for-the-badge&logo=ghidra&logoColor=white&labelColor=0D1117" alt="Ghidra" />
  <img src="https://img.shields.io/badge/IDA%20Pro-decompiler-059669?style=for-the-badge&labelColor=0D1117" alt="IDA Pro" />
  <img src="https://img.shields.io/badge/IDA%20Assist-AI%20copilot-059669?style=for-the-badge&labelColor=0D1117" alt="IDA Assist" />
  <img src="https://img.shields.io/badge/radare2-cli-059669?style=for-the-badge&logo=radare2&logoColor=white&labelColor=0D1117" alt="radare2" />
  <img src="https://img.shields.io/badge/Frida-hooks-059669?style=for-the-badge&logo=frida&logoColor=white&labelColor=0D1117" alt="Frida" />
</p>

<p align="center">
  <sub>for interop, security research, and making software behave.</sub>
</p>

---

## the numbers

<div align="center">
  <a href="https://github.com/FlyPhantomFly">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=FlyPhantomFly&show_icons=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=059669&icon_color=172554&text_color=C9D1D9&border_color=172554&ring_color=059669" alt="FlyPhantomFly's GitHub stats" />
  </a>
  <a href="https://github.com/FlyPhantomFly?tab=repositories">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FlyPhantomFly&layout=compact&langs_count=8&bg_color=0D1117&title_color=059669&text_color=C9D1D9&border_color=172554" alt="Top languages" />
  </a>
</div>

<div align="center">
  <a href="https://git.io/streak-stats">
    <img width="500" src="https://streak-stats.demolab.com/?user=FlyPhantomFly&background=0D1117&border=172554&stroke=161B22&ring=059669&fire=172554&currStreakNum=059669&currStreakLabel=C9D1D9&sideNums=C9D1D9&sideLabels=C9D1D9&dates=8B949E" alt="GitHub streak" />
  </a>
</div>

<details>
<summary><b>PhantomThreads, the other shadow</b></summary>
<br/>
<div align="center">
  <a href="https://git.io/streak-stats">
    <img width="500" src="https://streak-stats.demolab.com/?user=PhantomThreads&background=0D1117&border=172554&stroke=161B22&ring=059669&fire=172554&currStreakNum=059669&currStreakLabel=C9D1D9&sideNums=C9D1D9&sideLabels=C9D1D9&dates=8B949E" alt="PhantomThreads streak" />
  </a>
</div>

<div align="center">
  <a href="https://github.com/PhantomThreads?tab=repositories">
    <img height="130" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PhantomThreads&layout=compact&langs_count=8&bg_color=0D1117&title_color=059669&text_color=C9D1D9&border_color=172554" alt="PhantomThreads top languages" />
  </a>
</div>

<p align="center">
  <sub>the shadow is young. these cards fill in as it moves</sub>
</p>
</details>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.ashutosh-dwivedi0710.workers.dev/graph?username=FlyPhantomFly&bg_color=0D1117&color=8B949E&line=172554&point=059669&area=true&area_color=172554&title_color=059669&hide_border=true&custom_title=Contribution%20Activity" width="100%" alt="Contribution activity graph" />
</div>

<br/>

<div align="center">
  <img src="./profile-3d-contrib/profile-night-rainbow.svg" width="85%" alt="3D contribution calendar" />
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FlyPhantomFly/FlyPhantomFly/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FlyPhantomFly/FlyPhantomFly/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/FlyPhantomFly/FlyPhantomFly/output/github-contribution-grid-snake.svg" width="100%" alt="A snake eating the contribution graph" />
  </picture>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:172554,50:059669,100:172554&height=100&section=footer&text=%24%20exit&fontSize=25&fontColor=E6EDF3&animation=blinking" width="100%" alt="$ exit" />
</div>

<div align="center">
  <sub>built on Parrot Security OS, animated nightly by GitHub Actions. no javascript, no trackers, just svg</sub>
</div>
