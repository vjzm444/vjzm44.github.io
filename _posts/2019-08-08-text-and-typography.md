---
title: 구름IDE상에서의 커밋 방법
author: Cotes Chung
date: 2019-08-08 11:33:00 +0800
categories: [Blogging, Demo]
tags: [typography]
math: true
image: /assets/img/sample/goormide.jpg
---

-구름IDE상에서의 커밋 방법

https://studioplug.tistory.com/342

 
-현주의 git blog

https://vjzm444.github.io/

 
-구름IDE 작업장

https://ide.goorm.io/


이하글은 나중에 긁은 샘플들

## Titles

---

# H1

<h2 data-toc-skip>H2</h2>

<h3 data-toc-skip>H3</h3>

<h4>H4</h4>

---

## Paragraph

 아니 분명 아까 저 테이블은 없었는데 어디서 생겼지 하고 잘 보니 위에서 체크한 글 정보를 가지고 있는 것 같습니다. 그럼 어떻게 만든건지 확인해봅니다. 수정 버튼을 눌러볼게요

## List

### Ordered list

1. first item
2. second item
3. third item

### Unordered list

- item 1
	- sub item 1
	- sub item 2

- item 2

## Block Quote

> This line to shows the Block Quote.

## Tables

| Company                      | contact          | Country |
|:-----------------------------|:-----------------|--------:|
| Alfreds Futterkiste          | Maria Anders     | Germany |
| Island Trading               | Helen Bennett    | UK      |
| Magazzini Alimentari Riuniti | Giovanni Rovelli | Italy   |

## Link

<http://127.0.0.1:4000>


## Footnote

Click the hook will locate the footnote[^footnote].


## Image

![Desktop View](/assets/img/sample/mockup.png)


## Inline code

This is an example of `Inline Code`.

## Mathematics

The mathematics powered by [**MathJax**](https://www.mathjax.org/):

$$ \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6} $$

When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

## Code Snippet

### Common

```
This is a common code snippet, without syntax highlight and line number.
```

### Specific Languages

#### Console

```console
$ date
Sun Nov  3 15:11:12 CST 2019
```


#### Terminal

```terminal
$ env |grep SHELL
SHELL=/usr/local/bin/bash
PYENV_SHELL=bash
```

#### Ruby

```ruby
def sum_eq_n?(arr, n)
  return true if arr.empty? && n == 0
  arr.product(arr).reject { |a,b| a == b }.any? { |a,b| a + b == n }
end
```

#### Shell

```shell
if [ $? -ne 0 ]; then
    echo "The command was not successful.";
    #do the needful / exit
fi;
```

#### Liquid

{% raw %}
```liquid
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```
{% endraw %}

#### HTML

```html
<div class="sidenav">
  <a href="#contact">Contact</a>
  <button class="dropdown-btn">Dropdown
    <i class="fa fa-caret-down"></i>
  </button>
  <div class="dropdown-container">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
  <a href="#contact">Search</a>
</div>
```

**Horizontal Scrolling**

```html
<div class="panel-group">
  <div class="panel panel-default">
    <div class="panel-heading" id="{{ category_name }}">
      <i class="far fa-folder"></i>
      <p>This is a very long long long long long long long long long long long long long long long long long long long long long line.</p>
      </a>
    </div>
  </div>
</div>
```


## Reverse Footnote

[^footnote]: The footnote source.
