# Image-Embeddings-with-Voxel51
A session from the AI Summer of code hosted by Zion 

Harpreet Sahota 🥑 led us through an in-depth, hands-on session focused on extracting more value from embeddings, with a special emphasis on images. He introduced us to various embedding techniques using Voxel51, a powerful tool that enhances the way we visualize and analyze data and models.

Voxel51: Visualization and Analysis
Harpreet demonstrated live how to leverage Voxel51’s capabilities to visualize embeddings and gain deeper insights into datasets. Voxel51 provides robust visualization features that allow you to create low-dimensional representations of the samples and objects in your datasets. This makes it easier to explore relationships and patterns that might not be immediately obvious.

We then moved on to hands-on session performimg different tasks using fiftyone

- Similarity Search: We used Voxel51 to perform similarity searches, comparing model representations and conducting reverse image searches. This demonstrated how effectively embeddings can be used to find images with similar content.
 
- Document Search on Images: We performed a document search on images, specifically using the cover pages from the cvpr_papers_250_samples dataset. The process involved sorting by text similarity, where the plugin automatically identified images with similar keywords. This was achieved by running an OCR engine, creating a semantic document index, and then searching semantically for documents containing our target keywords.

- Crossmodal Search: Harpreet also introduced us to crossmodal embeddings, which allow for searching images based on a given audio clip. This opened up new possibilities for linking different types of media through shared semantic content.

- Concept Space Traversal: This technique enables the exploration of conceptual relationships within an embedding space, allowing us to move through different conceptually related images and understand how they are connected in the model’s representation.
