<template>
  <div class="container readme">
    <h1>NUXT(Vue) 기반 UI 마크업 가이드 v0.5</h1>
    <p>
      본 가이드는 HTML,CSS 작업자의 Vue 컴포넌트 환경 기반 마크업을 위한 작업
      가이드입니다.
    </p>

    <section>
      <h2>NUXT(Vue) 환경설치</h2>
      <p class="mt-4">
        <a href="#">http://github.com/sdsdfsdfsdf/sdfs</a>
      </p>
      <p>
        <code>&gt; cd c:/scard/dev</code>
      </p>
      <p>
        <code
          >&gt; git clone http://github.com/sdfsdfsdf/sdfsdf myFolderName</code
        >
      </p>
      <p>
        <code>&gt; npm install</code>
      </p>
      <p>
        <code>&gt; npm run dev</code>
      </p>
    </section>

    <section>
      <h2>폴더 구조 (필요 폴더만 기재)</h2>
      <ul class="folder">
        <li>
          <span>/assets</span>
          <i>정적 리소스 폴더</i>
          <ul>
            <li><span>/fonts</span></li>
            <li><span>/images</span></li>
            <li><span>/scss</span><i>공통 scss (7-1 Structure)</i></li>
          </ul>
        </li>
        <li>
          <span>/components</span>
          <ul>
            <li>
              <span>/elements</span>
              <i>엘리먼트 단위 공통 컴포넌트 파일 예시</i>
              <ul class="files">
                <li><span>Button-full.vue</span></li>
                <li><span>Button-round.vue</span></li>
                <li><span>Button-util.vue</span></li>
                <li><span>Input-group.vue</span></li>
                <li><span>Amount-group.vue</span></li>
              </ul>
            </li>
            <li>
              <span>/modules</span>
              <i>모듈 단위 공통 컴포넌트 파일 예시</i>
              <ul class="files">
                <li><span>Card.vue</span></li>
                <li><span>Card2.vue</span></li>
                <li><span>Cardloan.vue</span></li>
              </ul>
            </li>
          </ul>
        </li>
        <li>
          <span>/layouts</span>
          <ul class="files">
            <li><span>default.vue</span></li>
          </ul>
        </li>
        <li>
          <span>/pages</span>
          <ul>
            <li>
              <span>/My</span>
              <i>프로젝트 폴더 구조와 화면ID 파일명 예시</i>
              <ul class="files">
                <li><span>HDMFD000123032XX001.vue</span></li>
              </ul>
            </li>
            <li>
              <span>/Cardapply</span>
              <i>프로젝트 폴더 구조와 화면ID 파일명 예시</i>
              <ul class="files">
                <li><span>HDCFD000123032XX002.vue</span></li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
    </section>
  </div>
</template>

<script>
export default {}
</script>
