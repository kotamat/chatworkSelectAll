# chatworkSelectAll
チャットワーク全選択すると、画面一杯にtoが表示されうざったいと思ってる君！
下のコードをブックマークレットに登録するといいことあるよ

```javascript
javascript:(function(){c=document.getElementById("_toListSelectAll");c.click();a=document.getElementById('_chatText');a.value=a.value.replace(/%20.*\n/g,'');})()
```
