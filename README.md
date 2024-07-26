DARKWEB TRAFFIC ANALYSIS USING MACHINE LEARNING TECHNIQUE
Developed a Hierarchical Classification System:
Designed and implemented a three-layer hierarchical classifier to distinguish between four types of darknet (Tor, I2P, ZeroNet, Freenet) and 25 specific user behaviors.
Achieved 96.9% accuracy in classifying darknet types and 91.6% average accuracy in identifying user behaviors.
Data Collection and Labeling:

Deployed traffic collection probes in real darknet environments to capture and label 8 types of user behavior traffic, including browsing, chat, email, audio streaming, video streaming, file transfer, P2P, and VoIP.
Published the anonymized dataset on the web for public use, contributing to the research community.
Feature Extraction and Analysis:

Extracted 26 time-based flow features from the captured darknet traffic to represent its characteristics.
Utilized CICFlowMeter for feature extraction to convert continuous packet data into discrete feature vectors.
Algorithm Evaluation and Selection:

Evaluated six machine learning algorithms (Logistic Regression, Decision Tree, Random Forest, GBDT, XGBoost, LightGBM) and two deep learning algorithms (MLP, LSTM) for the local classifiers in the hierarchical model.
Determined XGBoost as the best-performing algorithm for this darknet traffic classification scenario.
Performance Improvement:

Enhanced classification accuracy by using a hierarchical classification approach compared to flat classifiers.
Demonstrated the hierarchical classifier's superiority in handling scenarios with a large number of classification categories.
Contribution to Research Community:

Addressed the challenge of the lack of public darknet datasets by creating and sharing a comprehensive dataset.
Provided a detailed methodology and results, contributing valuable insights into the field of darknet traffic classification and user behavior analysis.
