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
    
    ![Google](data:image/png;base64,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)

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

- 마크다운 내에서 LaTex 문법으로 수식 작성하기

    마크다운 내에서 LaTex문법을 작성할 수 있습니다. 이를 통해 수식을 넣을수 있게됩니다.
    LaTex문법은 여기를 참고하시면 됩니다 : [링크](https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:TeX_%EB%AC%B8%EB%B2%95)
    LaTex문법 작성을 위해서는 $과 $로 묶어준 다음 그 안에서 LaTex문법을 작성해 주면 됩니다.
    
    **LaTex문법은 해당 마크다운 에디터가 멀티 마크다운 일때만 지원됩니다**

    ~~~
    $
    LaTex 기호
    $
    ~~~
