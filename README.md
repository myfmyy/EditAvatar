# EditAvatar


![](https://raw.githubusercontent.com/myfmyy/EditAvatar/master/test/e.png)

![](https://raw.githubusercontent.com/myfmyy/EditAvatar/master/test/ee.png)

```js
//��ʼ��
var editAvatar = new EditAvatar($("#test_edit"));
            
$("#zoomin").click(function () {
    //����ѡ�������С
    editAvatar.cursorResize(true);//�Ŵ�
});
$("#zoomout").click(function () {
    editAvatar.cursorResize(false);//��С
});
//���view
editAvatar.addView($("#test_view_100"));
editAvatar.addView($("#test_view_50"));
editAvatar.addView($("#test_view_30"));
//���input file
editAvatar.getFile($("#getfile"));
$("#get").click(function () {
    //��ȡͼƬ
    console.log(editAvatar.getBase64());
});
//����
editAvatar.create();
```

* demo  [idaylog.com/EditAvatar](https://www.idaylog.com/EditAvatar)