# HolidayDateTime
A php class to check Japanese holiday and weekend. 土日祝日を判定するphpクラス。

## Usage

```
$date = new HolidayDateTime("2017-05-28");
$date->holiday();//"日"
```

It will return false if the date is not a holiday or weekend and return the name of holiday or weekend if it is.

## Referenced
[祝日を自動判定するDateTime拡張クラス](http://qiita.com/chiyoyo/items/539dc2840a1b70a8e2c3)

[DateTime クラスのまとめメモ](http://qiita.com/re-24/items/c3ed814f2e1ee0f8e811)