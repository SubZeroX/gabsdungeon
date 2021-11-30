---
tags:
  - Anki
---

# Método 1
+ ![](https://i.imgur.com/Wo3KZAj.png)
+ Vá em "Gerenciar tipos de notas"
	+ ![](https://i.imgur.com/2el4rze.png)
+ Escolha o tipo de nota que você usa e clique em "Cartões"
	+ ![](https://i.imgur.com/5livS5I.png)
+ Cole o código no "Verso"
	+ ![](https://i.imgur.com/kXhHdC0.png)

> Downside é que não funciona no back

```js
<script>try{try{document.querySelector(".replaybutton").innerHTML="\ud83d\udd0a"}catch{document.querySelector(".replay-button").innerHTML="\ud83d\udd0a"}}catch{}</script>
```

# Método 2
+ Adicione isso ao Style:

```css
.replay-button svg { 
display:none; 
}
.replay-button:before { 
content: '🔊'; 
}
```