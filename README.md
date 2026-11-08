# Hi, I'm Haroon Khan 👋

### AI / Machine Learning Engineer | Computer Vision | Deep Learning | LLMs & Agentic AI

M.Sc. Computer Vision & Robotics (ViBOT), based in Paris. I build practical AI systems,
from research and experimentation through to deployment, and I care about measuring them
honestly: held-out test sets, baselines, and a clear note on where each one fails.

### Portfolio

**Website: [haroonkhan02.github.io](https://haroonkhan02.github.io/)**, with a page per project
and five models that run in your browser.

Each project is its own repo with tests, CI, a reproducible pipeline and a results section.

| Project | What it does | Headline result |
|---|---|---|
| [robot-arm-imitation-learning](https://github.com/haroonkhan02/robot-arm-imitation-learning) | MuJoCo pick-and-place learned from demonstrations: behaviour cloning vs my own ACT, with controls | ACT 99.0 % success on unseen layouts vs 0.1 % for a plain MLP |
| [multi-object-tracking-bytetrack](https://github.com/haroonkhan02/multi-object-tracking-bytetrack) | Pedestrian tracking on MOT17: YOLO11x, own Kalman filter, SORT vs ByteTrack | HOTA 51.1 vs 48.9 for SORT, ID switches 269 vs 512 |
| [visual-odometry-slam](https://github.com/haroonkhan02/visual-odometry-slam) | RGB-D and monocular visual odometry with loop closure and pose-graph optimisation | TUM RGB-D trajectory error 1.4–8.8 cm with loop closure (4.8–19.2 cm without) |
| [clinic-voice-agent](https://github.com/haroonkhan02/clinic-voice-agent) | AI phone receptionist: Twilio + Pipecat, Deepgram STT/TTS, Claude tool use, emergency guardrails | 20/20 simulated calls handled correctly, 0.79 s median voice-to-voice |
| [multiview-3d-reconstruction-blender](https://github.com/haroonkhan02/multiview-3d-reconstruction-blender) | Photos to 3D: SfM from scratch vs COLMAP, plane-sweep MVS, Poisson mesh, Blender render | 0.21–0.85 cm median camera error on the 3 ETH3D scenes it fully registers |
| [construction-safety-lidar-vision](https://github.com/haroonkhan02/construction-safety-lidar-vision) | PPE detection with YOLO11 plus a LiDAR danger-zone monitor (RANSAC + DBSCAN) | PPE mAP@0.5 0.713; LiDAR alerts in 17/18 red-zone frames |
| [robotics-docs-rag](https://github.com/haroonkhan02/robotics-docs-rag) | RAG over the ROS 2 docs: hybrid search, reranking, cited answers, evaluation set | MRR@10 0.690 vs 0.454 for a BM25 baseline |
| [face-recognition-antispoofing](https://github.com/haroonkhan02/face-recognition-antispoofing) | Face verification and identification (ArcFace) plus anti-spoofing and liveness | LFW verification 99.55 % |
| [satellite-landuse-multispectral](https://github.com/haroonkhan02/satellite-landuse-multispectral) | Sentinel-2 land use on all 13 bands, and building change detection | EuroSAT 0.987 accuracy; LEVIR-CD change F1 0.890 |
| [polyp-segmentation-unet](https://github.com/haroonkhan02/polyp-segmentation-unet) | Colon polyp segmentation with a U-Net and MC-dropout uncertainty maps | Kvasir-SEG test Dice 0.904 |
| [lane-detection-classical-vs-deep](https://github.com/haroonkhan02/lane-detection-classical-vs-deep) | The same lane task solved with classical OpenCV and with a U-Net | TuSimple ego-lane accuracy 0.951 (deep) vs 0.773 (classical) |
| [hand-gesture-control](https://github.com/haroonkhan02/hand-gesture-control) | Touchless mouse, slides and whiteboard from real-time hand tracking | ~8 ms per frame tracking on CPU |

Some of these results come with caveats, and each README spells them out. For example,
the voice agent's emergency rules catch only 45 % of emergencies on a held-out set, and
the anti-spoofing model's test error is several times its validation error.

### Tech Stack

**Languages:** Python, SQL, C++, JavaScript

**ML/AI:** PyTorch, Scikit-learn, OpenCV, Transformers, Ultralytics YOLO, Open3D

**Generative AI:** LLMs, RAG, embeddings, vector databases, agentic workflows, voice agents

**Backend:** FastAPI, Flask, REST APIs

**MLOps/Cloud:** Docker, GitHub Actions, MLflow, AWS

### Currently Learning

Image-based robot policies · Re-identification for long occlusions in tracking · Learned safety classifiers for voice agents

### Contact

LinkedIn: [linkedin.com/in/haroonkhan01](https://www.linkedin.com/in/haroonkhan01)
