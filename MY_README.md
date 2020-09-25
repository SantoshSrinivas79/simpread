# MY README

Translation attempt using:


- https://github.com/soimort/translate-shell
- https://github.com/matheuss/google-translate-api
- https://github.com/itsecurityco/to-google-translate
- https://github.com/CocoaDebug/GoogleTranslate
- https://github.com/ssut/py-googletrans
- https://github.com/MoeFE/GoogleTranslate
- https://github.com/xfslove/alfred-google-translate
- https://github.com/googleapis/nodejs-translate
- https://stackoverflow.com/questions/2718196/find-all-chinese-text-in-a-string-using-python-and-regex
- https://github.com/wizyoung/googletranslate.popclipext
- https://chenyuzuoo.github.io/posts/28001/
- https://hotpot.ai/file-translator?s=sidebar
- Replace line in python
    + https://stackoverflow.com/questions/39086/search-and-replace-a-line-in-a-file-in-python
    + https://stackoverflow.com/questions/4719438/editing-specific-line-in-text-file-in-python/39676548
    + https://kaijento.github.io/2017/05/28/python-replacing-lines-in-file/
    + https://www.reddit.com/r/Python/comments/464cim/replace_a_line_in_a_txtfile/


```py
import re
s = u'new Notify().Render( "已加入到延迟加载。" );'

for n in re.findall(r'[\u4e00-\u9fff]+', s):
    print(n)
```