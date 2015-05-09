# Input_Tag
自動補完でタグを選択入力できるjQueryプラグイン

[DEMO](http://iritec.github.io/Input_Tag/)

![Alt text](sample.png)

## 使い方
### jQueryとjQuery UI、CSSを読み込む
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/jquery-ui.min.js"></script>
    <link rel="stylesheet" href="style.css">

### タグ入力表示部分
    <div id="tagwaku">
      <div id="tags"></div>
      <input type="text" id="tag-input">
      <input type="hidden" name="skills" id="skills">
    </div>

### 自動補完の選択肢を配列に保存
    <script>
    var dataTags = [
    "日本",
    "Iceland",
    "Ireland"
    ];
    </script>
    
### Input_Tagを読み込む
    <script src="input_tag.js"></script>
    
## 選択されたタグについて
    <input type="hidden" name="skills" id="skills">
にカンマ区切りで入力されます。
