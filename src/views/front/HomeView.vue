<template>
    這是首頁
    <nav class="navbar navbar-expand-lg " style="height: 85px; background-color: #FFFFFF;opacity-60">
      <div class="container">
        <a class="navbar-brand" href="#"><img src="/src/assets/images/logo.png" alt="" width="80" height="40"></a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#">最新消息</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#">精選商品</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#">蠟知識</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#">關於我們</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="搜尋商品" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style scoped>
</style>
