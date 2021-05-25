# GitHubのREADME.mdで使用できる画像の装飾

## ショートカットを表す場合

Mac : <kbd>⌘</kbd> + <kbd>R</kbd>  
Windows : <kbd>Ctrl</kbd> + <kbd>R</kbd>

## 中央寄せ
```markdown
<div align="center">
    <img src="images/heroku_cli_01.png" alt="alt" width="80%">
</div>
```
<div align="center">
    <img src="images/heroku_cli_01.png" alt="alt" width="80%">
</div>

<br>

## 枠
幅を指定すると隙間が気になる
- listでやる
    ```markdown
    |<img src="images/heroku_cli_01.png" alt="alt" width="80%">|
    |:-:|

    |<img src="images/heroku_cli_01.png" alt="alt" width="100%">|
    |:-:|
    ```
    |<img src="images/heroku_cli_01.png" alt="alt" width="80%">|
    |:-:|

    |<img src="images/heroku_cli_01.png" alt="alt" width="100%">|
    |:-:|

    <br>

- kbd
    ```markdown
    <kbd><img src="images/heroku_cli_01.png" alt="alt" width="80%"></kbd>
    <kbd><img src="images/heroku_cli_01.png" alt="alt" width="100%"></kbd>
    ```
    <kbd><img src="images/heroku_cli_01.png" alt="alt" width="80%"></kbd>
    <kbd><img src="images/heroku_cli_01.png" alt="alt" width="100%"></kbd>

    <br>
    

## 使えなかった
### styleタグ
```markdown
<style>
img {
    border: 1px red solid;
}
</style>
<img src="images/heroku_cli_01.png" alt="alt" border="1px">
```
