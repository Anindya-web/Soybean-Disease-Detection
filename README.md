# Soybean-Disease-Detection
This is the github repo for UAV-Based Soybean Disease Detection for UAV-Based Soybean Disease Detection . It includes the full model architecture, training configurations etc. for use across 3 types of Soybean Disease including Soybean Rust, Soybean Mosaic  & Soybean Semilooper Pest Attack.

```
Soy_Plant_Final_files/
├── CODE/
│   ├── 01 FPN-RF-soybean.ipynb                          # Proposed FPN + Random Forest model
│   ├── 02 FPN-SVM-soybean.ipynb                         # Proposed FPN + Support Vector Machine model
│   ├── 03 FPN-Xgboost-soybean.ipynb                     # Proposed FPN + XGBoost model
│   ├── 04 FPN-XAI.ipynb                                # Explainable AI analysis (Grad-CAM, Grad-CAM++, LRP)
│   ├── 05 ablation-only-C3-L-soybean.ipynb             # Ablation study using only C3 features
│   ├── 06 ablation-only-C4-soybean.ipynb               # Ablation study using only C4 features
│   ├── 07 ablation-only-C5-L-soybean.ipynb             # Ablation study using only C5 features
│   ├── 08 ablation-only-RF-soybean.ipynb               # Random Forest without FPN features
│   ├── 09 ablation-only-SVM-soybean.ipynb              # Support Vector Machine without FPN features
│   ├── 10 ablation-only-XGBoost-soybean.ipynb          # XGBoost without FPN features
│   ├── 11 ablation-study-(C3+C4)-L.ipynb               # Combined C3 + C4 feature ablation
│   ├── 12 ablation-study-(C3+C5)-L.ipynb               # Combined C3 + C5 feature ablation
│   ├── 13 ablation-study-(C4+C5)-L.ipynb               # Combined C4 + C5 feature ablation
│   ├── 14 DenseNet201-Indian-UAV.ipynb                 # DenseNet201 baseline on Indian UAV dataset
│   ├── 15 EfficientNet-B0-Indian-UAV.ipynb             # EfficientNet-B0 baseline on Indian UAV dataset
│   ├── 16 EfficientNet-B7-Indian-UAV.ipynb             # EfficientNet-B7 baseline on Indian UAV dataset
│   ├── 17 ResNet50-Indian-UAV.ipynb                    # ResNet50 baseline on Indian UAV dataset
│   ├── 18 ResNet101-Indian-UAV.ipynb                   # ResNet101 baseline on Indian UAV dataset
│   ├── 19 VGG16-Indian-UAV.ipynb                       # VGG16 baseline on Indian UAV dataset
│   ├── 20 VGG19-Soybean-Indian-UAV.ipynb               # VGG19 baseline on Indian UAV dataset
│   ├── 21 FPN-RF-10C-CrossV.ipynb                      # 10-fold cross-validation on Dataset-1
│   ├── 22 FPN-RF-Soybean-3-Class.ipynb                 # Three-class soybean disease classification
│   ├── 23 FPN-RF-Soybean-UAV-Cross-Validation.ipynb    # Cross-validation on the primary soybean UAV dataset
│   └── 24 MFLOPS-Inference-Time-Indian-UAV.ipynb       # Model complexity, FLOPs and inference time analysis
│
└── Figures_png/
    ├── Fig-1.png                # Figure 1: Real time crop health monitoring by UAV
    ├── Fig-2.png                # Figure 2: Healthy Soybean (a) & Soybean Rust (b) ; Soybean Mosaic (c) & Soybean Semilooper Pest Attack (d)
    ├── Fig-3.png                # Figure 3: End-to-End System for Soybean Leaf Disease Assessment
    ├── Fig-4.png                # Figure 4: Distribution of Soybean Samples by Health Condition and Disease Type
    ├── Fig-5.png                # Figure 5: Random Forest
    ├── Fig-6.png                # Figure 6: Support Vector Mechanism
    ├── Fig-7.png                # Figure 7: Extreme Gradient Boosting
    ├── Fig-8.png                # Figure 8: Feature Pyramid Network (FPN)
    ├── Fig-9.png                # Figure 9: The Proposed FPN-RF Model
    ├── Fig-10.png               # Figure 10: Confusion Matrix OF FPN-RF
    ├── Fig-11.png               # Figure 11: Confusion Matrix OF FPN-SVM
    ├── Fig-12.png               # Figure 12: Confusion Matrix OF FPN-XGBOOST
    ├── Fig-13.png               # Figure 13: ROC AUC Curve OF FPN-RF
    ├── Fig-14.png               # Figure 14: ROC AUC Curve OF FPN-SVM
    ├── Fig-15.png               # Figure 15: ROC AUC Curve OF FPN-XGBoost
    ├── Fig-16.png               # Figure 16: Grad-CAM result of FPN-RF
    ├── Fig-17.png               # Figure 17: Grad-CAM++ result of FPN-RF
    └── Fig-18.png               # Figure 18: LRP Result of FPN-RF
```
