[English](https://github.com/iygfa/PCT-Image-Converter/blob/main/README.md) | **한국어**

![KR](https://github.com/user-attachments/assets/c77e3097-f256-4b84-ad50-2b6a575e1c89)

도면 이미지 파일들을 <ins>**PCT 국제출원**</ins> 에서 요구하는 사양인 <ins>**Tiff format**</ins> 으로 변환하는 프로그램
- 300dpi
- 170mm x 255mm
- CCITT Group 4 압축
- 1-bit 흑백 이미지
- 인텔식 인코딩
- 싱글 스트립

위의 사양을 지키면서도, 화질을 위해 필터 탑재
- 언샤프 마스크(Unsharp Mask)
- 최소값 필터(MinFilter, Elode)
- Top-Hat/Bottom-Hat
- 디더링 알고리즘 선택 가능

이미지 크기/방향을 쉽게 변경
- 이미지 가로세로 비율을 유지
- 크기제한(170mm x 255mm)을 초과하는 이미지는 자동으로 축소
- 필요한 경우, 작은 이미지를 확대 가능
- 리사이즈시 LANCZOS 알고리즘 사용 가능

그 외
- 실시간으로 미리보기 가능
- 출력폴더가 없는 경우 알아서 생성
