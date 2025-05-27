# PCT-Image-Converter

**Windows Only!**

[Download](https://github.com/iygfa/PCT-Image-Converter/releases/download/v0.1.0/PCTImageConverter.0.1.0.exe)

[Ko-Fi](https://ko-fi.com/gwlee)

도면 이미지 파일들을 PCT 국제출원에서 요구하는 사양인 tif로 변환하는 프로그램
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

----------------------------------------------------------------------

Software to convert drawing image files to tif, the specification required for PCT applications
- 300 dpi
- 170mm x 255mm
- CCITT Group 4 compression
- 1-bit monochrome
- Intel Encoding
- Single Strip

Maintains the above specifications, but with filters for image quality
- Unsharp Mask
- MinFilter (Elode)
- Top-Hat/Bottom-Hat
- Selectable Dithering algorithm

Easily modify image size/orientation
- Preserve image aspect ratio
- Automatically shrink images that exceed the size limit (170mm x 255mm)
- Enlarge small images if needed
- Can use LANCZOS algorithm when resizing

And more
- Preview in real time
- Creates an output folder if one does not exist
