# Soybean-Disease-Detection
This is the github repo for UAV-Based Soybean Disease Detection for UAV-Based Soybean Disease Detection . It includes the full model architecture, training configurations etc. for use across 3 types of Soybean Disease including Soybean Rust, Soybean Mosaic  & Soybean Semilooper Pest Attack.

```
Soy_Plant_Final_files/
├── CODE/
│   ├── 01 FPN-RF-soybean.ipynb                         # 01 FPN-RF-soybean: FPN with RF
│   ├── 02 FPN-SVM-soybean.ipynb                        # 02 FPN-SVM-soybean: FPN with SVM
│   ├── 03 FPN-Xgboost-soybean.ipynb                    # 03 FPN-Xgboost-soybean: FPN with XGboost
│   ├── 04 FPN-XAI.ipynb                                # 04 FPN-XAI: Explainable AI analysis (Grad-CAM, Grad-CAM++, LRP)
│   ├── 05 ablation-only-C3-L-soybean.ipynb             # 05 ablation-only-C3 L-soybean: Ablation study using only C3 Layer
│   ├── 06 ablation-only-C4-soybean.ipynb               # 06 ablation-only-c4-soybean: Ablation study using only C4 Layer
│   ├── 07 ablation-only-C5-L-soybean.ipynb             # 07 ablation-only-C5 L-soybean: Ablation study using only C5 Layer
│   ├── 08 ablation-only-RF-soybean.ipynb               # 08 ablation-only-RF-soybean: Random Forest without FPN Layer
│   ├── 09 ablation-only-SVM-soybean.ipynb              # 09 ablation-only-SVM-soybean: Support Vector Machine without FPN Layer
│   ├── 10 ablation-only-XGBoost-soybean.ipynb          # 10 ablation-only-XGBoost-soybean: XGBoost without FPN Layer
│   ├── 11 ablation-study-(C3+C4)-L.ipynb               # 11 ablation-study-(c3+c4)-L: Combined C3 + C4 Layer
│   ├── 12 ablation-study-(C3+C5)-L.ipynb               # 12 ablation-study-(C3+C5)L: Combined C3 + C5 Layer
│   ├── 13 ablation-study-(C4+C5)-L.ipynb               # 13 ablation-study-(c4+c5)-L: Combined C4 + C5 Layer
│   ├── 14 DenseNet201-Indian-UAV.ipynb                 # 14 densenet201-indian-uav: DenseNet201 baseline on Indian UAV dataset
│   ├── 15 EfficientNet-B0-Indian-UAV.ipynb             # 15 efficientnet-b0-indian-uav: EfficientNet-B0 baseline on Indian UAV dataset
│   ├── 16 EfficientNet-B7-Indian-UAV.ipynb             # 16 efficientnetb7-indian-uav: EfficientNet-B7 baseline on Indian UAV dataset
│   ├── 17 ResNet50-Indian-UAV.ipynb                    # 17 resnet50-indian-uav: ResNet50 baseline on Indian UAV dataset
│   ├── 18 ResNet101-Indian-UAV.ipynb                   # 18 resnet-101-indian-uav: ResNet101 baseline on Indian UAV dataset
│   ├── 19 VGG16-Indian-UAV.ipynb                       # 19 vgg16-indian-uav: VGG16 baseline on Indian UAV dataset
│   ├── 20 VGG19-Soybean-Indian-UAV.ipynb               # 20 vgg19-soybean-indian-uav: VGG19 baseline on Indian UAV dataset
│   ├── 21 FPN-RF-10C-CrossV.ipynb                      # 21 FPN-RF-10C-CrossV: 10-class-cross-validation 
│   ├── 22 FPN-RF-Soybean-3-Class.ipynb                 # FPN-RF-Soybean-3-Class: Cross-validation on 3-class
│   ├── 23 FPN-RF-Soybean-UAV-Cross-Validation.ipynb    # 23 FPN-RF-Soybean-UAV-Cross-Validation: Cross-validation on indian-UAV dataset
│   └── 24 MFLOPS-Inference-Time-Indian-UAV.ipynb       # 24 MFLOPS-Inference-Time-Indian-UAV: Model complexity, FLOPs and inference time analysis
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
