<!-- the pattern works when using [][] -->
[ok][{{< relref "a" >}}]
[ok][{{< param "links" >}}]
[ok][{{< ref "links" >}}]

<!-- the pattern fails when using []() -->
[fail]({{< param "fail" >}})
