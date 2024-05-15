<template>
  <div id="quote" class="text-light py-2 px-5">
    <p id="phrase" class="fs-5 mb-0">“Let the future tell the truth and evaluate each one according to his work and accomplishments. The present is theirs; the future, for which I really worked, is mine.”</p>
    <div id="author" class="fs-6 text-end"> - Nikola Tesla</div>
  </div>
</template>

<script>
export default {
    name: 'Quote'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fugaz+One&display=swap');

#quote {
    height: 15vh;
    font-family: 'Fugaz One';
    background-color: #00597C;
}

#phrase {
    font-size: 14pt;
}

#author {
    font-size: 12pt;
}
</style>