Markdown Recipe
===
***

# 1. 제목(header)

- 문자서의 메인 제목(Main Title)으로 작성할 때

    ~~~
    Title
    ===
    ~~~
    
    다음과 같이 제목을 작성 후 그 밑에 **===**를 작성해 주면 제목으로 설정이 됩니다. 이 문법의 디폴트 값은 `#( == <h1>)`과 동일한 기능을 가집니다.

- 제목(`<h1>`,`<h2>`,`<h3>`,`<h4>`,`<h5>`,`<h6>`)

    ~~~
    # 제목
    ## 제목
    ### 제목
    #### 제목
    ##### 제목
    ###### 제목
    ~~~

    # 제목 
    ## 제목
    ### 제목
    #### 제목
    ##### 제목
    ###### 제목

    다음과 같이 #을 제목 앞에 붙여주면 됩니다. #의 최대 개수는 6개까지 입니다.주의할점은 #과 제목 사이에 한칸 띄어야한다.

- 목록

    - 순서 목록(Ordered List `<ol>`)

    ~~~
    1. A
    2. B
    3. C
    ~~~
    1. A
    2. B
    3. C

    - 순서 없는 목록(Unordered List `<ul>`)

    ~~~
    상위 목록의 처음 위치와 4칸 차이가 있습니다(Tab키)
    - A  
        - B
            - C
    
    + A
        + B
            + C
    ~~~

    - A
        - B
            - C
    
    + A
        + B
            + C
    
- 블록 생성

    ~~~
        ~~~
        마크다운
        ~~~
    ~~~

    ~~~
    Test Block
    ~~~

- 수평선(`<hr>`)

    수평선을 그어주는 문법입니다

    ~~~
    ***
    - - -
    ~~~

    예시)
    
    ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
    구분1
    ***
    구분2
    ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

- 링크기능

    ~~~
    [링크를 의미하는 단어 및 글](링크)
    ~~~

    [Naver](https://www.naver.com/)

- 이메일 연결(`<mailto>`)

    ~~~
    <메일주소>
    ~~~

    <jhyoon0815103@gmail.com>

- 이탤릭체(기울임체,`<i>` or `<em>`)

    ~~~ 

    *글*

    ~~~

    *로시작해서 꼭 *로 끝맺음을 해주어야합니다.

    *Markdown Recipe*

- 굵은 글씨 및 글자강조(`<b>`)

    ~~~

    **글**

    ~~~
    
    위의 이탤릭체와 동일하게 **로 시작해서 **로 끝맺음을 해주어야합니다.

    **Markdown Recipe**

- 이미지 첨부(`<img>`)

    ~~~

    ![이미지 설명(이 부분은 이미지 로드에 실패했을경우에 표시됩니다.img태그의 alt속성과 동일 )](이미지의 디렉토리 혹은 링크)

    ~~~
    
    ![Google](http://www.koreaittimes.com/news/photo/202003/96284_41540_2439.png)

    마크다운에서는 이미지 사이즈 조정이 불가능합니다.

- 코드블럭

    주로 마크다운에 코드를 첨부할때 사용합니다

    ~~~

    ```언어(C,C++,Python...etc)

        코드

    ```
    ~~~

    ```python
    print("hello world")
    ```

    ```java
    public static void main(String[] args)
    {
        System.out.println("hello world");
    }
    ```
- 인용문(Quote)

    ~~~

    > quote
    > > inner quote

    > * quote list

    ~~~

    > I skate to where the puck is going to be, not to where it has been.
    
    > quote
    > > quote

    > * quote list1
    > * quote list2

- 표(Table)

변수(열(column)이름)정렬은 ':'를 통해 정의할 수 있다. 왼쪽에만 : 작성시 왼쪽정렬, 오른쪽에만 : 작성시 오른쪽 정렬 양쪽 모두 : 작성시 가운데 정렬로 정의가된다.
    
    <가장 기본적인 표>
    
    |Col1|Col2|Col3|
    |----|----|----|
    |content|content|content|
    |content|content|content|
    |content|content|content|
    
    <변수 왼쪽정렬>
    
    |Col1|Col2|Col3|
    |:----|:----|:----|
    |content|content|content|
    |content|content|content|
    |content|content|content|
    
    <변수 오른쪽 정렬>
    
    |Col1|Col2|Col3|
    |----:|----:|----:|
    |content|content|content|
    |content|content|content|
    |content|content|content|
    
    <변수 가운데 정렬>
    
    |Col1|Col2|Col3|
    |----|----|----|
    |content|content|content|
    |content|content|content|
    |content|content|content|

결과는 아래와 같다.

<왼쪽정렬>

 |Col1|Col2|Col3|
 |:----|:----|:----|
 |content|content|content|
 |content|content|content|
 |content|content|content|
 
<오른쪽 정렬>

 |Col1|Col2|Col3|
 |----:|----:|----:|
 |content|content|content|
 |content|content|content|
 |content|content|content|

<가운데 정렬>

 |Col1|Col2|Col3|
 |:----:|:----:|:----:|
 |content|content|content|
 |content|content|content|
 |content|content|content|
