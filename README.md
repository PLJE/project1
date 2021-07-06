# KAISTcamp-project1   
## APK 구글 드라이브 링크
https://drive.google.com/file/d/1u3ICO728WT359Lc7Pm-EyFGLJAuYmz08/view?usp=sharing
## Team : 이주은, 양현호   
## Project1 - 탭 구조를 이용한 안드로이드 앱    
- TabLayout 과 ViewPager2를 이용하여 탭 구조 구현   
   
   
   
## [탭1] 휴대폰 주소록 불러오기   
### 화면   
- 휴대폰 기본 주소록앱에 저장된 번호, 사진, 이름 data를 contentResolver를 이용해서 가져와 RecyclerView 형식으로 띄움
- 사진이 없는 경우는 디폴트로 지정한 이미지
<img src = "https://user-images.githubusercontent.com/77712822/124542052-a070bd80-de5d-11eb-961e-ac890ab981e8.jpg" width="30%" height = "30%">    

### 기능       
- 가로로 스와이프하면 번호가 리사이클러뷰에서 삭제되고, contentResolver로 연락처 앱에서도 삭제되도록 구현
<img src = "https://user-images.githubusercontent.com/77712822/124557405-6d85f400-de74-11eb-83e3-ea6e0f09e405.png" width="30%" height = "30%">   

- ItemTouchHelper를 이용하여 Long click & drag 로 아이템의 위 아래 위치 변경 가능하도록 구현  
- 전화 버튼을 클릭하면 휴대폰 다이얼 화면으로 넘어가 해당 번호를 띄워 전화 걸기 가능   
<img src = "https://user-images.githubusercontent.com/77712822/124542556-8edbe580-de5e-11eb-9f1c-28c821285e88.jpg" width="30%" height = "30%">  
    
    
## [탭2] 갤러리   
### 화면   
- 어플에 저장한 이미지를 두개의 CardView로 나누어서 보여주고, 하나의 카드뷰는 여러 이미지를 RecyclerView로 띄움   
<img src = "https://user-images.githubusercontent.com/77712822/124542132-c39b6d00-de5d-11eb-85d1-f36bdc0d5ecf.jpg" width="30%" height = "30%">
<img src = "https://user-images.githubusercontent.com/77712822/124542153-ce560200-de5d-11eb-8d13-2546e44d6214.jpg" width="30%" height = "30%">

### 기능 
- 이미지를 클릭하면 확대해서 보여줌  
- 스와이프하면 이미지를 넘길 수 있음   
      
         
## [탭3] 모스 부호 변환 및 인식기   
### 기능   
- 출력 : 영어로 메시지를 입력하면 모스부호를 카메라 플래시로 출력     
<img src = "https://user-images.githubusercontent.com/77712822/124542175-da41c400-de5d-11eb-8d02-9aa23c29d6bf.jpg" width="30%" height = "30%"> 

- 디코드 : OpenCV 라이브러리를 이용해 카메라로 빛을 인식하여 모스 부호를 해독하여 메시지 띄움   
<img src = "https://user-images.githubusercontent.com/77712822/124558331-71fedc80-de75-11eb-982d-043cfe1e0bbc.png" width="30%" height ="30%">



