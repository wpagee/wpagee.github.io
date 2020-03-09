<template>
  <el-container class="has-background">
    <el-main>
      <div class="intro">
        <h1>William Agee</h1>
        <p>
          Currently the Director of Engineering at ZVerse. 
          I'm a full-stack developer, father of twins, keyboard and headphone enthusiast with a passion for writing code.
        </p>
      </div>
    </el-main>
    <el-footer>
      <a
        style="background-color:#eee;color:#3d3d3d;text-decoration:none;padding:4px 6px;font-family:-apple-system, BlinkMacSystemFont, &quot;San Francisco&quot;, &quot;Helvetica Neue&quot;, Helvetica, Ubuntu, Roboto, Noto, &quot;Segoe UI&quot;, Arial, sans-serif;font-size:12px;font-weight:bold;line-height:1.2;display:inline-block;border-radius:3px"
        href="https://unsplash.com/@blakeconnally?utm_medium=referral&amp;utm_campaign=photographer-credit&amp;utm_content=creditBadge" 
        target="_blank" 
        rel="noopener noreferrer" 
        title="Download free do whatever you want high-resolution photos from Blake Connally"
      >
        Photo by Blake Connally
      </a>
    </el-footer>
  </el-container>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

.has-background {
  background: url('../assets/blake-connally-B3l0g6HLxr8-unsplash.jpg') no-repeat center center fixed;
  background-size: cover;
  background-position: center;
  height: 100%;
}

.el-container {
  min-height: 100vh;
  color: #fff;
  position: relative;
  z-index: 1;
}

.el-main,
.el-footer {  
  background-color: rgba(52,52,52,0.5);
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei",Arial,sans-serif;
}

.intro {
  font-size: 2rem;
  margin: 15% auto 0; 
  max-width: 800px;
}
</style>
