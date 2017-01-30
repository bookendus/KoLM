# KoLM
한국어 언어모델을 만들기 위한 파이썬 기반 한국어 텍스트 처리 패키지입니다.  
본 패키지는 Python 2.7 버전을 기반으로 만들어졌으며 지속적으로 업데이트되고 있습니다.
</br>
</br>
## Requirements
- Python 2.7

## 주요 기능  
- 한국어 코퍼스 처리 (인코딩 변환, 파일 통합, 어절 통계, 텍스트 정규화 등)  
- 형태소 분석 (KoNLPy의 Mecab 연동)  
- 형태소 분석 결과로부터 의사형태소(pseudo-morpheme) 생성  
- 문자열로부터 발음열 생성(Grapheme-to-Phone; G2P)  
- 언어모델 제작을 위한 파일 생성
	- 정제된 코퍼스 원문(textraw) 생성  
	- 발음사전(lexicon.txt) 생성  
