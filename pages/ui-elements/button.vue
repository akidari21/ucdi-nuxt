<template>
  <!-- ** template 안에는 반드시 하나의 부모 wrapper 적용 필요 -->
  <div class="sc-cmn__button">
    <!-- step 3. import한 컴포넌트는 tag형식으로 적용 -->
    <Button />
    <button class="btn btn-xs btn-primary">버튼</button>
    <button class="btn btn-sm btn-primary">버튼</button>
    <button class="btn btn-primary">버튼</button>
    <button class="btn btn-lg btn-primary">버튼</button>
    <button class="btn btn-xl btn-primary">버튼</button>
  </div>
</template>

<script>
// step 1. components/elements/ 하위에 자신이 만든 컴포넌트를 import 한다.
import Button from '../../components/elements/Button.vue'

export default {
  components: {
    // step 2. Import한 컴포넌트를 현재 페이지에 사용하기 위해 등록
    Button,
  },
  // * /layouts/ 하위에 다양한 레이아웃을 정의하고 골라서 적용 가능
  layout: 'default',
}
</script>
