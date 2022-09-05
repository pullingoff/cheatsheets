# cheatsheets

No copyright intended.

## JS
<section style='display:flex'>
  <img width='60%' src='https://user-images.githubusercontent.com/50111853/188340183-10549aa7-888d-47d9-b277-c66f0fed0ce3.jpeg' />
</section>

## CSS

<section style='display:flex'>
  <img width='30%' src='https://user-images.githubusercontent.com/50111853/188340299-79686a5b-63bb-4690-a05d-6b8ddec79f9c.png' />
  <img width='30%' src='https://user-images.githubusercontent.com/50111853/188340295-24c6900a-059c-41b1-8829-411f252f29ad.png' />
  <img width='30%' src='https://user-images.githubusercontent.com/50111853/188340249-a7f5f5a1-4783-4966-b5fe-f2435a351dd8.png' />
  <img width='30%' src='https://user-images.githubusercontent.com/50111853/188340268-76da9ee8-e8a6-4078-ad37-f68270c6e3e3.png' />
  <img width='30%' src='https://user-images.githubusercontent.com/50111853/188340278-a3bb67a6-7a6d-468c-a82d-6e097d65bb50.png'/>
</section>

---
### 데이터가 엄청 많은 리스트, 그리드 7배 렌더링 빠르게 하기
[Original Source by Murtaza Nathani](https://dev.to/mnathani/two-lines-of-css-that-boosts-7x-rendering-performance-4mjd)

```css
{
  content-visibility: auto;
  contain-intrinsic-size: 1px 5000px;
}
```

- `content-visibility: auto`을 적용하면 브라우저가 렌더링을 알아서 처리함.  
- 먼저 많은 데이터들을 보이지 않게 로드 -> 그걸 담는 컴포넌트를 생성 -> DOM을 구성하면 -> 브라우저가 그 DOM의 99퍼센트를 알아서 계산해준다. 
**다만 애초에 많은 데이터들을 한번에 불러오지 않는게 좋다.** 

---

### div를 가운데정렬하는 10가지 방법
![how to center a div](https://user-images.githubusercontent.com/50111853/188340581-ba6cee96-955b-4cf2-afbf-2f963a2a6a88.JPG)

## HTML

<section style='display:flex'>
  <img width='60%' src='https://user-images.githubusercontent.com/50111853/188340222-232ff7a0-e1a1-422f-9d95-2cea8a9a66ac.png' />
</section>

`<input type="number"/>`는 숫자를 1씩 증감하는 것이 의미있는 경우에만 적절. 

보통의 경우(예: 우편번호, 카드번호)라면 `<input type="text" inputmode="numeric"/>`을 먼저 고려하여 UX 개선.

## React
