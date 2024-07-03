# RAG study
* RAG(Retrieval-Augmented Generation) 관련 코드

# 추후 사용시 참고 할만한 곳
* https://wikidocs.net/book/14314
  
# 생각
* LM context 는 token_size 중심이라 chunking 시 일반 splitter 보다는 임베딩 모델콜로 생성 및 분리
* Semantic chunker 를 사용하여 의미론적 유사한 청크 분할방법 고려
* similarity_score_threshold 가 일정값이상만 리턴하여야 불필요한 정보를 줄임
