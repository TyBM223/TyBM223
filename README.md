# Ty Mullinax

Software engineer with a B.S. in Software Engineering from Auburn University. I build computer
vision and machine learning systems that run in real time, and backend services that are measured
before they're optimized. I write down why each design decision was made and what the system can't do yet.

## Projects

**[ASL sign recognition](https://github.com/TyBM223/asl-sign-recognition)**
Recognizes fingerspelled letters and 10 word signs from a webcam in real time. MediaPipe hand
and pose landmarks feed a small MLP (letters) and a bidirectional GRU (word signs), followed by
smoothing and a running transcript. About 24 ms per frame on a laptop CPU, with 59 unit tests.
`Python` `PyTorch` `MediaPipe` `OpenCV`

**[soccer-possession](https://github.com/TyBM223/soccer-possession)** *(in progress)*
Ball possession tracking for match video, built on Roboflow's open-source player and ball
detection, tracking and team classification. Adds per-frame possession calls, temporal smoothing,
and a coverage stat so a weak ball detector can't hide behind confident numbers.
`Python` `YOLOv8` `ByteTrack` `supervision`

**[RideSim](https://github.com/TyBM223/RideSim)** *(early stage)*
A driver-to-rider matching and dispatch backend, built one measured phase at a time with
architecture decision records. The foundation is done; the domain model and matching come next.
`Python` `FastAPI` `pytest` `ruff`

**[MISE](https://github.com/TyBM223/AI-Operations-Agent-for-Restaurants)**
An LLM agent for restaurant end-of-shift work. Claude calls tools that compute tip-outs and
inventory reorders, then explains the results in plain English.
`React` `Vite` `Anthropic API`

## Tools

Python, PyTorch, OpenCV, MediaPipe, Ultralytics YOLOv8, FastAPI, pytest, JavaScript, React, Git

## Contact

[LinkedIn](https://www.linkedin.com/in/ty-mullinax-b0051629a/) · [tbm0042@auburn.edu](mailto:tbm0042@auburn.edu)
