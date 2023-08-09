<!-- the pattern works when using [][] -->
[ok][{{< relref "a" >}}]
[ok][{{< param "links" >}}]
[ok][{{< ref "links" >}}]
[should fail][{{< xxx "links" >}}]
[should fail][anything]

<!-- the pattern fails when using []() -->
[should not fail]({{< param "fail" >}})
