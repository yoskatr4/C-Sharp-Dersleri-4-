# Ders4
## C# Değişkenler ve Sabitler
C# dilinde, değişkenler, programınızda saklamak için kullanabileceğiniz verileri temsil eder. Değişkenler, belirli bir türde verileri saklamak için kullanılır ve bu verileri program sırasında kullanmak için kullanılır. C# dilinde, değişkenler tanımlamak için kullanılan anahtar kelime “var” veya türün adıdır.
Değişkenlerin türleri, değişkenlerin sakladığı verilerin türünü belirtir. Örneğin, bir int türünde bir değişken, tamsayı verileri saklamak için kullanılır. C# dilinde, değişkenlerin türleri şunlardır:

int: tamsayı verileri saklar
float: ondalıklı sayı verileri saklar
double: daha büyük ondalıklı sayı verileri saklar
bool: true / false değerlerini saklar
string: metin verilerini saklar
char: tek karakter verilerini saklar

Değişkenler tanımlamak için kullanılan sözdizimi şöyledir:

<pre>
[veri tipi] [değişken adı] = [değer];
</pre>
ÖRNEĞİN
<pre>
int yas = 25;
string ad = "Ali";
bool ogrenci= true;
</pre>
Değişkenlerin türleri, değişkenlerin oluşturulduğu anda belirlenir ve değişkenlerin türleri program sırasında değiştirilemez. Örneğin, bir int türünde bir değişken, tamsayı verileri sakladığı için, daha sonra bu değişkenin değerini bir metin değeri olarak değiştirmek mümkün değildir.

C# dilinde, değişkenlerin türleri mutlaka belirtilmelidir ve program sırasında otomatik olarak tanımlanamaz. Bu nedenle, değişkenlerin türleri önemlidir ve doğru şekilde tanımlanmalıdır.

Değişkenlerin türleri tanımlanırken aynı zamanda değişkenlerin başlangıç değerleri de belirlenebilir. Ancak, eğer başlangıç değeri belirtilmezse, değişkenler için varsayılan değerler kullanılır. Örneğin, int türünde bir değişken için varsayılan değer 0’dır. Ayrıca, değişkenlerin değerleri program sırasında değiştirilebilir. Örneğin, aşağıdaki kod parçasında “yas” değişkeninin değeri başlangıçta 25 olarak tanımlanmıştır ve daha sonra 30 olarak değiştirilmiştir:
<pre>
int yas = 25;
Console.WriteLine(yas); // 25
yas = 30;
Console.WriteLine(yas); // 30
</pre>

C# dilinde, ayrıca “const” ve “readonly” anahtar kelimeleri kullanılarak değişkenlerin değerlerinin değiştirilmemesini sağlayabilirsiniz. “const” anahtar kelimesi kullanılarak tanımlanan değişkenlerin değerleri derleme zamanında belirlenir ve program sırasında değiştirilemez. “readonly” anahtar kelimesi kullanılarak tanımlanan değişkenlerin değerleri yalnızca tanımlama anında veya yapılandırıcıda belirlenebilir ve program sırasında değiştirilemez.

<pre>
const int MaxAge = 100;
readonly int MinAge = 18;
</pre>

C# dilinde değişkenler, programlarınızda verileri saklamak ve işlem yapmak için önemlidir. Doğru türde tanımlanmaları ve kullanılmaları önemlidir. Ayrıca, “const” ve “readonly” anahtar kelimeleri kullanarak değişkenlerin değerlerinin değiştirilmemesini sağlayabilirsiniz.

C# dilinde, değişkenler ayrıca “dynamic” türü olarak tanımlanabilir. “dynamic” türü, değişkenin türünün önceden belirlenmediği anlamına gelir ve değişkenin türü program sırasında belirlenir. Bu, değişkenin türünün runtime sırasında belirlenmesi anlamına gelir ve değişkenin türünün önceden bilinmediği durumlarda kullanışlıdır.

<pre>
dynamic variable = "Hello";
Console.WriteLine(variable.GetType()); // System.String
variable = 5;
Console.WriteLine(variable.GetType()); // System.Int32
</pre>

“dynamic” türü kullanarak, bir değişkenin türünün önceden bilinmediği durumlarda kolayca değiştirilebilir ve çeşitli işlemler yapılabilir. Ancak, kod yazarken dikkatli olunması gerekir çünkü “dynamic” türünün kullanılması, derleme zamanı hatalarının önlenememesine neden olabilir.

Son olarak, C# dilinde, değişkenler ayrıca “var” anahtar kelimesi kullanarak da tanımlanabilir. “var” anahtar kelimesi kullanarak tanımlanan değişkenlerin türleri derleme zamanında otomatik olarak belirlenir ve değişkenin türünün belirtilmesine gerek yoktur. Ancak, bu değişkenlerin türlerinin belirlenmesi için tanımlama anında bir değer verilmesi gerekir. Örneğin,

<pre>
var isim = "Burak";
</pre>

Bu örnekte, “isim” değişkeni otomatik olarak “string” türüne atanmıştır.

“var” anahtar kelimesi kullanarak tanımlanan değişkenler, okunabilirliği arttırmak ve kodun daha kısa olmasını sağlamak amacıyla kullanılabilir. Ancak, kodun anlaşılırlığını azaltabileceği için dikkatli kullanılması gerekir. Özellikle değişkenin türünün belirlenmesi için kullanılan değerin ne olduğu açık değilse.

C# dilinde, değişkenler, programlarınızda verileri saklamak ve işlem yapmak için önemlidir. Doğru türde tanımlanmaları ve kullanılmaları önemlidir. “var” , “const” ve “readonly” anahtar kelimeleri ile değişkenlerin türlerinin belirlenmesi ve değişkenlerin değerlerinin değiştirilmemesi sağlanabilir. “dynamic” türü ise runtime sırasında türün belirlenmesi için kullanılabilir.


# 🌐 Sosyal Medya:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/https://discord.gg/uXjfKUJXs7) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/1yazilim.exe1) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@yoskatechnology)











kaynak: http://www.yazilimkodlama.com/dokuman/c-degiskenler-ve-sabitler/
