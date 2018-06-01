# JavaScript

## 面向对象

```JavaScript

let pageRecorder = {
  index: 1,
  name: '随意',
  pagecount: 10,
  enable: true,
  nextPage: function() {
    if (this.enable) {
      this.index++;
    }
  },
  sss: function(index) {
    console.log(index);
  }
};
```

如上述代码，创建了一个名为 `pageRecorder`  的对象