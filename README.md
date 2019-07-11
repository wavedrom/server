## Markdown embedding
Server side WaveDrom rendering

```html
<img src="https://svg.wavedrom.com/github/wavedrom/wavedrom/master/test/reg-vl.json5"/>
```

<img src="https://svg.wavedrom.com/github/wavedrom/wavedrom/master/test/reg-vl.json5"/>

```html
<img src="https://svg.wavedrom.com/{signal:[{wave:'0.P.....'},{wave:'02345230',data:'S E R V E R'}]}"/>
```

<img src="https://svg.wavedrom.com/{signal:[{wave:'0.P.....'},{wave:'02345230',data:'S E R V E R'}]}"/>

### Render diagram from MD file with details right after the image inline

```
<img src="https://svg.wavedrom.com/github/wavedrom/wavedrom/master/server/README.md/mark1"/>
```

<img src="https://svg.wavedrom.com/github/wavedrom/wavedrom/master/server/README.md/mark1"/>

<details><pre lang="js">
{signal:[
  {wave: '0.P.....'},
  {wave: '02345230',data: 'S E R V E R'}
]}
</pre></details>
