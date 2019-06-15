# Zadanie dodatkowe

Napisz funkcję, która generuję tagi języka HTML.
```
>> tag("br")
"<br />"
>> tag("p", "content")
"<p>content</p>"
>> tag("p", "content", "content2")
"<p>content</p><p>content2</p>"
>> tag("img", src="example.org/img.png")
<img src="example.org/img.png" />
>> tag("p", "content", "content2", title="Content")
<p title="Content">content</p><p title="Content">content2</p>
```