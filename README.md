# Floating Button

A collection of HTML and CSS snippets for creating floating action buttons on your website. You can add buttons for Messenger and WhatsApp with customizable styles.

## Messenger (HTML & CSS & Font Awesome)

```html
<style>
  .float {
  position: fixed;
  width: 60px;
  height: 60px;
  bottom: 20px;
  right: 20px;
  background-color: #168AFF;
  color: #FFF;
  border-radius: 50px;
  text-align: center;
  font-size: 30px;
  box-shadow: 2px 2px 3px #999;
  z-index: 100;
  }
  .my-float {
  margin-top: 16px;
  }
</style>
<a href="https://m.me/12345671234567" class="float">
  <i class="fa-brands fa-facebook-messenger my-float"></i>
</a>
```

## WhatsApp (HTML & CSS & Font Awesome)

```html
<style>
  .float {
  position: fixed;
  width: 60px;
  height: 60px;
  bottom: 20px;
  right: 20px;
  background-color: #25d366;
  color: #FFF;
  border-radius: 50px;
  text-align: center;
  font-size: 30px;
  box-shadow: 2px 2px 3px #999;
  z-index: 100;
  }
  .my-float {
  margin-top: 16px;
  }
</style>
<a href="https://web.whatsapp.com/send?phone=1231234567" class="float">
  <i class="fa fa-brands fa-whatsapp my-float"></i>
</a>
```

## Messenger (Bootstrap & Font Awesome)

```html
<a href="https://web.whatsapp.com/send?phone=1231234567" class="position-fixed bottom-0 end-0 mb-3 me-3 text-white rounded-circle d-flex justify-content-center align-items-center shadow" style="background-color: #075E54; width: 60px; height: 60px; font-size: 30px; z-index: 100;">
  <i class="fa fa-brands fa-facebook-messenger"></i>
</a>
```

## WhatsApp (Bootstrap & Font Awesome)

```html
<a href="contact.html" class="position-fixed bottom-0 end-0 mb-3 me-3 text-white rounded-circle d-flex justify-content-center align-items-center shadow" style="background-color: #25d366; width: 60px; height: 60px; font-size: 30px; z-index: 100;">
  <i class="fa fa-brands fa-whatsapp my-float"></i>
</a>
```

## Support (Bootstrap & Font Awesome)

```html
<a href="https://web.whatsapp.com/send?phone=1231234567" class="position-fixed bottom-0 end-0 mb-3 me-3 bg-primary text-white rounded-circle d-flex justify-content-center align-items-center shadow" style="width: 60px; height: 60px; font-size: 30px; z-index: 100;">
  <i class="fa fa-solid fa-headset"></i>
</a>
```
