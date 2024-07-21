## 0. Data Preprocessing
 - [ ] Chunk Optimization
 - [ ] Embedding Model Optimization (DAPT, TAPT, etc .. )
 - [ ] Make MetaData
 - [ ] RAFT
## 1. Query Analysis (= Pre-Retriever)
 - [ ] Multi Query
 - [ ] Decomposition
 - [ ] HyDE
 - [ ] 부정어가 섞여있는 query의 경우 부정적인 쿼리를 filtering해서 가져올 수 있는지? (ex, 산은 좋고, 바다는 싫어 -> 바다에 대한 relevant docs는 걸러내야 함)
 - [ ] 자연어 query를 넣었을 때와 한국어 토크나이징을 수행한 query의 relevant docs 추출 성능비교
## 2. Query Routing (= Pre-Retriever)
 - [ ] Logical Routing
 - [ ] Semantic Routing
## 3. Retriever & Indexing
 - [ ] Lexical : BM25
 - [ ] Lexcial : BM42 (advanced)
 - [ ] Semantic : DPR
 - [ ] Semantic : PDR
 - [ ] Ensemble : Hybrid Search
 - [ ] Indexing : FAISS
 - [ ] Indexing : HNSW
 - [ ] RDB + Vector (= Docker + ParadeDB)
## 4. Filtering (= Post-Retriever)
 - [ ] Meta-Data Filtering
 - [ ] Similarity threshold cut-off
 - [ ] Passage Filtering : Refine
 - [ ] Passage Filtering : Compressor
## 5. Re-Ranking (= Post-Retriever)
 - [ ] API Base
 - [ ] LM Base
 - [ ] LLM Base
 - [ ] Language Specific Model Base
## 6. Prompting
 - [ ] Long-Context Reorder (-> Lost in the middle)
 - [ ] Zero-shot & Few-shot
 - [ ] Prompt-Chaining
 - [ ] CoT
 - [ ] ToT
 - [ ] TDB
 - [ ] ReAct
 - [ ] Reflextion
## 7. Generation & Inference
 - [ ] LLM Base Generation
 - [ ] Data type(fp16, fp32, bp16, nf16, etc..)
 - [ ] vllm
 - [ ] Ollama
 - [ ] DSPy
## 8. Hallucination Control
 - [ ] CRAG
 - [ ] Self-RAG
 - [ ] etc..  
## 9. Evaluation
 - [ ] Evaluation (each RAG step)
 - [ ] Relevance (hitrate)
 - [ ] Groundtruth 
## 10. Methology
 - [ ] Memory moudle (from Modular RAG)
 - [ ] Tabular Data Reasoning
 - [ ] RE-Questioning
 - [ ] RAG Module Implementation
