# 前端面試寶典


## Introduction

## HTML

1. HTML的重要性與作用
2. HTML5 相較 HTML4 的新特性
3. `<meta>` 標籤的用途
4. `<div>` vs `<span>`
5. `<img>`的 alt 屬性
6. 語義化 HTML 元素
7. 語意化標籤的目的為何
7. `data-*` 屬性用途
8. HTML VS XHTML 差異
9. `<fieldset>` / `<legend>`
10. 什麼是自閉合標籤
11. 常見的 HTML 表單屬性有哪些？
12. 如何建立一個可訪問性的網頁？
13. 如何提升 HTML 文件的SEO ?
14. `<header>`和`<nav>`有什麼差異？使用時機？

## CSS

好的，這是一份根據您提供的筆記內容，將 CSS 前端面試題目進行主題分類的列表：

**CSS 基礎概念**

1. CSS 的主要優勢？如何提升可維護性與效率？
2. CSS 盒模型與 box-sizing
3. 常見選擇器與優先順序
4. 請解釋 CSS 盒模型（Box Model）
5. inline、internal、external CSS 的差異

**排版與佈局**

6. position 屬性的四種模式與應用
7. Flexbox 概念與屬性
8. CSS Grid vs Flexbox
9. 如何水平垂直置中 `<div>`？至少兩種方法
10. Flex vs Grid 有什麼差異？什麼時候該用哪一個？

**單位與響應式設計**

11. rem vs em 的差異與作用
12. 什麼是響應式設計？媒體查詢的作用？
13. Container Queries 是什麼？與 Media Queries 差異？

**進階與現代 CSS**

14. CSS 預處理器（Sass/LESS）概念與核心功能
15. 什麼是 CSS-in-JS？Styled Components vs Emotion 比較
16. 偽類 vs 偽元素 差異與應用

**性能與除錯**

17. 如何優化大型 CSS 的性能與維護性？
18. 如何避免圖片失真？有什麼習慣？
19. Mobile 版型有狀況時如何除錯？


## Javascript

好的，這是一份根據您提供的筆記內容，將 JavaScript 前端面試題目進行主題分類的列表：

**數據類型**

1. JS 的七種基本資料型別 + 一種引用型別
2. == vs === 的差異與推薦使用時機
3. undefined、null 、 not defined、NaN和undeclared 的差異？
4. var / let / const 差異
5. 什麼是提升（Hoisting）？let/const 怎麼處理？
6. 在 JavaScript 中 0.1 + 0.2 會是多少？為什麼？如何避免相關問題？
7. 嚴格模式 (use strict) 的用途？有什麼好處？

**複雜數據類型**

8. 什麼是this? this 在不同上下文中的行為
9. 原型鏈與繼承機制
10. 在 JavaScript 中，Map 與 object 的差別？為什麼有 object 還需要 Map？
11. 請解釋 Set、Map、WeakSet 和 WeakMap 的區別？
12. ES6 中的 class 是什麼？和函式構造函式差別是什麼？

**函式**

13. 什麼是閉包（Closure）？應用範例？
14. 什麼是箭頭函式 (Arrow Function)？跟一般的函式有什麼差別？
15. JavaScript 立即調用函式 IIFE (Immediately Invoked Function Expression) 是什麼？優缺點是什麼？
16. 什麼是高階函式 (Higher order function)？使用高階函式有什麼好處？

**DOM**

17. 事件委託（Event Delegation）是什麼？
18. 請解釋事件的「捕獲與冒泡」機制？如何阻止冒泡？
19. 什麼是 JavaScript 模組化？它的好處？
20. call by value vs call by reference 差異？
21. 為什麼推薦用 structureClone 在 JavaScript 做深拷貝?

**異步函數**

22. 請說明瀏覽器中的事件循環 (Event Loop)
23. async/await 的原理與與 Promise 的比較？
24. Promise 是什麼？有什麼用途？
25. Promise.race 是什麼？如何實踐 Promise.race？
26. Micro-task vs Marcro-task
27. 最常見的事件循環 (Event Loop) 面試題目彙整

### Typescript

28. 2023 Advent of TypeScript 第一到五題詳解

### Javascript手寫題

**原理**

29. JsonP
30. Promise
31. PromiseAll
32. DeepClone

**性能**

34. Debounce
35. Throttle
36. Curry

**數組**

37. flatten
38. unique

**字符串**

40. Trim
41. Camel Case to Pascal Case

**數學**

42. pi calculation
43. quick sort

**演算法**

44. 最长递增子序列
45. Merge

## React

**Context API**

1. useContext 的作用是什麼？它如何解決 prop drilling？

**Refs**

2. useRef 的作用是什麼？常見用途？

**Performance Optimization**

3. React.memo 的作用是什麼？何時使用？
4. 如何優化 React 應用程式的性能？請列舉常見策略。
5. 什麼是 Code Splitting？在 React 中如何實現？
6. 什麼是 Lazy Loading？在 React 中如何實現？
7. 如何處理大型列表的性能問題？（如使用 react-window, react-virtualized）

**Error Handling**

8. 如何在 React 中處理錯誤？什麼是 Error Boundaries？
9. Error Boundaries 的限制有哪些？

**Testing**

10. 如何測試 React 組件？請說明常見的測試工具（如 Jest, React Testing Library）。
11. 什麼是單元測試（Unit Testing）？什麼是整合測試（Integration Testing）？在 React 中如何應用？

**State Management**

12. 除了 React 內建的 Context API 和 useReducer，還有哪些狀態管理工具？（如 Redux, Zustand, Recoil）
13. 請說明 Redux 的核心概念（Store, Reducer, Action）。
14. Redux Toolkit (RTK) 解決了 Redux 的哪些痛點？
15. 什麼是資料流（Data Flow）？請比較單向資料流與雙向資料流。

**Styling in React**

16. 在 React 中有哪些常見的樣式處理方法？（如 CSS Modules, Styled Components, Emotion, Tailwind CSS）
17. 請比較 CSS Modules 和 Styled Components 的優缺點。

**Advanced Concepts**

18. 什麼是 Higher-Order Components (HOCs)？請舉例說明。
19. HOCs 有哪些缺點？Hooks 如何改進？
20. 什麼是 Render Props？請舉例說明。
21. 什麼是 Portals？何時使用 Portals？
22. 什麼是 Concurrent Mode？它解決了什麼問題？
23. 什麼是 Suspense？它有什麼用途？

**Server-Side Rendering (SSR)**

24. 什麼是 Server-Side Rendering (SSR)？它與 Client-Side Rendering (CSR) 有何不同？
25. SSR 的優點和缺點分別是什麼？
26. 在 React 中如何實現 SSR？（如使用 Next.js）

**Next.js**

27. 什麼是 Next.js？它提供了哪些功能？
28. 請說明 Next.js 中的 Pages Router 和 App Router 的差異。
29. 什麼是 Static Site Generation (SSG) 和 Server-Side Rendering (SSR)？在 Next.js 中如何選擇？
30. 什麼是 Incremental Static Regeneration (ISR)？

**TypeScript with React**

31. 如何在 React 專案中使用 TypeScript？
32. 請說明常見的 React 組件 TypeScript 型別定義（如 FunctionComponent, FC）。

**Design Patterns**

33. 在 React 開發中，有哪些常見的設計模式？

**Best Practices**

34. 在開發 React 應用程式時，有哪些推薦的最佳實踐？
35. 如何編寫可讀性高且易於維護的 React 組件？

## Git & Github


**Git 基礎觀念**

1. `git push origin master` 這個指令是在做些什麼事？
2. 請說明 `git clone`、`git fetch` 跟 `git pull` 這三個指令有什麼不同？
3. Git 裡的 HEAD 是什麼東西？
4. 合併過的分支你通常會怎麼處理？為什麼？
5. 刪除已經合併過的分支會發生什麼事？
6. `git diff` 這個指令是做什麼用的？
7. 在使用 Git 的時候，你通常會怎麼使用標籤（Tag）？
8. 你有在 GitHub 上用過 `fork` 這個功能嗎？它跟 `git branch` 指令有什麼不同？
9. 用一般方式的合併，跟使用 `rebase` 方式合併，有什麼不同？各有何優缺點？
10. 合併發生衝突（Conflict）的時候，你會怎麼處理？
11. 試說明 `git checkout SHA1`、`git reset SHA1` 以及 `git revert SHA1` 這三個指令有什麼不同？

**Git 狀況題與除錯**

12. 如果不小心把還沒合併的 develop 分支刪掉了，該怎麼辦？
13. 不小心用 `git reset --hard` 指令把檔案處理掉了，有機會救回來嗎？
14. 你什麼時候會使用 `git cherry-pick` 指令？該怎麼使用？
15. 在專案中可能有些比較敏感或內容比較機密的檔案（例如 `/config/database.yml`），在使用 Git 時，你通常會怎麼處理這類型內容比較敏感的檔案？
16. 想要知道這行程式碼是誰寫的？
17. 你用過 `git push -f` 指令嗎？在什麼情境下用的？
18. 在團隊一起工作的時候，如果你推了一個 commit 到大家一起共同的地方，你發現這個 commit 有問題想取消它，你會怎麼做？
19. 如果你正在某個分支進行開發，突然被老闆叫去修別的問題，這時候你會怎麼處理手邊的工作？
20. 如何把好幾個 Commit 合併成同一個？
21. 假設某位平常沒在用 Git 的主管跟你說：「你可以把剛剛那批更新的檔案給我嗎？」，你會怎麼做？
22. 空的目錄無法被加入 Git 版控，如果這個目錄是個重要的目錄一定要放進 Git 版控的話，你會怎麼處理？
23. 要怎麼從過去的某個時間點的 Commit，再開一個新的分支執行新任務？
24. 當執行 `git push` 指令之後出現這個訊息是什麼意思？又該如何解決？
25. 有時候回到過去的某個時間點的 Commit 的時候會看到這個訊息是什麼意思？又該如何解決？
26. 有時候在切換分支的時候會看到這個訊息，然後沒辦法順利的切換分支，這時該怎麼解決？
27. 剛剛把 `feature/develop` 這個分支合併到 `master` 分支，該怎麼取消剛剛這次的合併呢？
28. 剛剛把 `feature/develop` rebase 到了 `master` 分支，該怎麼取消剛剛這次的 rebase 動作？
29. 如果你發現某位豬隊友使用了 git push -f 把線上的東西蓋掉了，該怎麼辦？

## Software engineering

## Sources
