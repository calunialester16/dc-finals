<template>
   <div id="link-wrapper">
    <div id="iframe-wrapper">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/2M5P3YgCYHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/zq1Jv3qU-yo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/tzrSPByRkAQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/hlcMnKWm4tk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/wvatkDfy074" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
   </div>
</template>

<style scoped>

#link-wrapper{
  height: 550px;
  width: 77%;
  background-color: rgba(0, 0, 0, 0.579);
  margin: 25px auto;
  /* display: flex; */
  overflow: auto;
}

#iframe-wrapper iframe{
  margin: 10px 10px 10px;
}

#iframe-wrapper{
  display: inline-grid;
  grid-template-columns: auto auto;
}
</style>
