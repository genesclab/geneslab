<template>
  <section>
    テスト
    {{ green }}
    {{ test }}
    <script src="https://tonejs.github.io/CDN/latest/Tone.min.js"></script>
    <script>
      console.log(10000000000000)
      console.log(100099999900)
      if (Tone) {
        console.log(12)
      }
      else {
        console.log(2)
      }

    </script>
  </section>
</template>

<script>
let green
if (Tone) {
    green = "succses"
  }
  else {
    green = "false"
  }
export default {
  data() {
    return {
      green: green,
      test: "お疲れ"
    }
  }

}
</script>
