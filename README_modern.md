# Updated Face Mask Detection for Latest Python/Libraries

## Compatibility
Updated for **Python 3.11+** (TF not yet supporting 3.14 officially). Uses latest TensorFlow 2.15+, OpenCV 4.10+, etc.

## Setup
1. **Use Python 3.11** (download from python.org if needed).
2. `python -m venv venv311`
3. `venv311\\Scripts\\activate.bat`
4. `pip install --upgrade pip`
5. `pip install -r requirements_py311.txt`
6. Test training: `python train_mask_detector.py` (generates new `mask_detector.keras`, press Ctrl+C after 1 epoch to test)
7. Test inference: `python detect_mask_video.py` (loads `mask_detector.keras` - modern format)

Legacy model backed up as `mask_detector_legacy.model`.

Pylance errors ignore - resolve after pip install in venv.

Project now runs on latest libs where supported!
