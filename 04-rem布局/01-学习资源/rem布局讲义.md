# rem适配

## 核心知识点

1. rem单位

## 每日目标

1. 理解rem单位
2. 使用rem+less+媒体查询完成优惠券案例

## rem单位

1. em单位

   ```css
   em： 相对单位，相对当前标签中的文字大小
   例如：
   div {
       font-size: 20px;
       width: 10em;
       height: 10em;
       background-color: red;
   }
   ```

2. rem单位

   ```css
   rem：相对单位，相对当前文档中根标签html中的文字大小
   
   例如:
   html {
       font-size: 20px;
   }
   
   div {
       width: 10rem;
       height: 10rem;
       background-color: red;
   }
   ```

3. rem 适配的优势

   - 可以实现网页中的元素随着设备大小的变化而变化，不再是固定大小了
   - rem适配，不会影响标签中文字大小的设置（继承的权重为0）

4. rem适配的实际开发过程中的注意事项

   1.  实际开发中移动设备UI图 常见的尺寸有  640px   750px   1024px