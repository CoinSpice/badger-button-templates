# Badger Button Templates

## How to use it

There are 2 to 3 steps to follow to set up the Badger Button donation button.

Step one is including the Badger Wallet JavaScript file into your website, right at the end of the code, before the closing body tag (```</body>```).

```html
<!-- insert this at the end of the page before the closing body tag -->
<script src="https://badgerwallet.cash/button.js"></script>
```

Step two is inserting one or more buttons in your page. Edit the field ```data-to``` and insert your BCH address and the field ```data-satoshi``` with the amount you want to receive (in satoshis).

```html
<!-- insert the button anywhere -->
<button class="badger-button" data-to="bitcoincash:qq6e3seenwkhjqv88vavrlpfy7wc6mrzt5xqu0w5ch" data-satoshis="1000"><span>Donate 1000 satoshis</span></button>
```

Optional step three is to customize the style of your button using CSS.

```css
.badger-button {
  /* your styling here */
}
```