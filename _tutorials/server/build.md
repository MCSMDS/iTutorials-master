---
title: 开始搭建
fragment:
  - title: 开始搭建
    frags:
      - 域名简介
      - 域名的选择
      - 虚假域名
      - 域名注册商
---

## 开始搭建

是的，没错，开始了!

### 获取虚拟主机的 `IP地址` 或 `网址`

一些主机注册商会提供 `IP` 地址，当然有些主机提供商会提供 `网址` ，把他们记录下来！

### 域名解析

登入你的域名注册商，检查是否自带 `DNS解析器`，如果没有，可使用[cloudflare](//www.cloudflare.com)进行绑定。

然后就在DNS解析器进行解析域名，方法如下：

<table class="table table-bordered">
<thead>

<tr>
<th scope="col">记录类型</th>
<th scope="col">名称</th>
<th scope="col">值</th>
</tr>

</thead>
<tbody>

<tr>
<th scope="row">A</th>
<td>空白/@/其他</td>
<td>IP地址</td>
</tr>

<tr>
<th scope="row">CNAME</th>
<td>空白/@/其他</td>
<td>主机域名</td>
</tr>

<tr>
<th scope="row">MX</th>
<td>空白/@/其他</td>
<td>邮箱提供商</td>
</tr>

</tbody>
</table>
