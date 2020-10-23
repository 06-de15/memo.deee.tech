## 文字列の連結

PHPを勉強中なのですが、文字列の連結の基礎を学んだので、メモ。

$familyName = 'サトウ';
$firstName = 'タロウ';

echo $familyName.$firstName;

サトウタロウ

と表示される。

$name = 'サトウ';
$name .= 'タロウ';

echo $name;
サトウタロウ

の省略形もあるようだ。

