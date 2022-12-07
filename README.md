# seeyoutube-backend-sample
기존의 YOLOV5 알고리즘을 수정하여 동영상에서 객체를 인식함과 동시에 객체 데이터를 생성하여 실시간으로 출력한 토이프로젝트입니다.

</br>

## 프로젝트 소개

![sample_detection (1) (online-video-cutter com) (1)](https://user-images.githubusercontent.com/65602906/206127633-04e811ef-64f4-4329-88a2-caacd0d15c1f.gif)

- 동영상 파일을 detect하면 객체를 인식하여 보여줍니다
- 프레임마다 인식된 객체의 이름, Bounding Box 좌표, 정확도를 시간과 함께 출력합니다
<img width="565" alt="반디캠캡쳐" src="https://user-images.githubusercontent.com/65602906/206129639-5e6cb4ad-a76c-4497-895d-4c1c86acf94c.png">


</br>

## 준비사항

- Google Colab에 접속할 Google ID

</br>

## 프로젝트 실행 환경 

- Google Colab

</br>

## 프로젝트 실행 방법

1. 'seeyoutube-backend-sample' repository에서 ObjectDetection.ipynb를 들어가 'Colab에서 열기' 버튼을 클릭합니다.
2. 작성되어 있는 명령어를 순서대로 실행시킵니다.
3. 마지막 detect 명령어를 실행하면 실시간으로 샘플 동영상이 detection되면서 객체 데이터가 출력되는 것을 확인할 수 있습니다. 
4. detect된 동영상 파일은 마지막 detect 명령어 실행 결과창의 마지막 줄에 적혀 있는 파일에 들어가 다운로드하여 확인할 수 있습니다.
