사용자가 음성으로 만들고싶은 이미지를 말을하면 Azure STT 로 텍스트로 변환한뒤 translator로 영어로 변환한다
변환된 문장을 Wordnet으로 단어로 짜른뒤 그 단어의 대한 반의어를 추출한다 번역된 단어는 prompt 반의어는 negative prompt
KALO prompt에 사용이 된다 KALO 에서 Image 를 생성한뒤 영어로 번역된 문장을 TTS 로 출력한다
