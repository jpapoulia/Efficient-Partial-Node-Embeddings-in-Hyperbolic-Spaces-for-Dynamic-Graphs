# Efficient-Partial-Node-Embeddings-in-Hyperbolic-Spaces-for-Dynamic-Graphs


This repository accompanies my Master’s thesis in the MSc program Data Science and Machine Learning at NTUA, titled Efficient Partial Node Embeddings in Hyperbolic Spaces for Dynamic Graphs.

Description

Dynamic graphs model real-world systems such as social networks or recommender systems, where the topology evolves over time. Existing hyperbolic embedding methods, such as HyperMap and Mercator, require a complete re-embedding of all nodes after each structural change. This process is computationally expensive and impractical for real-time applications.

This work proposes the Local Hyperbolic Re-embedding (LHR) method, which selectively updates only a strategically chosen subset of nodes S that are directly affected by the insertion of new nodes. The rest of the embedding remains unchanged, drastically reducing computational overhead.

Results

The LHR method reduced computation time by up to 90% compared to full re-embedding.

It maintained high geometric accuracy (cosine similarity & hyperbolic distances).

On real-world datasets (Arena-Jazz, Facebook network), it achieved particularly strong performance, especially with HyperMap.

Machine learning and graph analysis techniques were used to determine the subset of nodes S, enabling efficient local updates of the embeddings. This approach significantly reduced computational costs while preserving high accuracy, making it a practical solution for dynamic graphs in real-time scenarios.

The generalizability of the LHR framework opens new possibilities for applications in social networks, recommender systems, and dynamic information graphs.

