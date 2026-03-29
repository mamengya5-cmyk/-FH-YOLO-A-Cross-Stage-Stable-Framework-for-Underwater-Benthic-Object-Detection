# FH-YOLO: Underwater Benthic Object Detection Framework (Under Review)

This is the core implementation code for our paper **"FH-YOLO: A Cross-Stage Stable Framework for Underwater Benthic Object Detection"**, which is currently under review.

---

## Code Availability

Due to review requirements, only the core code implementing our key innovations is publicly available in this repository.
**The full code will be open-sourced after the paper is accepted.**

If you need the complete code to reproduce our results, please contact the author via:
📧 **mmy20040219@outlook.com**

---

## Dataset Availability

The self-built Underwater Benthic Dataset (UBD) used in this paper is not fully public at this moment.
We have uploaded **15 representative sample images** and the class name file `names.txt` in `demo/sample_data/` to demonstrate the data format and underwater environmental characteristics.

**The full dataset will be open-sourced synchronously after the paper is accepted.** If you need access to the complete dataset for review purposes, please contact us via the email above.

---

## Usage Examples

- Training: `python demo/step1_start_train.py`
- Inference/Tracking: `python demo/step3_start_window_track.py`
