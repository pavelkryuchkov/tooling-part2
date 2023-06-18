# Использование Chrome DevTools - анализ открытия сайта

## 1. Вкладка Network

Профиль загрузки находится в папке assets.

#### Дублирование ресурсов:

<img src="./images/network-1.png" style="width:700px;" />
<img src="./images/network-2.png" style="width:700px;" />
<img src="./images/network-3.png" style="width:700px;" />
<img src="./images/network-4.png" style="width:700px;" />
<img src="./images/network-5.png" style="width:700px;" />

#### Медленно загружающиеся ресурсы:

<img src="./images/network-6.png" style="width:700px;" />
<img src="./images/network-7.png" style="width:700px;" />


## 2. Вкладка Performance

Профиль загрузки находится в папке assets.

Время от начала навигации до событий

  -  First Paint (FP): 1512.2 ms
  -  First Contentful Paint (FCP): 1512.2 ms
  -  Largest Contentful Paint (LCP): 8178.7 ms
  -  DOM Content Loaded (DCL): 6231.0 ms
  -  Load: 13005.7 ms

Событие LCP происходит на элементе `img.contentImage__image`.

<img src="./images/performance-1.png" style="width:400px;" />


## 3. Вкладка Coverage


<img src="./images/coverage-1.png" style="width:700px;" />

Объём неиспользованного CSS: 548 kB

<img src="./images/coverage-2.png" style="width:700px;" />

Объём неиспользованного JS: 2.3 MB (2355kB)

<img src="./images/coverage-3.png" style="width:700px;" />
