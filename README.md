# input-dates tag

- 日付複数選択コンポーネント
- [サンプルアプリ](https://code4fukui.github.io/input-day/)

<img src=https://user-images.githubusercontent.com/1715217/122636184-cd656680-d122-11eb-8ca3-a4808ca5398a.png width=300>

```
<script type="module" src="https://code4fukui.github.io/input-dates/input-dates.js"></script>
<input-dates id="inputdates"></input-dates>

<script type="module">
inputdates.value = "2021-06-19,2021-06-18";
inputdates.onchange = () => {
  console.log(inputdates.value);
};
</script>
```

## reference

- ベースレジストリ、[行政基本情報データ連携モデル 日付及び時刻](https://github.com/code4fukui/BaseRegistry/blob/main/%E8%A1%8C%E6%94%BF%E5%9F%BA%E6%9C%AC%E6%83%85%E5%A0%B1%E3%83%87%E3%83%BC%E3%82%BF%E9%80%A3%E6%90%BA%E3%83%A2%E3%83%87%E3%83%AB-%E6%97%A5%E4%BB%98%E5%8F%8A%E3%81%B3%E6%99%82%E5%88%BB.md)

## lib

- [day-es](https://github.com/code4fukui/day-es/)
