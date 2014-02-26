# table

---

通用表格组件，可带表头表尾，用于显示各类数据。

---

## 演示文档

<link type="text/css" rel="stylesheet" media="screen" href="src/table.css">

### 正常表格

````html
<div class="ali-table-container">
    <table class="ali-table"><!-- 可以在class中加入ali-table-inbox或ali-table-noborder分别适应不同的情况 -->
        <thead>
            <tr>
                <th>创建时间</th>
                <th>名称<em class="ft-bar">|</em>交易号</th>
                <th>对方</th>
                <th>金额<em class="ft-bar">|</em>明细</th>
                <th>状态</th>
                <th>操作</th>
                <th>备注</th>
            </tr>
        </thead><!-- 表头可选 -->
        <tbody>
            <tr>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
            </tr>
            <tr class="ali-table-split">
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
            </tr>
            <tr>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
            </tr>
            <tr class="ali-table-split">
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
            </tr>
            <tr>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="7">表尾数据</td>
            </tr>
        </tfoot><!-- 表尾可选 -->
    </table>
</div>
````

### 无边框的表格

````html
<table class="ali-table ali-table-noborder">
    <tbody>
        <tr>
            <td>1</td>
            <td>吴实</td>
            <td>
                <p>电话：13000111222</p>
                <p>地址：浙江省杭州市西湖区晚唐路567号</p>
            </td>
            <td>操作</td>
        </tr>
        <tr class="ali-table-split">
            <td>2</td>
            <td>吴实</td>
            <td>
                <p>电话：13000111222</p>
                <p>地址：浙江省杭州市西湖区晚唐路567号</p>
            </td>
            <td>操作</td>
        </tr>
        <tr>
            <td>3</td>
            <td>吴实</td>
            <td>
                <p>电话：13000111222</p>
                <p>地址：浙江省杭州市西湖区晚唐路567号</p>
            </td>
            <td>操作</td>
        </tr>
        <tr class="ali-table-split">
            <td>4</td>
            <td>吴实</td>
            <td>
                <p>电话：13000111222</p>
                <p>地址：浙江省杭州市西湖区晚唐路567号</p>
            </td>
            <td>操作</td>
        </tr>
    </tbody>
</table>
````

### 可以嵌在别的框里的表格

````html
<div class="ali-table-container">
    <table class="ali-table ali-table-inbox"><!-- 可以在class中加入ali-table-inbox或ali-table-noborder分别适应不同的情况 -->
        <thead>
            <tr>
                <th>创建时间</th>
                <th>名称<em class="ft-bar">|</em>交易号</th>
                <th>对方</th>
                <th>金额<em class="ft-bar">|</em>明细</th>
                <th>状态</th>
                <th>操作</th>
                <th>备注</th>
            </tr>
        </thead><!-- 表头可选 -->
        <tbody>
            <tr>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td class="ali-table-action">Data</td>
                <td>Data</td>
            </tr>
            <tr class="ali-table-split">
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td>Data</td>
                <td class="ali-table-action">Data</td>
                <td>Data</td>
            </tr>
        </tbody>
    </table>
</div>
````
