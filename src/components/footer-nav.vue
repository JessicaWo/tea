<template>
  <div>
    <el-footer>
      <ul class="footer">
        <li>
          <a><i class="el-icon-edit"></i>
            <p>首页</p></a>
        </li>
        <li>
          <a><i class="el-icon-edit"></i>
          <p>首页</p></a>
        </li>
        <li>
          <a><i class="el-icon-edit"></i>
            <p>首页</p></a>
        </li>
        <li>
          <a><i class="el-icon-edit"></i>
            <p>首页</p></a>
        </li>
      </ul>
    </el-footer>
  </div>
</template>
<style lang="scss">
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }

  .footer {
    list-style: none;
    padding: 0;
    margin: 0;
    line-height: 0;
    zoom: 1; /*兼容ie6*/
    li {
      float: left;
      padding-top: 10px;
      width: 25%;
      text-align: center;
    }
    &:after {
      content: '';
      clear: both;
      display: block;
      visibility: hidden;
      height: 0;
    }
  }

</style>
