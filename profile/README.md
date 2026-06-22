
<div align="center">
<img width="7550" height="1725" alt="image" src="https://github.com/user-attachments/assets/205065ec-03f8-411a-afa5-b886b3d8a6bc" />


[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=100&pause=1000&color=29BB33&center=true&vCenter=true&width=435&lines=Welcome+To+CROSS+THE+LINE!)](https://git.io/typing-svg)

### Tennis line judging system using yolo ball detection + marker ✨
**A mobile-based system for detecting tennis ball landing points and judging in/out decisions.**

</div>

---

## Links & QR

**Figma**  
(https://www.figma.com/design/Bx0W34yOOzlsdTEeWw99Pa/CTL_public?node-id=0-1&p=f&t=Uh3SfwASq7wNGwvp-0)

## Overview

**A tennis line-judging project designed to help players review whether a ball landed inside or outside the court line.**

In amateur tennis games, line calls are often judged by players themselves. However, it is difficult to make accurate decisions in fast rallies, and disagreements can occur easily.
This project solves that problem by combining:

- mobile camera recording 📷
- marker-based court calibration 👟
- AI-based ball tracking 🎾
- server-side IN / OUT judgment ⛳️
- replayable judgment clip storage 💼


<img width="1326" height="851" alt="스크린샷 2026-06-22 오후 6 32 08" src="https://github.com/user-attachments/assets/d6155fe9-2359-4be8-8cd0-0a811624035e" />
<img width="897" height="432" alt="스크린샷 2026-06-22 오후 6 32 24" src="https://github.com/user-attachments/assets/29e99abc-d2e6-457c-9b72-206e94826459" />

<img width="1230" height="226" alt="스크린샷 2026-06-22 오후 6 32 54" src="https://github.com/user-attachments/assets/dcfd04c6-5b7a-4ce9-b486-eb7ff897fad3" />


## Key Features

### Mobile-based Line Judging

Users can start a match directly from the mobile app.

- start match
- check usage guide
- place marker
- rotate phone to landscape mode
- start camera-based judgment flow

---

### Marker-based Court Calibration

The system uses markers to detect and calibrate the tennis court line.

Markers help the backend understand:

- court perspective
- line position
- camera viewpoint
- judgment reference coordinates

The app does not proceed until marker and court line detection succeed.

---

### Judgment Button

During a match, users press the judgment button when they want to check a line call.

The system analyzes the video around the pressed moment.

## Tech Stack
### Front-end 

![flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### Back-end
![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571.svg?style=for-the-badge&logo=fastapi)

### Model
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge&logo=yolo&logoColor=white) 




