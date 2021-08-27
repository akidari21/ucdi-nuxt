<template>
  <div>
    <button class="btn btn-primary" type="button">기본 버튼</button>
  </div>
</template>

<style lang="scss" scoped>
// 공통 외의 예외 스타일이 있을 경우 작성
// 컴포넌트 스타일 커스터마이징
.btn {
  &-primary {
    background-color: $secondary;
    &:hover {
      background-color: #f2f2f2;
    }
  }
}
</style>
