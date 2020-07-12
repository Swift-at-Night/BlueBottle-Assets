# BlueBottle-Assets
블루보틀 관련 이미지와 텍스트 리소스

## 구성
1. 블루보틀 앱아이콘
2. 블루보틀 음료 이미지 모음
3. 블루보틀 음료 세부 정보 (음료 이름, 소개문구, 설명, 칼로리 등)
4. 블루보틀 음료 정보를 나타내는 `Drink` 구조체가 정의된 `.swift` 파일

## 사용방법
- `AppIcon` 폴더에 있는 이미지들을 **Assets**폴더의 App Icon에 적절한 위치에 드래그 앤 드랍 합니다.
- 이미지들은 Xcode 프로젝트의 **Assets** 폴더에 드래그앤 드랍 합니다.
- `Drink.swift` 파일도 Xcode 화면 좌측 **Navigator**의 적절한 위치에 드래그 앤 드랍 합니다.
- `Drink.fetchDrinks()` 메소드를 통해 저장된 모든 음료들을 `[Drink]` 형태로 가져올 수 있습니다.

> **참고**
> `Drink.swft` 파일에 있는 음료 정보들은 `BlueBottle.txt`의 일부만 가져온 것이므로 음료들을 추가할 때는 `BlueBottle.txt` 를 참고하면 됩니다.

- - -
각 음료 이미지와 세부정보 들은 실제 블루보틀 앱에서 가져왔습니다(BLUE BOTTLE COFFE Inc.)
All images and details originated from "Blue Bottle", an application service by BLUE BOTTLE COFFEE Inc..
