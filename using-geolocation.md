# Използване използване на HTML5 Geolocation

Следния snippet от код ще ви покаже как лесно може да ползвате геолокацията на браузъра във вашите приложения.

```javascript
function showPosition(position) {
    console.log(position.coords.latitude);
    console.log(position.coords.longitude);
}

navigator.geolocation.getCurrentPosition(showPosition);

```
Може да копирате и да поставите горния код в конзолата на браузъра си, за да тествате.

* Fetch-ването на геолокацията може да се забави известно време (до 2-3 секуди), така че го имайте в предвид.
