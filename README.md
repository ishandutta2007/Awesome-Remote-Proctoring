# Awesome-Remote-Proctoring

## Top Remote Proctoring Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Online Exam Integrity, AI Monitoring, Live Proctoring, Browser Lockdown & Identity Verification*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Remote Proctoring**. These systems help institutions and organizations conduct secure online exams by monitoring candidates via webcam, screen, audio, and AI-driven behavior analysis, often combined with browser lockdown and identity verification.



**Examples** include Proctorio, Honorlock, ProctorU, Examity, Respondus Monitor, SMOWL, Talview, Mercer Mettl Proctoring, Inspera Proctoring, and ProctorExam (the category leaders).



**Open-source emphasis**: Mature, production-grade remote proctoring platforms are almost entirely commercial due to privacy, security, scalability, and liability requirements. Useful open options are limited to experimental projects, browser lockdown tools, and academic prototypes. This section lists the strongest available open resources and is realistic about the significant gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Proctorio](https://proctorio.com/)**  

  Fully automated AI-driven remote proctoring platform focused on scalable behavioral and screen monitoring with strong privacy controls.



- **[Honorlock](https://honorlock.com/)**  

  Hybrid proctoring solution combining AI detection with on-demand live human proctors, popular in higher education.



- **[ProctorU (Meazure Learning)](https://www.meazurelearning.com/)**  

  Live human proctoring platform with AI support, widely used for high-stakes exams requiring human oversight.



- **[Examity](https://www.examity.com/)**  

  Configurable auto and live proctoring platform offering flexible levels of monitoring and review for academic and certification exams.



- **[Respondus Monitor](https://web.respondus.com/)**  

  Automated proctoring tool that works with Respondus LockDown Browser for recorded exam sessions and AI review.



- **[SMOWL](https://smowl.net/)**  

  AI-based remote proctoring platform focused on continuous monitoring and behavioral analysis for online assessments.



- **[Talview](https://www.talview.com/)**  

  AI proctoring and assessment platform that also supports broader talent evaluation and interviewing use cases.



- **[Mercer Mettl Proctoring](https://mettl.com/)**  

  Enterprise proctoring solution with AI and live options, integrated into Mercer Mettl’s assessment platform.



- **[Inspera Proctoring](https://www.inspera.com/)**  

  Proctoring capabilities within the Inspera assessment platform, designed for secure digital exams.



- **[ProctorExam](https://proctorexam.com/)**  

  Remote proctoring service offering automated and live monitoring options for educational and professional testing.



## Open-Source GitHub Projects

- **[OpenProctor](https://github.com/kamlendras/OpenProctor)**  

  Open-source online proctoring software built with Next.js — real-time monitoring and a secure exam environment. Early-stage and customizable.



- **[ExamSecure](https://github.com/rajrajhans/examsecure)**  

  Academic open-source project for remote exams featuring browser lockdown, face detection, multiple-person detection, and impersonation checks.



- **[AI-based remote exam proctoring prototypes](https://github.com/)**  

  Community and university projects using face recognition, anti-spoofing, head-pose estimation, and object detection (YOLO, face-api.js, etc.).



- **[Safe Exam Browser (SEB)](https://safeexambrowser.org/)**  

  Open-source secure browser that locks down the exam environment (kiosk mode, restricted applications). Often paired with commercial or custom proctoring.



- **[WebRTC-based monitoring experiments](https://github.com/)**  

  Open projects that stream candidate webcam/screen feeds for manual or semi-automated proctor review.



- **[Face detection and behavior analysis libraries](https://github.com/)**  

  OpenCV, MediaPipe, face-api.js, and related tools used as building blocks for custom proctoring logic.



- **[Browser lockdown and kiosk open solutions](https://github.com/)**  

  Tools and configurations that restrict browser functionality during assessments (complementary to full proctoring).



- **[Academic remote exam frameworks](https://github.com/)**  

  University research projects exploring privacy-preserving or lightweight remote monitoring approaches.



- **[Custom LMS proctoring plugins](https://github.com/)**  

  Open plugins or extensions for Moodle, Open edX, and similar platforms that add basic camera or activity checks.



- **[Privacy-focused monitoring research tools](https://github.com/)**  

  Experimental systems that attempt on-device analysis or minimized data collection for exam integrity.



### Additional Strong Open-Source Options

- Using **Safe Exam Browser** as a free lockdown layer in combination with any assessment platform.

- Building lightweight monitoring with open computer-vision libraries for low-stakes or internal assessments.

- Exploring academic prototypes (OpenProctor, ExamSecure, and similar) for research or highly customized needs.

- Accepting that scalable AI detection, live human proctor networks, robust identity verification, legal defensibility, and large-scale recording/review workflows still require commercial platforms.

- Focusing open efforts on browser security and basic activity logging rather than full AI proctoring replacement.



**Frameworks for building custom systems**: Secure browser (Safe Exam Browser or equivalent) → webcam/screen capture via WebRTC → open face/object detection models → rule-based or simple ML flagging → human review dashboard. This can work for low-to-medium stakes or research settings. Commercial platforms (Proctorio, Honorlock, ProctorU, Examity, Respondus Monitor, Talview, Mercer Mettl, etc.) remain the practical choice for high-stakes, high-volume, or regulated exams that demand proven integrity, support, and auditability.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Remote proctoring involves continuous collection of biometric and behavioral data (video, audio, screen). Strict privacy, consent, data-protection (GDPR, etc.), and accessibility requirements apply. Open-source or self-built solutions carry significant legal, ethical, and technical risk if used for high-stakes assessments. Always involve legal, privacy, and academic integrity stakeholders. This list is not legal, educational policy, or compliance advice.



---

**Made for academic institutions, certification bodies, and assessment teams who need trustworthy online exam integrity.**

Let's keep remote assessment secure, fair, and as transparent as the stakes allow.
