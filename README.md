# Line_Tracer_AutoCar
<b>AIoT AutoCar Prime을 이용한 라인트레이서입니다. (카메라만 사용)</b> <br><br>
[![Video Label](http://img.youtube.com/vi/OqTPGbrp2nU/0.jpg)](https://youtu.be/OqTPGbrp2nU)

## 사용 제품
https://hanback.com/ko/archives/9740

## 사용 기술
Gaussian Blur

영상에서 ROI 추출

HSV를 이용한 color masking

bounding box 생성, 무게중심 좌표 반환 

무게중심 좌표를 이용해 바퀴의 각도 반환

## 프로세스
1. 320 x 240으로 down scailing
2. Gaussian Blur 사용
3. ROI 지정 <br>
![image](https://github.com/woodong11/Line_Tracer_AutoCar/assets/91379630/7a2554ba-acc6-4112-a942-c975cc1dbe7a)
4. HSV를 이용한 Color Masking <br>
![image](https://github.com/woodong11/Line_Tracer_AutoCar/assets/91379630/97d9264b-0f80-4f96-a801-9e5fb8b5721f)
5. Bounding box 찾고 Center of gravity 찾기
![image](https://github.com/woodong11/Line_Tracer_AutoCar/assets/91379630/b48c57ae-2775-47f5-b3ab-090c4184f66a)
6. 무게중심의 x좌표에 따라 steering 조절








