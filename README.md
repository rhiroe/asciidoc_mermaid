https://rhiroe.github.io/asciidoc_mermaid

### ローカルで`.adoc`からhtmlを生成するには

```shell
$ bundle install
$ yarn install
$ asciidoctor -o out/index.html -b html5 -r asciidoctor-diagram docs/sample.adoc
```
