# RecommendByAlbumCovers

**이미지 유사도 기반 음악 추천 시스템**
<br/>


## 프로젝트 요약

기존 음악 추천 시스템과 달리 앨범 커버라는 시각적 데이터를 사용하여 음악 추천 시스템을 구현하였다. 구현한 추천 시스템은 다음과 같다.  

사용자가 선호하는 앨범들의 앨범 커버(Album cover)와 그 앨범의 감정(angry, happy, relaxed, sad)을 입력받는다. YOLO와 k-means를 이용하여 입력받은 앨범과 같은 감정을 가진 앨범 중 객체 및 색채를 기준으로 앨범 커버의 유사도가 높은 앨범 5종을 추천한다.  
<br/>
<br/>


## 팀원

• **이재용** - 응용통계학과  
• **김수린** - 응용통계학과  
• **강민기** - 소프트웨어학부  
<br/>
<br/>


## 모델

![그림1](https://user-images.githubusercontent.com/63530964/150704785-c766eb05-5d63-42a8-8f77-41bb4c37e3f3.png)
<br/>
<br/>


## 추천 시스템 결과

**객체 인식 기반**
![그림2](https://user-images.githubusercontent.com/63530964/150704854-23e513ce-89f2-4207-b1f7-45e0f05bdfc2.png)
<br/>

**대표색 추출 기반**
![그림3](https://user-images.githubusercontent.com/63530964/150704855-0de13475-2875-4cce-826b-16278367d4ac.png)
