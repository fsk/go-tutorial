# float

Virgüllü sayılar için kullanılır.

## float32

32 bit değerindeki sayılar için kullanılır.

## float64

64 bit değerindeki sayılar için kullanılır.

````Go
package main

import "fmt"

func main() {

    var floatSayi1 float32 = 10.123
	fmt.Println(floatSayi1)
	
	var floatSayi2 float64 = 3.14
	fmt.Println(floatSayi2)
	
}
````

Burada çok önemli bir husus var. Bu da noktalı sayılarda noktadan sonra kaç basamak işleneceği.
Bunun için ise aşağıdaki yöntemi kullanabiliriz.

````Go
package main

    var floatSayi1 float32 = 10.123
	fmt.Printf("Float Sayi %.2f",floatSayi1)
	
````

Bu şekilde formatlama yapabiliriz. Ama formatlama işlemkerini Printf içerisinde yapmamız gerekir.