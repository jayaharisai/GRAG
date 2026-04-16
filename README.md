**RAG** stands for **Retrieval-Augmented Generation**. it's techniquw used in AI (especially with large language model like ChatGPT) to improve answers by combining two things:

## 1. Retrieval
The system first searched for relevant information from an external sources, such as:
- Documents
- Databases
- Websites
- Company knowledge bases

## 2. Generation
Then, it uses that retrieved information to generate a response, instead of relying only on what the model was trained on.

### Simple way to think about it
- Without RAG: That AI answers from memory (its training data).
- with RAG: The AI looks things up first, then answers using that fresh info.

# RAG (Retrival-Augmented Generation)
At a system level RAG is a hybrade architecture that couples:
- a parametric model (LLM with fixed weights)
- a non-parametric memory (external knowledge store)
