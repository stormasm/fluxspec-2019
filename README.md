# fluxspec

* index.md is the index
* spec.md is the
[original spec without an index](https://github.com/influxdata/flux/blob/master/docs/SPEC.md)
* specindex.md is the index and the spec combined

To generate the index simply

git clone https://github.com/jonschlinkert/markdown-toc

```
npm install
node cli.js > index.md
```

Then simply copy and paste the **index.md** to the top of the **spec.md**
and create a new file called **specindex.md**

Eventually this could be automated into the flux doc build process.
