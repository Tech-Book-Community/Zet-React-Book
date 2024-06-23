# 《React 思維進化》讀書會第一組

<table>
  <tr>
    <th>日期</th>
    <th>章節</th>
    <th>導讀人</th>
    <th>筆記工</th>
    <th>Slide</th>
    <th>Note</th>
  </tr>
  <tr>
    <td>2024/2/18</td>
    <td>
      2-1 DOM 與 Virtual DOM </br>
      2-2 建構畫面的最小單位：React element </br>
      2-3 Render React element (31)
    </td>
    <td>Lois</td>
    <td>Aya</td>
    <td><a href="https://hackmd.io/YuqYjrh6SMiDY-maqGWqmg#/">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Zet-React-Book/discussions/12">Note</a></td>
  </tr>
  <tr>
    <td>2024/03/03</td>
    <td>
      2-4 JSX 根本就不是在 JavaScript 中寫 HTML </br> 
      2-5 JSX 的語法規則脈絡與畫面渲染的實用技巧 (38)
    </td>
    <td>玄米</td>
    <td>William</td>
    <td><a href="https://docs.google.com/presentation/d/1Ad6zmtKFbI-DczCELsPEUJTwQ4n_8pONqVmsXitWKWk">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Zet-React-Book/discussions/16">Note</a></td>
  </tr>
  <tr>
    <td>2024/03/17</td>
    <td>
      2-6 單向資料流與一律重繪渲染策略 </br>
      2-7 畫面組裝的藍圖：component 初探(55)
    </td>
    <td>Aya</td>
    <td>Lois</td>
    <td><a href="">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Zet-React-Book/discussions/17">Note</a></td>
  </tr>
  <tr>
    <td>2024/03/31</td>
    <td>
      2-8 React 畫面更新的發動機：state 初探 </br>
      2-9 React 畫面更新的流程機制：reconciliation(30)
    </td>
    <td>Steven</td>
    <td>Yo0</td>
    <td><a href="https://hackmd.io/@stevenchang421/B1QCgIUk0">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Zet-React-Book/discussions/22">Note</a></td>
  </tr>
  <tr>
    <td>2024/04/14</td>
    <td>
      3-1 如何在子 component 裡觸發更新父 component 的資料 </br>
      3-2 深入理解 batch update 與 updater function(31)
    </td>
    <td>William</td>
    <td>Steven</td>
    <td><a href="https://gamma.app/docs/React-3-1-3-2-lzmmxy2uwpvhzdz">Slide</a></td>
    <td><a href="">Note</a></td>
  </tr>
  <tr>
    <td>2024/04/28</td>
    <td>
      3-3 維持 React 資料流可靠性的重要關鍵：immutable state </br>
      3-4 Immutable update(30)
    </td>
    <td>Evonne</td>
    <td>玄米</td>
    <td><a href="https://drive.google.com/file/d/18bSkZBUfCKgAHim7kXcmrq_Wwfnt1zgS/view?usp=sharing">Slide</a></td>
    <td><a href="">Note</a></td>
  </tr>
  <tr>
    <td>2024/05/12</td>
    <td>
      4-1 Component 的生命週期 </br> 
      4-2 Function component 與 class component 關鍵區別 </br>
      4-3 每次 render 都有自己的 props、state 與 event handler 函式(30)
    </td>
    <td>Kai</td>
    <td>Evonne</td>
    <td><a href="https://docs.google.com/presentation/d/1-Qjit2Qjo3ffKXPWI8e6uv-FefWDW5dAT3uYl9vY46s/edit#slide=id.g2710f8a2103_0_272">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Zet-React-Book/discussions/32">Note</a></td>
  </tr>
  <tr>
    <td>2024/05/26</td>
    <td>
      5-1 React 中的副作用處理：effect 初探 </br>
      5-2 useEffect 其實不是 function component 的生命週期 API(35)
    </td>
    <td>Yo0</td>
    <td>Willy</td>
    <td><a href="https://hackmd.io/@yG0XWIa8QgGITxdROQeX1w/vita-useEffect#/">Slide</a></td>
    <td><a href="https://github.com/Tech-Book-Community/Zet-React-Book/discussions/37">Note</a></td>
  </tr>
  <tr>
    <td>2024/06/09</td>
    <td>
      5-3 維護資料流的連動：不要欺騙 hooks 的 dependencies(29)
    </td>
    <td>Lai</td>
    <td>Vita</td>
    <td><a href="https://docs.google.com/presentation/d/1SYxv-BzwdPzaQC3oON--x-SK2cUH-ezJVitPLDDyoro/edit?usp=sharing">Slide</a></td>
    <td><a href="">Note</a></td>
  </tr>
  <tr>
    <td>2024/06/23</td>
    <td>
      5-4 React 18 的 effect 函式在 mount 時為何會執行兩次？ </br>
      5-5 副作用處理的常見情境設計技巧(31)
    </td>
    <td>Willy</td>
    <td>Lai</td>
    <td><a href="https://docs.google.com/presentation/d/16NZJthlK9NKQ1C2XjTXauZM8U20QGtvhiiUuTaCvRbY/edit#slide=id.g2e79cf95692_0_1">Slide</a></td>
    <td><a href="">Note</a></td>
  </tr>
  <tr>
    <td>2024/07/07</td>
    <td>
    5-6 useCallback 與 useMemo 的正確使用時機 </br>
    5-7 Hooks 的運作原理與設計思維(16)
    </td>
    <td>Vita</td>
    <td>Kai</td>
    <td><a href="">Slide</a></td>
    <td><a href="">Note</a></td>
  </tr>
</table>
