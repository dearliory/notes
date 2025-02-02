# DeepSeek Demyth: A Simple Explanation for Everyone (Even My Grandma)

DeepSeek is a powerful Large Language Model (LLM) that can answer questions and provide explanations on a wide range of topics. Recently, it has gained significant attention for its state-of-the-art (SOTA) performance, while only at a fraction of the computational cost of traditional models. What makes DeepSeek particularly exciting is that it is open-source, meaning anyone can use it for free, with no barriers to access.

## What is DeepSeek’s Architecture?

DeepSeek is built on established architectures like the Transformer and integrates innovations such as Mixture of Experts (MoE), originally introduced by Google. However, DeepSeek goes a step further by optimizing its design to reduce computational costs. These enhancements include leveraging sparsely activated model components and utilizing lower-precision training parameters, making the model more efficient while maintaining high performance.

Thanks to these innovations, training DeepSeek costs less than $6 million—only a fraction of what is typically required for other cutting-edge models. This cost efficiency marks a major breakthrough in AI, challenging the previous belief that scaling laws necessitate an exponential increase in computational resources.

## How does Deepseek model trains?

DeepSeek, like other AI models, reads on its own by processing vast amounts of text. This is similar to how a student learns from books, newspapers, and articles to gain knowledge. It predicts the next word based on context, improving its language skills over time. With additional guidance, it can answer questions, write, and perform various tasks—all built on a deep understanding of human language. 

## What Does DeepSeek Look Like?

You may have heard of various versions of DeepSeek, such as V1, V2, and V3. The latest, DeepSeek V3, boasts an impressive 671 billion parameters. For comparison, the human brain has about 80 billion neurons. Just like only a portion of the human brain is active at any given time, V3 uses only a fraction of its parameters—around 37 billion, or 5% of its full capacity—during each computation. Despite using only a small part of its potential, DeepSeek’s computational power far surpasses the human brain in certain areas, especially when it comes to processing massive datasets and performing complex calculations. V3 has analyzed nearly all the books and data humanity has accumulated, a feat well beyond the capabilities of any individual mind.

Additionally, there is the R1 model. R1 shares the same architecture as V3 but has been specially trained to simulate a "thought process" before responding. This makes it appear as if it’s reflecting or thinking, much like a human pausing to contemplate before answering. It’s the combination of V3 and R1, not the baseline V3 alone, that has generated the most excitement in the AI community. DeepSeek R1 is the first open-source model to perform at a level comparable to commercial state-of-the-art models, marking a significant milestone in AI. Its ability to "think" before responding is one of the key features that sets it apart.

## What Does It Take to Run DeepSeek Locally?

Running the DeepSeek V3 model requires significant computational power. The default configuration demands around 670GB of memory, far exceeding the capacity of most personal computers. For comparison, typical home computers have only 16GB of memory, making it impractical to run the full V3 model on such systems. To make DeepSeek more accessible, a teacher-student approach has been implemented. In this method, smaller models are trained to learn from the larger, more powerful models. These smaller models, starting at 1 billion parameters, can be run on more limited hardware, providing greater accessibility.

##  Is DeepSeek Better than SOTA?

Not necessarily. While it may not outperform the best models in every area, DeepSeek matches their performance at a much lower cost and is available as open-source. It excels in science and math but isn't as strong when it comes to writing and coding.

## What Can We Learn from DeepSeek's Latest Updates?
- **Training Large Models is Expensive**: While it cost about $5 million to train DeepSeek, this doesn’t include the additional costs from experiments and trial-and-error. Also its cost is based on the GPU renting price in China, but that price is several times higher in other countries. So, the real cost of developing a model like DeepSeek could be much higher.
- **Scaling Laws Still Apply**: Bigger models tend to perform better, but they also need more computing power. So, as we make models larger, they get more capable but also more costly to run.
- **Open Source and Community Support**: DeepSeek’s open-source code places it on the right side of history, gaining strong support and acceptance from the community. This is a big win for the open-source movement, fostering collaboration and innovation.
