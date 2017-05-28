# HolidayDateTime
A php class to check Japanese holiday and weekend. 土日祝日を判定するphpクラス。

## Usage

```
$date = new HolidayDateTime("2017-05-28");
$date->holiday();//"日"
```

It will return false if the date is not a holiday or weekend and return the name of holiday or weekend if it is.
