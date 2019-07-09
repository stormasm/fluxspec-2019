# fluxspec

* index.md is the index
* spec.md is the
[original spec without an index](https://github.com/influxdata/flux/blob/master/docs/SPEC.md)
* specindex.md is the index and the spec combined

To generate the index simply

git clone https://github.com/jonschlinkert/markdown-toc

```
cd markdown-toc
npm install
node cli.js <location of the file spec.md> > index.md
```

```
cat index.md spec.md > specindex.md
```

The above command simulates a
copy and paste the **index.md** to the top of the **spec.md**
and create a new file called **specindex.md**

Eventually this could be automated into the flux doc build process.

### First step towards automation

copy the bash script run to the markdown-toc repo

```
cd <the markdown-toc> repo
bash run
```
