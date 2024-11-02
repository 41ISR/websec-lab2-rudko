# Payloads для gruyere

`</div></td></tr></tbody></table><img src="" onerror=alert("1")>`
## Example Payload

При переходе по ссылке `https://example.com/example`. Параметр `example` можно заменить на пейлоад `<script>alert(document.cookies)</script>` для выполнения Reflected XSS инъекции в элементе `<div id="search-query-param">...</div>`, который покажет куки файлы пользователя

## Payload 1

На странице `/newsnippet`. В `Snippet content` можно написать `<img src="" onerror=alert("1")>` для выполнения Stored XSS инъекции в элементе `/snippets <div id="content">`. 
PS Он работает на главной тоже!

## Payload 2

На странице `/editprofile`. В `Private Snippet` можно написать `<img src="" onerror=alert("1")>` для выполнения Stored XSS инъекции в элементе `/ <div id="private snippets">`.



## Payload 3

На странице `/upload`. В `Upload` можно загрузить `payload2.html` для выполнения Stored XSS инъекции в элементе `/ <div id="private snippets">`.
Я позорный позор и глянул подсказку.. А ТАМ РЕАЛЬНАЯ ПОДСКАЗКА!

