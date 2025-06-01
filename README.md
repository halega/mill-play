VSCode Metals plugin doesn't work on a new Mill project. Execute before start from console:

```
mill.bat -i --import ivy:com.lihaoyi::mill-contrib-bloop: mill.contrib.bloop.Bloop/install
```