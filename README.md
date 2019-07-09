# fluxspec

* index.md is the index
* spec.md is the
[original spec without an index](https://github.com/influxdata/flux/blob/master/docs/SPEC.md)
* specindex.md is the index and the spec combined

To generate the index simply

git clone this repo  
git clone https://github.com/jonschlinkert/markdown-toc

```
cd markdown-toc
npm install
cp ./../fluxspec/run .
bash run
```


cp ./../fluxspec/run .
node cli.js ./../fluxspec/spec.md > ./../fluxspec/index.md
cd ./../fluxspec
cat index.md spec.md > specindex.md
```

Eventually this could be automated into the flux doc build process.

### First step towards automation

```
cd fluxspec
bash run
```
