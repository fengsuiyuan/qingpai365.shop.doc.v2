# App信息

> 更新记录

<table>
    <tr>
        <th style="width:250px;">日期</th>
        <th>更新内容</th>
    </tr>
    <tr>
        <td>2018-06-04 10:53:38</td>
        <td>生成时间</td>
    </tr>
</table>

> 字段

<table>
    <tr>
        <th style="width:150px;">属性名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:60px;">必填</th>
        <th style="width:200px;">说明</th>
        <th>备注</th>
    </tr>
    <tr>
        <td>id</td>
        <td>integer</td>
        <td>-</td>
        <td></td>
        <td>-</td>
    </tr>
    <tr>
        <td>userId</td>
        <td>int</td>
        <td>是</td>
        <td>创建人userId</td>
        <td>-</td>
    </tr>
    <tr>
        <td>deviceCount</td>
        <td>int</td>
        <td>是</td>
        <td>设备数量</td>
        <td>-</td>
    </tr>
    <tr>
        <td>shopCount</td>
        <td>int</td>
        <td>是</td>
        <td>门店数量</td>
        <td>-</td>
    </tr>
    <tr>
        <td>smsCount</td>
        <td>int</td>
        <td>是</td>
        <td>短信数量</td>
        <td>-</td>
    </tr>    
    <tr>
        <td>status</td>
        <td>int</td>
        <td>-</td>
        <td>状态</td>
        <td>100:正常 0:禁用</td>
    </tr>    
    <tr>
        <td>createdAt</td>
        <td>datetime</td>
        <td>-</td>
        <td>创建时间</td>
        <td>-</td>
    </tr>
</table>


## 我的APP信息

```
GET /app/app/app
```