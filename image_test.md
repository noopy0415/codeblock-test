# kbdタグあれこれ

## ショートカットを表す場合

Mac : <kbd>⌘</kbd> + <kbd>R</kbd>  
Windows : <kbd>Ctrl</kbd> + <kbd>R</kbd>

## 枠
枠線を付けるのに応用できる
幅を指定すると隙間が気になるけどlistとほぼ同じ使い方でできるかな

- listでやる
    ```markdown
    |<img src="https://image.lgtmoon.dev/93186" alt="alt" width="80%">|
    |:-:|

    |<img src="https://image.lgtmoon.dev/93186" alt="alt" width="100%">|
    |:-:|
    ```
    |<img src="https://image.lgtmoon.dev/93186" alt="alt" width="80%">|
    |:-:|

    |<img src="https://image.lgtmoon.dev/93186" alt="alt" width="100%">|
    |:-:|

    <br>

- kbd
    ```markdown
    <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="80%"></kbd>
    <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="100%"></kbd>
    ```

    <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="80%"></kbd>  
    <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="100%"></kbd>

    <br>

- kbd + センタリング
    ```markdown
    <div align="center">
        <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="80%"></kbd>
    </div>
    <div align="center">
        <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="100%"></kbd>
    </div>
    ```

    <div align="center">
        <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="80%"></kbd>
    </div>
    <div align="center">
        <kbd><img src="https://image.lgtmoon.dev/93186" alt="alt" width="100%"></kbd>
    </div>

    <br>

## 使えなかった
### styleタグ
```markdown
<style>
img {
    border: 1px red solid;
}
</style>
<img src="https://image.lgtmoon.dev/93186" alt="alt" border="1px">
```
