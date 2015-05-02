## jQuery Timer

��ӭ���״��룬�Լ� [DEMO](#����ʾ��) �� BUG

## ʲô�� jQuery Timer

- ���� jQuery �ļ�ʱ����ȡ�� js ԭ���� setTimeout �� setInterval �Ⱥ�����
- �Ƽ� jQuery ʹ�ã�1.7+��
- �����������Chrome 14+, Safari 5.0+, IE6+, Firefox 3.5+.

## Ŀ¼
* [����](#����)
* [����](#����)
* [��������](#��������)
* [����ʾ��](#����ʾ��)
* [����˵��](#����˵��)
* [������־](#������־)

## ����
* �������µ� jQuery
* �������٣�ʹ�ü򵥱��
* ʵ���ḻ��ѧϰ�ɱ��ϵ�

## ����
* [jquery-timer.js](jquery-timer.js) *(������,3.0kb)*
* [jquery-timer-min.js](jquery-timer-min.js) *(������,0.7kb)*

## ��������
```javascript
//�����Ժ󵯳��Ի���.
$("body").setTimer(function() {
	alert("Hello jQuery Timer!");
});
```

## ����ʾ��
1. [�趨�ӳ�ִ�к�������ʼʹ�ü�ʱ�����](demo/param-fun.html)
2. [�趨�ص����ʱ��](demo/param-time.html)
3. [ָ���ص��Ĵ���](demo/param-iCount.html)
4. [ָ���Ƿ�����ִ��](demo/param-immediately.html)
5. [���ûص����������лص������Ժ���ã�](demo/param-callback.html)
6. [��������ʱ����](demo/pay0.html)
7. [��������������](demo/pay1.html)
8. [��̬��ȡ�ı���ʾʾ��](demo/pay2.html)

## ����˵��

setTimer �������յĿ�ѡ���������ղ���˳���о�

���� | ���� | Ĭ��ֵ | ˵��
------------ | ------------ | ------------ | ------------
fun | Function | $.noop | ��ʱ���ӳ�ִ�еĻص�����������һ����ѡ������ʶ��ǰ�ص�ִ�еĴ�����ͬʱ���ܵڶ��������ɻ��Ŀ�����
time | Number | 2000 | ��ʱ���ص�ʱ������ʱ�䵥λ�Ǻ���
iCount | Number | 1 | ��ʱ���ص�������С����0���������ѭ����ֱ������ stopTimer ��ֹ��������Ϊ 0 ���� -1 ʱ��
immediately | Boolean | false | �Ƿ�����ִ�С�������Ϊ true ʱ����ִ��һ�λص�������
callback | Function | $.noop | ��ʱ��ɺ�Ļص��������ص������ﵽ�����лص���ɺ�ִ�е����ջص�����������ѭ���ص�ʧЧ��

[Project Home](http://wwh447.github.io/jQueryTimer/)

[DEMO](http://wwh447.github.io/jQueryTimer/#%E6%89%80%E6%9C%89%E7%A4%BA%E4%BE%8B)

## ������־
##### v1.0.0 beta
1. ������Ŀ��ʼ����
2. ����˵����ʾ��

