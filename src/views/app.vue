<template>
  <div class="wrapper">
    <p>自定义模块正在运行(Custom Module server is running)</p>
    <h4>下面是一些单页面入口(Following are the entries of page)</h4>
    <ul>
      <li><a href="custom/knowledge">/custom/knowledge</a></li>
      <li><a href="custom/public">/custom/public</a></li>
      <li><a href="custom/upload">/custom/upload</a></li>
      <li><a href="custom/dashboard/air">/custom/dashboard/air</a></li>
    </ul>
    <h4>no nginx config using following</h4>
    <ul>
      <li><a href="/views/custom/knowledge.html">/custom/knowledge</a></li>
      <li><a href="/views/custom/public.html">/custom/public</a></li>
      <li><a href="/views/custom/upload.html">/custom/upload</a></li>
      <li><a href="/views/custom/dashboard/air.html">/custom/dashboard/air</a></li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {}
  },
  created(){}
}
</script>
