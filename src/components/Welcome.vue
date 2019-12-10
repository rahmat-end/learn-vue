<template>
    <div id="welcome">
        <div class="header-wrap">
            <h1>{{ msg }}</h1>
            <p>{{ msg }}</p>
            <ul class="header-list">
                <li>1</li>
                <li>2</li>
                <li>3</li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Welcome',
  data () {
    return {
      msg: 'Welcome mas broo'
    }
  }
}
</script>
