
# 디자인 패턴

## Ⅰ.분류
1. 생성 패턴 - 객체를 어떻게 만들것인가

    <table>
        <thead>
            <th>번호</th>
            <th>패턴명</th>
            <th>설명</th>
        </thead>
        <tbody>
            <tr>
                <td>⑴</td>
                <td>싱글톤</td>
                <td>클래스의 인스턴스가 오직 하나만 생성되도록 보장하는 패턴</td>
            </tr>
            <tr>
                <td>⑵</td>
                <td>팩토리</td>
                <td>객체 생성의 인터페이스를 정의하고, 어떤 클래스의 인스턴스를 만들지는 서브클래스에서 결정하는 패턴</td>
            </tr>
            <tr>
                <td>⑶</td>
                <td></td>
                <td></td>
            </tr>
        </tbody>
    </table>
    
2. 행동 패턴 - 객체 순회를 어떻게 진행할지, 알고리즘을 어떻게 짤지

    <table>
        <thead>
            <th>번호</th>
            <th>패턴명</th>
            <th>설명</th>
        </thead>
        <tbody>
            <tr>
                <td>⑴</td>
                <td>전략</td>
                <td>객체의 행위를 바꾸고 싶을 때 사용</td>
            </tr>
            <tr>
                <td>⑵</td>
                <td>옵저버</td>
                <td>객체의 상태가 변화했을 때, 그 객체에 의존하는 다른 객체들에게 통보하는 패턴</td>
            </tr>
            <tr>
                <td>⑶</td>
                <td>이터레이터</td>
                <td>컬렉션의 요소들에 접근하는 패턴</td>
            </tr>
        </tbody>
    </table>

3. 구조 패턴 - 구조를 효율적으로 관리하는 방법

    <table>
        <thead>
            <th>번호</th>
            <th>패턴명</th>
            <th>설명</th>
        </thead>
        <tbody>
            <tr>
                <td>⑴</td>
                <td>프록시</td>
                <td>대리자 패턴으로, 어떤 객체에 대한 접근을 제어하는 패턴</td>
            </tr>
        </tbody>
    </table>

## Ⅱ. 대표적인 아키텍처처 패턴
### 1. MVC (Model-View-Controller)
   - 모델, 뷰, 컨트롤러로 구성된 아키텍쳐 패턴
   - 모델 : 데이터와 로직을 담당하는 부분
   - 뷰 : 사용자 인터페이스를 담당하는 부분
   - 컨트롤러 : 모델과 뷰 사이의 상호작용을 처리하는 부분

### 2. MVP (Model-View-Presenter)
   - MVC의 변형으로, 뷰와 모델 사이에 프레젠터가 위치하여 상호작용을 처리하는 패턴
   - 뷰는 프레젠터에게 이벤트를 전달하고, 프레젠터는 모델에서 데이터를 가져와 뷰에 표시함

### 3. MVVM (Model-View-ViewModel)
   - 데이터 바인딩을 활용한 아키텍쳐 패턴으로, 뷰모델이 모델과 뷰 사이의 중재 역할을 함
   - 뷰모델은 뷰에 필요한 데이터를 제공하고, 뷰는 데이터 바인딩을 통해 자동으로 업데이트됨


<br>
<br>
<details>
  <summary>여기를 클릭하면 펼쳐집니다</summary>
  <p>숨겨진 내용이 여기에 표시됩니다.</p>
</details>

<style>
  summary {
    list-style: none;
  }
  summary::-webkit-details-marker {
    display: none;
  }
</style>