## A3: Reflection

TBA - after group sharings

## B4: Reflection

Based on our conceptual system map, the **Data Processing/Input Pipeline** and the **Safety Checks** component had the most critical failure points.

1. **Data Processing pipeline:** Had the risks of misinterpreting mixed viewing contents or treating a single “one-off” query as the user’s permanent interest, which may expand the recommendations for sensitive or unwanted topics, affecting reliability and robustness.
2. **Safety checks layer:** Suffered from misclassification distinguishing between awareness/educational danger warning videos and content that actually promoted dangerous trends, resulting in safety risks.

This reflects that AI engineering should also focus on the engineering system around the model rather than relying solely on the model’s capabilities. They can focus on:

1. **Safety & Alignment Guardrails:** Deploying the input/output guardrails at the Application layer to filter the contents.
2. **Multi-Dimensional Quality Trade-Offs:** Optimising feature pipelines to understand short-term search signals to balance safety, fairness and relevance so one-off queries don’t affect user feeds.
