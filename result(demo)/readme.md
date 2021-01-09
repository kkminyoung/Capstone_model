# result(demo)

- input : 테스트해보고 싶은 동영상 파일 (.mp4형식)
- output : frame별 anomaly score (.txt형식) 


1)강도질, 2) 정상 도로 상황, 3) 교통사고 각각의 동영상에 대해 테스팅해봤는데 결과 상태가 좋다!!!



### 실행방법
```
1. 'https://drive.google.com/file/d/105RYWyyyHLppTAaudntde_ocA8NyMRtL/view?usp=sharing'로가서 c3d_sports1m.h5 파일을 다운받아  trained_models 폴더에 저장한다.
2. cmd 창을 켜고 Capstone_model/result(demo) 폴더로 이동
3. pip install -r requirements.txt
4. python test_detect.py
5. python app.py 실행 localhost/5000/anomaly_score로 이동
```
