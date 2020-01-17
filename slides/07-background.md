import { Card } from '@fusuma/client';

<Card
  left={
    <>
      <img src="../images/react.png" width="250px" />
      <h2>React.js</h2>
      <br />
      <li>チーム初導入</li>
      <li>国際的なシェアが多い</li>
      <li>独特な記法</li>
      <li>Vue.jsに比べると学習効率は高い</li>
    </>
  }
  right={
    <>
      <img src="../images/vue.jpg" width="250px" />
      <h2>Vue.js</h2>
      <br />
      <li>現在チーム内すべてのWebアプリで使われている</li>
      <li>React.jsや他のライブラリと比べると学習コストが低い</li>
      <li>描画とロジックが別れていて、デザイナーやHTMLコーダーでも触りやすい</li>
      <li>日本での導入事例が多く日本語でのドキュメントが充実している</li>
    </>
  }
/>