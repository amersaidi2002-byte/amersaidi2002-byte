# Amer Saidi

### Machine Learning & Computer Vision Engineer
**Deep Learning · Signal Processing · NLP & LLMs · Embedded AI**

I build machine learning systems for images, signals and language, from data
preparation and model training to evaluation, optimization and deployment.

My skills cover **computer vision, signal and image processing, NLP and LLM
fine-tuning**, with **Python, C++ and PyTorch**. I combine mathematical modeling
and numerical optimization with practical software engineering to develop
reproducible ML pipelines and efficient inference applications.

I work across **model development and embedded deployment**, including ONNX
inference, ROS 2 perception pipelines and hardware implementation with FPGA
and RISC-V.

**Open to engineering opportunities in France** in applied machine learning,
computer vision, signal processing, NLP and embedded AI.

## Skills

| Area | Skills & technologies |
|---|---|
| Machine learning & deep learning | Supervised and unsupervised learning, neural networks, model training and evaluation, PyTorch, scikit-learn |
| Computer vision | Image classification, object detection, anomaly detection, image preprocessing, OpenCV |
| Signal & image processing | Spectral analysis, hyperspectral unmixing, matrix factorization, constrained optimization, NumPy, SciPy |
| NLP & LLMs | Sequence modeling, RNNs, GRUs, Transformers, Hugging Face, language model fine-tuning, SFT, DPO |
| Inference & deployment | Python, C++, ONNX Runtime, ROS 2, GStreamer, Docker, Linux |
| Embedded systems & hardware | C, Raspberry Pi, FPGA, VHDL, RISC-V |

## Selected projects

### [Visual Defect Inspection](https://github.com/amersaidi2002-byte/visual-defect-inspection)

Detect and localize anomalies in industrial images using normal training examples.
Compare a convolutional autoencoder with a compact PatchCore variant on three
MVTec AD categories.

- Fitted models, a local inspection app and per-image predictions.
- Evaluation of image/pixel AUROC, defect recall, false alarms and CPU latency.
- Recorded experiment settings, data checksums and tests.

[View the project](https://github.com/amersaidi2002-byte/visual-defect-inspection)
· [Read the experiment](https://github.com/amersaidi2002-byte/visual-defect-inspection/blob/main/docs/experiment.md)

[![Visual defect inspection examples](https://raw.githubusercontent.com/amersaidi2002-byte/visual-defect-inspection/main/docs/assets/inspection-demo.gif)](https://github.com/amersaidi2002-byte/visual-defect-inspection)

### [Hyperspectral Unmixing](https://github.com/amersaidi2002-byte/hyperspectral-unmixing)

Estimate material spectra and their fractions in hyperspectral images using
**SPA + FCLS, Simplex NMF and Spatial NMF**.

- 112 measured fits across real benchmark scenes and controlled synthetic mixtures.
- Compare spectral angles, abundance errors and reconstruction residuals.
- A local pixel inspector, an executed notebook and saved numerical results.

[View the project](https://github.com/amersaidi2002-byte/hyperspectral-unmixing)
· [Read the experiment](https://github.com/amersaidi2002-byte/hyperspectral-unmixing/blob/main/docs/experiment.md)

[![Hyperspectral image, material fractions and pixel spectrum](https://raw.githubusercontent.com/amersaidi2002-byte/hyperspectral-unmixing/main/docs/assets/overview.png)](https://github.com/amersaidi2002-byte/hyperspectral-unmixing)

### [Embedded Digit Recognition](https://github.com/amersaidi2002-byte/projet_mnist)

Connect **PyTorch training** with **handwritten C++ inference** for MLP and CNN
digit classifiers targeting Raspberry Pi.

- Implement neural network forward passes without a deep learning runtime.
- Integrate OpenCV preprocessing with a GStreamer video pipeline.
- Compare model behavior through training notebooks and a project report.

[View the project](https://github.com/amersaidi2002-byte/projet_mnist)
· [Read the report](https://github.com/amersaidi2002-byte/projet_mnist/blob/main/CR_IA_embarque.pdf)
