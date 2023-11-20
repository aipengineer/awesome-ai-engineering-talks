# LLMOps: An Evaluation Perspective

*By Ryan McConville, Machine Learning Engineer from Weights & Biases*

## TLDR:

- Evaluating large language models (LLMs) is more challenging than traditional ML models.
- Standard metrics like loss may not be sufficient; actual outputs need examination.
- LLMs are often chains of models, requiring multidimensional evaluation.
- Qualitative debugging and tailored quantitative metrics are critical.
- Benchmark tasks may not reflect real-world performance.
- Human evaluation of test sets is ideal but expensive.
- User testing and iteration are crucial for improving quality.
- Treat LLM evaluation like software debugging.
- As LLMs deploy more, proper evaluation tools/practices are essential for reliability and transparency.

## Understanding Large Language Models (LLMs)

Ryan from Weights & Biases introduced the significance of LLMs, emphasizing their ability to process diverse data types beyond text, including tokenized information like words and images. This versatility, showcased by large multimodal models, has revolutionized industries, especially in areas like biomedical applications.

## Challenges in LLM Operationalization

Distinguishing between Machine Learning Operations (MLOps) and LLMOps, the speaker highlighted challenges in deploying LLMs due to the vast, untrained space they encounter. Different from traditional ML models, training LLMs from scratch is less common, with a focus on fine-tuning or using pre-trained models. This shift introduces new complexities, particularly in evaluation.

## Evolution of LLM User Personas

Ryan discussed three main personas in the LLM space: LLM Creators (training LLMs from scratch), Fine Tuners (utilizing pre-trained models), and Users of LLMs (app developers or API users). This diverse landscape requires tailored approaches for evaluation and deployment.

## Evaluation Strategies for LLMs

The talk emphasized the importance of comprehensive evaluation beyond standard metrics. Ryan advocated for a debugger-like approach, examining the outputs of the model at different checkpoints. Tools such as Weights and Biases dashboards were recommended for effective evaluation, focusing on outputs, loss, accuracy, and real-world applicability.

## Challenges in LLM Evaluation

Ryan acknowledged the challenges in evaluating LLMs, especially given the secretive nature of training distributions. The lack of information on the distribution between training and production data poses a unique challenge compared to traditional ML models. The need for new tools to handle the generative nature of LLMs was emphasized.

## Scalable User Testing for LLMs

In response to a question about user testing, Ryan highlighted the importance of scalability, feasibility, and effectiveness in obtaining user feedback. Drawing parallels with A/B testing, the speaker recommended sampling users, conducting focus groups, and utilizing standard testing practices to gather valuable insights.

## Application of LLMs in Traditional Problems

In response to a question about applying LLMs to classical problems like clustering, Ryan suggested that while LLMs can be used for various tasks, they may not consistently outperform traditional methods. However, experimentation is encouraged, especially with Transformers, as they serve as a fundamental building block for LLMs.

## Conclusion and Key Takeaways

The talk concluded by emphasizing the ongoing evolution of LLMs and their applications. The importance of user feedback, comprehensive evaluation, and the need for a debugger-like approach were highlighted as crucial aspects of navigating the complex landscape of LLMs. The session provided valuable insights into the challenges and opportunities within Large Language Models.
