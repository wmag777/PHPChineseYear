# PHPChineseYear

## Compatible with PHP v.8.0 ++
If your project on below PHP v.8.0, use "switch" construction instead of "match"

Ready PHP class to get name of Chinese Year - Enjoy!

To use it in your project, use this class in your file and initiate it like this: <br><br>

<code>use ChinaHoroscope;
$horoscope = new ChinaHoroscope;
$horoscope->getNameByUnknownDate($date);</code>


<br><br>
$date should looks like: "yyyy" OR "dd.mm.yyy", year between 1900 to 2099
