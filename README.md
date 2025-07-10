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

1. React 基礎概念
	1.	React 是什麼？它的核心概念有哪些？
	2.	React 的 Virtual DOM 是什麼？它與真實 DOM 有什麼差別？
	3.	React 為什麼要使用 key？key 有什麼限制與設計原則？
	4.	React 的 reconciliation 機制是什麼？


2. JSX 與元件設計
	1.	JSX 是什麼？它與 HTML 有什麼不同？
	2.	React 元件有哪些種類？Class 與 Function Component 的差異？
	3.	在 JSX 中為什麼不能直接用 if-else？
	4.	React 的元件命名與檔案結構有什麼建議？


3. Props 與 State
	1.	props 和 state 有什麼不同？
	2.	如何在元件中更新 state？需要注意什麼？
	3.	state 更新是同步還是非同步？
	4.	如何處理多層 props 傳遞問題？


4. React Hooks
	1.	React Hooks 是什麼？為什麼出現？
	2.	useState 是什麼？如何使用？
	3.	useEffect 的用途是什麼？會在哪些情境下被呼叫？
	4.	useRef 有什麼用途？常見使用場景有哪些？
	5.	useCallback 與 useMemo 有什麼差別？
	6.	自定義 Hook 要怎麼寫？有什麼限制？


5. 元件生命週期與事件處理
	1.	React 的生命週期分為哪幾個階段？
	2.	useEffect 模擬 componentDidMount 與 componentWillUnmount 的方式是什麼？
	3.	React 中事件處理與原生 DOM 的差別在哪？


6. 元件間溝通與 Context
	1.	如何在 React 中進行元件間溝通？
	2.	props drilling 是什麼？如何避免？
	3.	React 的 Context API 是什麼？適合用在哪些情境？


7. 效能優化與 Re-render
	1.	為什麼 React 會重新渲染元件？有哪些方式可以避免不必要的渲染？
	2.	useMemo 與 useCallback 的使用時機與風險？
	3.	React.memo 是什麼？什麼情況下會使用？


8. React Router 與導航
	1.	React Router 是什麼？怎麼使用？
	2.	BrowserRouter 與 HashRouter 的差異？
	3.	如何在程式中導航到其他頁面？


9. 表單處理與狀態管理
	1.	如何在 React 處理表單資料？
	2.	什麼是 controlled 與 uncontrolled 元件？
	3.	React Hook Form 是什麼？使用情境？
	4.	為什麼需要像 Redux、Zustand 等狀態管理工具？


10. 測試與開發工具
	1.	React 專案常見的測試工具有哪些？
	2.	如何撰寫 React 單元測試？有哪些原則？
	3.	Storybook 是什麼？有什麼實際效益？


11. React 生態系與架構設計
	1.	Next.js 是什麼？它與 React 有什麼差異？
	2.	如何選擇適合的狀態管理工具？
	3.	React 專案如何模組化？常見架構怎麼設計？


12. 實務應用與開發模式
	1.	React 專案中常見的資料流模式是什麼？
	2.	如何設計大型應用的元件架構？
	3.	怎麼做 Error Handling 與 Loading 狀態管理？


13. 其他通識與邏輯題
	1.	React 中 custom prop（例如 <div blahblahblah={true} />）會有什麼結果？為什麼？
	2.	git clone、git pull 和 git fetch 差在哪？
	3.	說明 Git stash 的用途與使用情境？
	4.	說明 Git 分支的作用與多人協作的意義？
	5.	JavaScript 的 microtask 與 macrotask 差異是？


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
