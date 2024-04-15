# Estimaion-and-AR
camera estimation and AR object visualization using OpenCV in python
<h2>소개</h2>
<p>내 카메라를 캘리브레이션하고, 촬영한 물체에 대해 간단한 AR 기법을 적용해 보았다.</p>
<h2>기능</h2>
<ul>
  <li>1. 나의 카메라를 이용해 카메라의 자세를 획득</li>
  <li>2. AR 물체 표시</li>
</ul>
<h2>내용</h2>
<p>1. 카메라 캘리브레이션을 수행하여 카메라의 자세 좌표를 얻었다.</p>
<p><img width="722" alt="cv4-1" src="https://github.com/Cho1jaeho/Estimaion-and-AR/assets/162866830/1355e25b-a08d-40b1-a702-490cc5a4737a">
<img width="487" alt="cv4-2" src="https://github.com/Cho1jaeho/Estimaion-and-AR/assets/162866830/4ea8ae3e-0ec3-45cb-8821-55d1979172be"></p>
<p>2. 이 좌표값을 pose_estimation 코드에 넣어 AR 물체를 표시하였다.</p>
