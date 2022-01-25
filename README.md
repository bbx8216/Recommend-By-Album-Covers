# Album Recommendation System using Image Similarity

**이미지 유사도 기반 앨범 추천 시스템**
<br/>
<br/>
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FCUAI-CAU%2FRecommendByAlbumCovers.git&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)


[paper](https://github.com/CUAI-CAU/RecommendByAlbumCovers/blob/main/2022CUAI_winter%20%EC%9D%B4%EB%AF%B8%EC%A7%80%EC%9C%A0%EC%82%AC%EB%8F%84%20%EA%B8%B0%EB%B0%98%20%EC%95%A8%EB%B2%94%20%EC%B6%94%EC%B2%9C%20%EC%8B%9C%EC%8A%A4%ED%85%9C_paper.docx?raw=true) | [PPT](https://github.com/CUAI-CAU/RecommendByAlbumCovers/blob/main/2022CUAI_winter%20%EC%9D%B4%EB%AF%B8%EC%A7%80%EC%9C%A0%EC%82%AC%EB%8F%84%20%EA%B8%B0%EB%B0%98%20%EC%95%A8%EB%B2%94%20%EC%B6%94%EC%B2%9C%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C.pptx?raw=true)

## Members

• [**Jaeyong Lee**](https://github.com/jaeyonggy) - School of Applied Statistics, Chung-Ang Univ.   
• [**Surin Kim**](https://github.com/eggplant000) - School of Applied Statistics, Chung-Ang Univ.   
• [**Minki Kang**](https://github.com/bbx8216) - School of Computer Science & Engineering, Chung-Ang Univ. 
<br/>
<br/>


## Abstract

기존 음악 추천 시스템과 달리 앨범 커버라는 시각적 데이터를 사용하여 음악 추천 시스템을 구현하였다.

사용자가 선호하는 앨범들의 앨범 커버(Album cover)와 추천된 앨범을 통해 얻고자하는 감정 또는 사용자의 현재 감정(angry, happy, relaxed, sad)을 입력받는다. YOLO와 k-means를 이용하여 입력받은 앨범과 같은 감정을 가진 앨범 중 객체 및 색채를 기준으로 앨범 커버의 유사도가 높은 앨범 5종을 추천한다.  
<br/>
<br/>


## Pipeline

![KakaoTalk_Photo_2022-01-24-20-07-20](https://user-images.githubusercontent.com/63530964/150773784-ea0755da-50a1-44b3-8dc5-34decd8b0ba3.png)
<br/>
<br/>


## Recommendation Results

#### Based on Object Detection
![그림2](https://user-images.githubusercontent.com/63530964/150704854-23e513ce-89f2-4207-b1f7-45e0f05bdfc2.png)
<br/>

#### Based on Representative Color
![그림3](https://user-images.githubusercontent.com/63530964/150704855-0de13475-2875-4cce-826b-16278367d4ac.png)
