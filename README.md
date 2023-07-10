# React
React 예상 면접질문


<br>


<details>
<summary>리액트는 라이브러리인가요 프레임워크인가요</summary>
<div markdown="1">
React는 복잡한 사용자 인터페이스를 JavaScript만으로 만드는 것보다 훨씬 쉽게 구축할 수 있게 해주는 라이브러리입니다. (전적으로 Client 사이드 JavaScript 코드)
라이브러리는 보통 하나에 초점을 맞추는데, React의 경우는 사용자 인터페이스 부분에만 초점을 맞춘 라이브러리입니다. 
대규모의 React 프로젝트를 구축하려면 라우팅에 필요한 라이브러리, 인증에 필요한 라이브러리 등을 추가해야합니다.
</div>
</details>

<details>
<summary>리액트를 사용하는 이유</summary>
<div markdown="1">
React는 컴포넌트를 사용해서 유지보수가 용이하고, virtual DOM을 활용하여 필요한 부분의 컴포넌트만 렌더링할 수 있기 때문에 최적화되고 빠른 렌더링이 가능합니다. 또한 다양한 라이브러리 사용이 가능합니다. 
</div>
</details>

<details>
<summary>virtual DOM에 대해서 아나요</summary>
<div markdown="1">
리액트는 XML이나 HTML 문서에 접근하기 위한 일종의 인터페이스인 DOM(Document Object Model)을 활용하여 객체의 자바스립트와 CSS를 적용합니다. DOM은 새로운 요청이 있으면 렌더트리를 재생성하고 레이아웃을 만들고 페인팅을 하는 과정을 거쳐 리렌더링을 하게 되는데, 규모가 큰 애플리케이션에서 DOM에 직접 접근하게 되면 성능 이슈가 발생하게 됩니다. 그래서, 리액트는 실제 DOM의 사본인 Virtual DOM을 사용하여 DOM 업데이트를 추상화함으로써 DOM 처리 횟수를 최소화하고 효율적으로 진행합니다. 리액트에서 데이터가 변하여 웹 브라우저에 실제 DOM을 업데이트 할 때는 다음 절차를 밟습니다. 데이터를 업데이트 하면 전체 UI를 Virtual DOM에 리렌더링하고, 이전 Virtual DOM에 있던 내용과 현재 내용을 비교하여 바뀐 부분만 실제 DOM에 적용합니다. Virtual DOM 을 사용한다고 해서 리액트가 무조건 빠른 것이 아니라 지속적으로 데이터가 변화하는 대규모 애플리케이션에서 사용할 때 효율적으로 사용할 수 있습니다.
</div>
</details>

<details>
<summary>React에서 함수 컴포넌트와 클래스 컴포넌트의 차이</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>props와 state의 차이</summary>
<div markdown="1">
props는 부모 컨포넌트로부터 전달 받은 다양한 정보(속성)를 담고 있는 자바스크립트 객체입니다. state는 컴포넌트 내부에서 바뀔 수 있는 상태값으로 변화하는 데이터가 사용자 인터페이스에 반영되어야할 때 쓰입니다. 즉, state가 바뀌면 해당 state가 등록된 컴포넌트형 함수가 재실행되고 JSX 코드를 다시 평가합니다.
</div>
</details>

<details>
<summary>Props가 컴포넌트간에 
전달받는 것이라고 했는데 자식에서 부모로도 
전달할 수 있는가</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>FLUX에 대해서 아나요?</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>리덕스에 대해서 아나요? </summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>리덕스의 기본 원칙은?</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>React에서 state 불변성을 유지하라는 말이 있는데 이에 대해 설명해주세요.</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>


<details>
<summary>리듀서 내부 불변성을 지키는 이유는? 전개 연산자의 단점을 해결할 수 있는 방법은 무엇인가? </summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>리액트 사용 시 부수효과 문제점은? </summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>컴포넌트 라이프 사이클 메서드는?</summary>
<div markdown="1">
컴포넌트 사이클은 마운트, 업데이트, 언마운트 카테고리로 나뉩니다.
마운트는 DOM이 생성되고 웹 브라우저상에서 나타나는 것,
업데이트는 props, state가 바뀔 때, 부모 컴포넌트가 리렌더링되는 것,
언마운트는 마운트의 반대 과정, 즉 컴포넌트를 DOM에서 제거하는 것입니다.
</div>
</details>

<details>
<summary>Hooks의 종류</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>


<details>
<summary>useCallback을 사용할 때와 사용하지 않고 함수를 선언할 때는 어떤 차이가 있나요?</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>


<details>
<summary>useMemo와 useCallback의 차이를 아나요</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>언제 useState 대신 useRef를 쓸 수 있나요?</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>리액트에서 setState는 비동기 동작인가요 동기 동작인가요? </summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>


<details>
<summary>setState가 비동기 동작을 취했을 때 얻을 수 있는 이점은 무엇인가요?</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>


<details>
<summary>useLayoutEffect는 무엇인가요?</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>


<details>
<summary>리액트의 성능개선 방법에 대해서 설명해주세요</summary>
<div markdown="1">
useMemo나 useCallback같은 Hook 함수를 사용하거나 Next.js 프레임워크, react.lazy 함수 등을 사용하여 코드 스플리팅을 통해 성능 개선을 할 수 있습니다.
</div>
</details>

<details>
<summary>컴포넌트에서 이벤트를 실행시키기 위해서는 어떻게 핸들링해야 하나요</summary>
<div markdown="1">
이벤트로 설정할 함수를 호출하는 것이 아니라 직접 넣어 줄 때는 화살표 함수 문법을 사용하여 넣어 주어야 합니다.
</div>
</details>

<details>
<summary>SPA가 뭔가요</summary>
<div markdown="1">
Single Page Application의 약자. index.html 한개의 페이지와 여러개의 JavaScript 파일로 이루어진 애플리케이션을 뜻합니다. 대표적인 SPA 프레임워크는 React가 있습니다.
</div>
</details>

<details>
<summary>SSR이 뭔가요</summary>
<div markdown="1">
Server Side Rendering의 약자. HTML 문서가 매 페이지 요청이 있을때마다 생성되는 사전 렌더링 방식입니다. SSG에 비해 데이터가 자주 업데이트 되는 동시에 SEO가 요구되는 경우, 사용자의 요청이 있어야 데이터가 변경되는 경우에 유용합니다.
단점은 서버에 매번 요청을 하기 때문에 서버에 부하가 많은 것, 초기 로딩은 사전렌더링이 되어 괜찮지만 페이지 전환할때마다 새로고침되어 화면이 깜빡거린다는 느낌을 받을 수 있습니다.
</div>
</details>

<details>
<summary>SEO가 뭔가요</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>하이드레이션에 대해 알고 있나요</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>Next의 렌더링 수행 방식</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>Next를 쓴 이유가 있나요</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>

<details>
<summary>Next를 구성하는 기본 설정 파일에 대해서 알고 있나요?</summary>
<div markdown="1">
Next를 구성하는 기본 설정 파일은 pages 폴더 안에 들어가는 app.tsx 파일, document.tsx 파일, error.tsx 파일 등이 있습니다.

app.tsx 파일의 App 컴포넌트는 모든 페이지의 공통 페이지 역할을 하므로 페이지들의 공통 레이아웃, 페이지 탐색할 때 상태 유지, 추가 데이터를 페이지에 주입, global CSS 추가 등의 역할을 합니다.

document.tsx 파일은 사용자 정의 Document로 일반적으로 html 및 body 태그를 보강하는데 사용됩니다. title, description, meta 등 프로젝트의 정보를 제공하는 HTML 코드를 작성할 수 있고 그 외에 폰트, 외부 api, cdn 불러오기, 서버 사이드 렌더링 설정 등을 할 수 있습니다.

error.tsx 파일은 에러 페이지의 역할을 합니다. Next에서는 따로 라우팅 경로를 설정하지 않더라도 빌드된 프로덕션 환경에서 에러가 발생한다면 error.tsx 파일로 자동으로 넘어가게 됩니다. 추가적으로 에러 상황에 따라 500.tsx, 404.tsx 파일 등을 추가할 수 있습니다.
</div>
</details>

<details>
<summary>사전 렌더링을 위해 사용해 본 함수가 있나요</summary>
<div markdown="1">
Next 9.3 버전 이전에는 getInitialProps만을 사용했지만, 9.3 버전 이후부터는 3가지 사전 렌더링 함수가 있습니다.
첫째로 getStaticProps를 사용할 수 있습니다. 빌드시 고정되는 값으로 빌드 이후에는 수정이 불가능하고, 빌드 시에 data를 미리 가져와 정적(static)으로 제공하므로 매 유저의 요청마다 fetch할 필요가 없는 데이터를 가진 페이지를 렌더링할 때 유리합니다.
둘째로 getStaticPath를 사용할 수 있습니다. getStaticProps와 동적 라우팅 둘다 필요할 때 사용할 수 있습니다. 동적 라우팅 시, 라우팅되는 경우의 수를 하나하나 넣어야하고 정의하지 않은 하위 경로는 접근해도 화면이 뜨지 않고 에러 페이지로 라우팅됩니다.

셋째로 getServerSideProps를 사용할 수 있습니다. 빌드와 상관없이, 매 페이지 요청마다 데이터를 서버로부터 가져올 수 있습니다.
</div>
</details>


<details>
<summary>Suspense가 뭔가요? </summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>


<details>
<summary>suspense로 가능한 것은 어떤 것들이 있나요?</summary>
<div markdown="1">
답변을 적어주세요
</div>
</details>
<br>
