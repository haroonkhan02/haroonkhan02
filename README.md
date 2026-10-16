# Hi, I'm Haroon Khan 👋

### AI / Machine Learning Engineer | Computer Vision | Deep Learning | LLMs & Agentic AI

M.Sc. Computer Vision & Robotics (ViBOT), based in Paris. I build practical AI systems,
from research and experimentation through to deployment, and I care about measuring them
honestly: held-out test sets, baselines, and a clear note on where each one fails.

### Portfolio

Each project is its own repo with tests, CI, a reproducible pipeline and a results section.

| Project | What it does | Headline result |
|---|---|---|
| [clinic-voice-agent](https://github.com/haroonkhan02/clinic-voice-agent) | AI phone receptionist: Twilio + Pipecat, Deepgram STT/TTS, Claude tool use, emergency guardrails | 20/20 simulated calls handled correctly, 0.79 s median voice-to-voice |
| [multiview-3d-reconstruction-blender](https://github.com/haroonkhan02/multiview-3d-reconstruction-blender) | Photos to 3D: SfM from scratch vs COLMAP, plane-sweep MVS, Poisson mesh, Blender render | 0.2–0.9 cm median camera error on 4 of 5 ETH3D scenes |
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

Multi-object tracking · Visual odometry / SLAM · Model export (ONNX, CoreML) · Robot learning in simulation

### Contact

LinkedIn: [linkedin.com/in/haroonkhan01](https://www.linkedin.com/in/haroonkhan01)
