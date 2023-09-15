# What happens to my lang attribute ?
An inventory of the lang attribute across different email boxes


This small repository aims to record the attitude of the lang attribute across all available mailboxes.

We start with a simple example. We indicate the attribute in three different places:

-the html tag
-the body tag
-a wrapping div

We also add the xml:lang="" attribute because the question is whether this attribute is useful or not for Outlook

```
<html lang="es" xml:lang="es" 
<body lang="es" xml:lang="es">
<center lang="es" xml:lang="es">
```


| Email Client  |  html         | body          | center|
| ------------- | ------------- | ------------- | -------------|
| Outlook 2021  | ------------- | &lt;body lang="EN-US"&gt; | -------------|
| Outlook 2019  | ------------- | &lt;body lang="EN-US"&gt; | -------------|
|Office 365 (win 11) | ------------- | &lt;body lang="EN-US"&gt; | -------------|
| Outlook 2016 | ------------- | &lt;body lang="EN-US"&gt; | -------------|
| Outlook 2013 | ------------- | &lt;body lang="EN-US"&gt; | -------------|
| ------------- | ------------- | ------------- | -------------|
| iphone 11 Gmail  | &lt;html&gt; | &lt;div lang="es"&gt; | &lt;center lang="es"&gt;|
| iphone 12 Gmail iOS 14 dark  |&lt;div lang="es"&gt; | &lt;center lang="es"&gt;|
| ------------- | ------------- | ------------- | -------------|
| iphone 14 Gmail iOS 16 dark  | &lt;html lang="es" xml:lang="es"&gt; | &lt;body lang="es" xml:lang="es"&gt; | &lt;center lang="es" xml:lang="es"&gt;|
| iphone 14 plus iOS 16 dark  | &lt;html lang="es" xml:lang="es"&gt; | &lt;body lang="es" xml:lang="es"&gt; | &lt;center lang="es" xml:lang="es"&gt;|
|iphone 14 iOS 16 Pro Max | &lt;html lang="es" xml:lang="es"&gt; | &lt;body lang="es" xml:lang="es"&gt; | &lt;center lang="es" xml:lang="es"&gt;|
| ------------- | ------------- | ------------- | -------------|
|iphone 13 Pro Max iOS 15  |  N/A | N/A |  N/A|
| iPad Air (Gen 4) iOS 15  | N/A | N/A |  N/A|
|iPhone 13 iOS 15 | N/A | N/A |  N/A|
| iPhone 12 Pro Max iOS 14| N/A | N/A |  N/A|
| iPhone 12 Pro iOS 14 | N/A | N/A |  N/A|
|iPhone 12 iOS 14 (force dark) | N/A | N/A |  N/A|
| iPhone 12 Mini - iOS 14| N/A | N/A |  N/A|
| iPhone XE iOS 14 | N/A | N/A |  N/A|
| iPhone SE (Gen 2) iOS 14 | N/A | N/A |  N/A|
| ------------- | ------------- | ------------- | -------------|
|Android 11 Gmail Pixel 4  | &lt;html&gt;  |&lt;div lang="es"&gt;  | &lt;center lang="es"&gt;  |
| ------------- | ------------- | ------------- | -------------|
| Samsung Mail - S20 Android  | &lt;html lang="es" xml:lang="es"&gt; | &lt;body lang="es" xml:lang="es"&gt; | &lt;center lang="es" xml:lang="es"&gt;|
|Samsung Mail - A10 Android | &lt;html lang="es" xml:lang="es"&gt; | &lt;body lang="es" xml:lang="es"&gt; | &lt;center lang="es" xml:lang="es"&gt;|
| ------------- | ------------- | ------------- | -------------|
| Gmail - Chrome | &lt;html&gt; | &lt;div lang="es"&gt; | &lt;center lang="es"&gt; |
| Google Workspace - Chrome | &lt;html&gt; | &lt;div lang="es"&gt; | &lt;center lang="es"&gt; |
| T-Online Chrome | &lt;html&gt; | &lt;body&gt; | &lt;center lang="es"&gt; |
| ------------- | ------------- | ------------- | -------------|
| Web.de | &lt;html&gt; | &lt;body&gt; | &lt;center&gt; |
| GMX Chrome | &lt;html&gt; | &lt;body&gt; | &lt;center&gt; |
| ------------- | ------------- | ------------- | -------------|
| Freenet.de | N/A | N/A | N/A |
| ------------- | ------------- | ------------- | -------------|
| Outlook Chrome | &lt;html&gt; | &lt;html&gt; | &lt;div lang="es"&gt; | &lt;center lang="es"&gt; |
| Outlook Chrom dark | &lt;html&gt; | &lt;html&gt; | &lt;div lang="es"&gt; | &lt;center lang="es"&gt; |
| Office 365 Chrome | &lt;html&gt; | &lt;html&gt; | &lt;div lang="es"&gt; | &lt;center lang="es"&gt; |
| ------------- | ------------- | ------------- | -------------|
|Zimbra  | &lt;html&gt; | &lt;body lang="es" xml:lang="es"&gt; | &lt;center lang="es" xml:lang="es"&gt;|
| ------------- | ------------- | ------------- | -------------|
| Mai.ru | &lt;html lang="en_US"&gt; | N/A | &lt;center lang="es"&gt; |
| ------------- | ------------- | ------------- | -------------|
| Yandex | &lt;html&gt; | &lt;div lang="es"&gt; | &lt;center lang="es"&gt; |
| ------------- | ------------- | ------------- | -------------|
| Yahoo/ AOL  | &lt;html&gt; | N/A | &lt;center lang="es"&gt; |
| ------------- | ------------- | ------------- | -------------|
| Libero | &lt;html lang="en"&gt; | N/A | &lt;center&gt; |
| ------------- | ------------- | ------------- | -------------|
| Wall!Mail | &lt;html lang="en"&gt; | N/A |  &lt;center lang="es"  xml:lang="es"&gt; |
| ------------- | ------------- | ------------- | -------------|
| Ceznam | &lt;html lang="cz"&gt; | &lt;div lang="un"&gt; |  &lt;center lang="es"&gt; |













