<div align="center">

<pre>
              _
 _   ______ _(_)___  ____  ____  _____
| | / / __ `/ / __ \/ __ \/ __ \/ ___/
| |/ / /_/ / / / / / / / / /_/ / /
|___/\__,_/_/_/ /_/_/ /_/\____/_/
</pre>

**Homelab, air traffic control tooling, and whatever else is running this week.**

<a href="https://vainnor.com"><img alt="vainnor.com status" src="https://img.shields.io/website?url=https%3A%2F%2Fvainnor.com&label=vainnor.com&up_message=online&down_message=offline&up_color=B5A8F5&down_color=E5675F&labelColor=10141B&style=flat-square"></a>

<img alt="Rust" src="https://img.shields.io/badge/-Rust-E8803F?style=flat-square"> <img alt="React" src="https://img.shields.io/badge/-React-4FC3D0?style=flat-square"> <img alt="Kubernetes" src="https://img.shields.io/badge/-Kubernetes-6F9FD8?style=flat-square"> <img alt="Proxmox" src="https://img.shields.io/badge/-Proxmox-E6A52E?style=flat-square"> <img alt="VATSIM" src="https://img.shields.io/badge/-VATSIM-94C47D?style=flat-square">

[ [vainnor.com](https://vainnor.com) ] &nbsp; [ [Status](https://status.vainnor.com) ] &nbsp; [ [Git](https://git.vainnor.com) ] &nbsp; [ [mainlinesim.com](https://mainlinesim.com) ] &nbsp; [ [vzdc.org](https://vzdc.org) ]

</div>

```text
vainnor@lab:~$ whoami
vainnor
vainnor@lab:~$ cat about.txt
Founder of Mainline Sim.
Runs a Kubernetes homelab on Proxmox.
Writes Rust and React.
Does ATC work on VATSIM: training tools and ARTCC websites.
vainnor@lab:~$ █
```

## Projects

| Project | What it is |
| :-- | :-- |
| [Mainline Sim](https://mainlinesim.com) | Founder. A US freight and passenger train simulator, in development. |
| [Stepclimb](https://github.com/Vainnor/stepclimb) | An open-source learning platform with courses, server-graded exams, practice games, and integrations. Built with Rust and React. |
| [vZDC Website](https://github.com/vZDC-ARTCC/website) | A website for a VATSIM subdivision. |
| [vZDC IDS](https://github.com/vZDC-ARTCC/ids) | The vZDC ARTCC's modern take on an IDS. |
| [zdc-cli](https://github.com/Vainnor/zdc-cli) | A command-line tool for the vZDC ARTCC. |
| [Muster](https://github.com/Vainnor/muster) | A small, fast desktop app launcher for Windows, macOS, and Linux, with app groups you can launch in one click. |
| [Tessera](https://github.com/Vainnor/tessera) | A local-first notes app built on plain Markdown files, with end-to-end encrypted sync. |
| [AvioDeck](https://aviodeck.app) | Free flight sim tools for streamers, pilots, and controllers: stream overlays, Twitch automation, a Discord bot, and VATSIM tools. |

## VainnorLabs

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#161B24','primaryTextColor':'#D3D9E2','primaryBorderColor':'#B5A8F5','lineColor':'#B5A8F5','fontFamily':'monospace'}}}%%
flowchart LR
    pve["Proxmox"] --> k8s["Kubernetes"]
    k8s --> auth["Auth"]
    k8s --> git["Git"]
    k8s --> secrets["Secrets manager"]
    k8s --> rest["...and the rest"]
```

| Service | What it does |
| :-- | :-- |
| [status.vainnor.com](https://status.vainnor.com) | Is everything up? Checked once a minute. |
| [git.vainnor.com](https://git.vainnor.com) | The forge. |

## Elsewhere

| | |
| :-- | :-- |
| [GitHub](https://github.com/Vainnor) | Code, mostly. |
| [Mainline Sim](https://mainlinesim.com) | The train sim I founded. |
| [vZDC](https://vzdc.org) | The Virtual Washington ARTCC on the VATSIM network. |
| [vainnor.com](https://vainnor.com) | My homepage. |

<div align="center">
<sub>VainnorLabs // <a href="https://status.vainnor.com">Status</a></sub>
</div>
