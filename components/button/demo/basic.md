---
order: 0
title:
  zh-CN: 按钮类型
  en-US: Type
---

## zh-CN

按钮有四种类型：主按钮、次按钮、虚线按钮、危险按钮。主按钮在同一个操作区域最多出现一次。

> `danger` 在 `antd@2.7` 后支持。

## en-US

There are `primary` button, `default` button, `dashed` button and `danger` button in antd.

> `danger` is supported after `antd@2.7`.

````jsx
import { Button } from 'choerodon-ui';

ReactDOM.render(
  <div>
    <Button funcType="raised">Rasied</Button>
    <Button funcType="flat">Flat</Button>
    <Button shape="circle" funcType="flat" icon="search" />
  </div>
, mountNode);
````
