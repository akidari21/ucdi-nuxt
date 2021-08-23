<template>
  <section class="container-fluid example">
    <div class="d-flex flex-column">
      <button class="btn btn-xs btn-primary">버튼</button>
      <button class="btn btn-sm btn-primary">버튼</button>
      <button class="btn btn-primary">버튼</button>
      <button class="btn btn-lg btn-primary">버튼</button>
      <button class="btn btn-xl btn-primary">버튼</button>
    </div>
  </section>
</template>

<style lang="scss" scoped>
// 공통 외의 Special 예외 버튼이 있을 경우만 작성
// 가이드용 scss
.example {
  .btn {
    margin-bottom: 1rem;
  }
}
</style>
