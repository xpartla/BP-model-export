## ONNX export notebook for MCI prediction
This repo is an extension of my Bachelor's thesis ([Code](https://github.com/xpartla/Bakalarka), [Paper](https://opac.crzp.sk/?fn=detailBiblioFormChildI5KAV&sid=71F69C32541FA50933677EB0024D&seo=CRZP-detail-kniha)) on predicting Mild Cognitive Impairment (MCI) within 4 years using the NACC dataset.

### Overview
End to end ML pipeline
- Data preprocessing
- Feature engineering
- Feature selection
- Tuned and optimized model

Final model - LightGBM, achieveing ~0.96 AUC score.\
Model exported to ONNX with numerical equivalent verification.\
Exported artifacts for standalone inference (schema, preprocessing metadata...).

### Additional work
[Rust inference engine](https://github.com/xpartla/BP-inference-extension) for MCI prediction

### Notes
Research-oriented project intended for experimentation, not clinical deployment.
