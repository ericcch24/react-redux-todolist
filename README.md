# React Todo List

以 React 實作的 Todo List，並以 Redux 儲存需要共用的 state。

[Todo List 連結](https://ericcch24.github.io/w23-react-redux-todolist/)

![](https://i.imgur.com/IjbSdVw.png)

## 功能說明

- 新增 todo
- 刪除 todo
- 標記已完成 / 未完成，其中已完成的 todo 會畫線
- 清空全部 todo
- 篩選 todo，分別顯示全部、未完成、已完成的 todo

## 使用工具

- React: 以 function component + hooks 的方法實作。
- Redux: filter 與 todos 的 state 儲存於 Redux store，篩選與 todo 相關功能使用 dispatch action 方法。
- styled components: React component 的樣式製作。
