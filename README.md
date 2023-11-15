# Artificial Intelligence (AI) Bill of Materials (BOM) aka AI BOM
What is an AI BOM?
Much like a traditional Bill of Materials in manufacturing that lists out all the parts and components of a product, an AI BOM provides a detailed inventory of all components of an AI system. But, what about Software Bill of Materials (SBOMs)? How are they different from AI BOMs? In the case of SBOMs, they are used to document the components of a software application. However, AI BOMs are used to document the components of an AI system, including the model details, architecture, usage, training data, and more.

Ezi Ozoani, Marissa Gerchick, and Margaret Mitchell introduced the concept of AI Model Cards in [a blog post in 2022](https://huggingface.co/blog/model-cards). Since then, AI BOMs continue to evolve. Manifest (a supply chain security company) also introduced an AI BOM concept that is being suggested to be included in OWASP’s CycloneDX and the Linux Foundation also created a project to standardize AI BOMs.

I created a proposed [JSON schema](schema.json) for the AI BOM elements that Manifest introduced. This JSON schema describes the structure of an AI BOM document and defines which fields are required and which are optional, as well as the expected data types for each field. You can use this schema to validate any AI BOM documents to ensure they meet the specification outlined. The concept of AI BOMs is defined in the following academic paper:
*Santos, O. (2023). Toward Trustworthy AI: An Analysis of Artificial Intelligence (AI) Bill of Materials (AI BOMs). Retrieved from https://dx.doi.org/10.13140/RG.2.2.18893.61929*

A visual representation of the AI BOM schema can be generated using the A visual representation of the AI BOM schema can be generated using the [AI BOM Visualizer Tool](https://aibomviz.aisecurityresearch.org/).
