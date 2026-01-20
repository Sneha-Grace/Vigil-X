# Vigil-X: A Transparent NFC Security

Vigil-X is an AI-powered security API designed for financial institutions. It secures NFC Tap-to-Pay transactions against sophisticated modern threats while using Explainable AI (XAI) to restore user trust through transparent communication.

Developed for the IEEE WIE Big Idea Pitch Competition Finals (2025).

THE PROBLEM:

Contactless payments are the global standard, but they face a dual-crisis:
- The Fraud Front: Advanced AI-driven threats like Relay Attacks, Deepfake Identities, and Synthetic Fraud are bypassing traditional security.
- The Trust Front: Current "Black Box" security systems often block legitimate transactions without explanation. These False Positives cost merchants nearly $118 Billion annually—a financial loss six times higher than the actual fraud they intend to stop.

THE SOLUTION: Shield & Compass

Vigil-X is not a standalone app; it is a B2B API that plugs into existing banking infrastructures to provide:

- The Shield (Proactive Defense): Uses Machine Learning and Generative Adversarial Networks (GANs) to simulate and neutralize evolving fraud patterns, including GPS-verified "Impossible Travel" scenarios.

- The Compass (Transparent Guidance): Powered by Explainable AI (XAI), it translates complex algorithmic decisions into clear, human-readable alerts. Instead of a "Declined" message, users receive a specific reason (e.g., "New Device detected in Delhi") and the power to verify the transaction instantly.

PROPOSED TECH STACK
Vigil-X is built on a foundation of scalable, open-source, and industry-standard technologies:

- Core Logic: Python 
- Artificial Intelligence: TensorFlow / PyTorch: For deep learning and behavioral analysis.
- Scikit-learn: For anomaly detection (Isolation Forests, LSTMs).
- Generative AI: GANs for synthetic fraud data generation.
- Explainability (XAI): SHAP (SHapley Additive exPlanations): For feature importance.
- LIME: For local interpretable model-agnostic explanations.
- Backend & API: FastAPI / Flask: For high-performance, low-latency API responses.
- Docker: For containerization and easy bank-side integration.
- Data Verification: Google Maps Platform API (for real-time GPS signal cross-referencing).

IMPLEMENTATION ROADMAP

Vigil-X is designed with a feasible 4-phase growth strategy:
- Phase 1: Research, data sourcing (Kaggle/Public Datasets), and protocol analysis.
- Phase 2: Training the 'Shield' (Fraud models) and building the 'Compass' (XAI translation layer).
- Phase 3: MVP development of the API and user interface mock-ups.
- Phase 4: Pilot testing with a partner financial institution and backtesting on historical data.

EXPECTED OUTCOMES

- For Users: Reduction in payment anxiety and a 50% decrease in frustrating false declines.
- For Banks: Lower fraud-related losses and a significant increase in customer Net Promoter Score (NPS).
- For the Ecosystem: A new ethical standard for AI transparency in fintech.
