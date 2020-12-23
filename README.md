# RepeatLayoutManager

</div>
一款可以让`RecyclerView`无限循环的`LayoutManager`

## 使用

* 添加依赖

```gradle
 implementation 'cn.student0.manager:repeatmanager:1.0.2'
```

* 在代码中使用 
```java
        RecyclerView recyclerView = findViewById(R.id.rv_demo);
        recyclerView.setAdapter(new DemoAdapter());
        recyclerView.setLayoutManager(new RepeatLayoutManager(RecyclerView.VERTICAL));
```

* 效果
<div  align="center">
<img src="https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/c00a312e889e4f57a952e3a71263b628~tplv-k3u1fbpfcp-watermark.image" width = "260" height = "490" alt="1xx"/>
</div>

<hr/>

```
   Copyright 2020 wangjian

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```