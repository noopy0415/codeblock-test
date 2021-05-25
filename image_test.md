# GitHubのREADME.mdで使用できる画像の装飾

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
```markdown
|<img src="images/heroku_cli_01.png" alt="alt">|
|:-:|
```
|<img src="images/heroku_cli_01.png" alt="alt">|
|:-:|

<br>

```markdown
<kbd><img src="images/heroku_cli_01.png" alt="alt"></kbd>

```
<kbd><img src="images/heroku_cli_01.png" alt="alt"></kbd>

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
