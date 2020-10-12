## vue공부한 것
1. 리액트와 달리 vue는 script를 import하여 사용 가능하다<br> 
<code>
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<!--최신 버전-->
</code>
<br>
2. 뷰객체는 el(template),data,method로 이루어져있다.<br>
  * 공식 문서에 el은 element로 되어 있다. vue는 실행되면서 DOM의 element들과 mount(접근 가능하게 함)되게 한다. 우리는 el을 통해 DOM의 element들을 다룰 수 있게 된다.<br>
  * data는 json 형식의 데이터가 들어간다. 아래는 공식문서 예시이다.<br>
<code>
 var data = { a: 1 }
 // direct instance creation
 var vm = new Vue({
   data: data
 })
 vm.a // => 1
 vm.$data === data // => true
 
 // must use function when in Vue.extend()
 var Component = Vue.extend({
   data: function () {
     return { a: 1 }
   }
 })
</code>
