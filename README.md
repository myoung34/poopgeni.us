# Poopgenius

This is deployed to fastly WASM

[Its super dumb](https://poopgeni.us/)

Terraform located [here](https://github.com/myoung34/homelab/blob/main/terraform/fastly/poopgeni_us.tf)

To test:

```
$ fastly compute serve
```

To deploy:

```
$ fastly compute publish
```
