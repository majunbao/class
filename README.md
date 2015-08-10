# keui

NO gulp!  NO SCSS!  NO CoffeeScript!  NO Grunt、Stylus、LESS....!!!!没有封装！！没有新技术！！

一个简约时尚的模块化UI案例

# 模块
一个模块就是一个文件夹，下面我们来新建一个模块试试。

### 新建一个模块

```sh
mkdir button
```

### 删除一个模块

```sh
rm -rf button
```

# 编辑模块
编辑模块就是编辑文件，没了。

### html 文件

```html
<button>按钮</button>

<button class="error">按钮</button>

incloud('button.html')
```

### CSS 文件

```css
button { }

button.error { }

@import button
```

### Javascript 文件

```js
export.button

button.prototype.error

require('button')
```