# fabric-amcl
Forking milagro-crypto/amcl - hyperledger/fabric-amcl to make my life much easier

If you have fallen into the same trap with the amcl package. Just override in Gopkg.toml:

```toml
[[override]]
  name = "github.com/milagro-crypto/amcl"
  source = "github.com/epappas/fabric-amcl"
```
