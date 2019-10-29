<template>
  <el-table :data="tableData" style="width: 100%" height="250">
    <el-table-column fixed prop="date" label="日期" width="150"></el-table-column>
    <el-table-column prop="name" label="姓名" width="120"></el-table-column>
    <el-table-column prop="province" label="省份" width="120"></el-table-column>
    <el-table-column prop="city" label="市区" width="120"></el-table-column>
    <el-table-column prop="address" label="地址" width="300"></el-table-column>
    <el-table-column prop="zip" label="邮编" width="120"></el-table-column>
  </el-table>
</template>

<script>
export default {
  name: "Table",
  data() {
    return {
      tableData: [
        {
          date: "2019-10-29",
          name: "张三",
          province: "江苏",
          city: "苏州",
          address: "江苏省苏州市中移软件园A01",
          zip: 215500
        },
        {
          date: "2019-10-29",
          name: "张三",
          province: "江苏",
          city: "苏州",
          address: "江苏省苏州市中移软件园A01",
          zip: 215500
        },
        {
          date: "2019-10-29",
          name: "张三",
          province: "江苏",
          city: "苏州",
          address: "江苏省苏州市中移软件园A01",
          zip: 215500
        },
        {
          date: "2019-10-29",
          name: "张三",
          province: "江苏",
          city: "苏州",
          address: "江苏省苏州市中移软件园A01",
          zip: 215500
        },
        {
          date: "2019-10-29",
          name: "张三",
          province: "江苏",
          city: "苏州",
          address: "江苏省苏州市中移软件园A01",
          zip: 215500
        },
        {
          date: "2019-10-29",
          name: "张三",
          province: "江苏",
          city: "苏州",
          address: "江苏省苏州市中移软件园A01",
          zip: 215500
        },
        {
          date: "2019-10-29",
          name: "张三",
          province: "江苏",
          city: "苏州",
          address: "江苏省苏州市中移软件园A01",
          zip: 215500
        }
      ]
    };
  },
  // props: {
  //   msg: String
  // }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
