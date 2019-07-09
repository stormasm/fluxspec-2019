# fluxspec

* index.md is the index
* spec.md is the
[original spec without an index](https://github.com/influxdata/flux/blob/master/docs/SPEC.md)
* specindex.md is the index and the spec combined

grab a new copy of **spec.md** and replace the older version
in this repo.

To generate the index simply

git clone this repo  
git clone https://github.com/jonschlinkert/markdown-toc

```
cd markdown-toc
npm install
cp ./../fluxspec/run .
bash run
```

Eventually this could be automated into the flux doc build process.
