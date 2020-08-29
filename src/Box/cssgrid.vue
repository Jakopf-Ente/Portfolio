<template>
  <div class="griddi" style="margin-left:auto; margin-right:auto; margin-bottom:0px; height:100%;">
    <div id="bigcontent1">
      <b-link to="/projects/projekt1">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
      </b-link>
    </div>
    <div id="bigcontent2">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content1">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content2">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content3">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content4">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content5">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content6">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content7">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
    <div id="content8">
      <img
        class="img-responsive"
        style="width:100%;  margin:0px;"
        src="https://www.getdigital.de/web/getdigital/gfx/products/__generated__resized/1100x1100/15343NSM_yoshi_main.jpg"
      />
    </div>
  </div>
</template>

<style>
.griddi {
  display: grid;
  height: 100vh;
  width: 80%;

  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr;
  grid-template-areas:
    "bigcontent1 bigcontent1 content1 content2"
    "bigcontent1 bigcontent1 content3 content4"
    "content5 content6 bigcontent2 bigcontent2"
    "content7 content8 bigcontent2 bigcontent2 ";

  grid-gap: 2.5rem;
  
}

#content1 {
  grid-area: content1;
  border: 2px solid black
}

#content2 {
  grid-area: content2;
  border: 2px solid black
}

#content3 {
  grid-area: content3;
  border: 2px solid black
}

#content4 {
  grid-area: content4;
  border: 2px solid black
}

#content5 {
  grid-area: content5;
  border: 2px solid black
}

#content6 {
  grid-area: content6;
  border: 2px solid black
}

#content7 {
  grid-area: content7;
  border: 2px solid black
}

#content8 {
  grid-area: content8;
  border: 2px solid black
}

#bigcontent1 {
  grid-area: bigcontent1;
  border: 2px solid black
}

#bigcontent2 {
  grid-area: bigcontent2;
  border: 2px solid black
}

@media only screen and (max-width: 800px) {
  .griddi {
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-template-areas:
      "bigcontent1"
      "content1"
      "content2"
      "content3"
      "content4"
      "bigcontent2"
      "content5"
      "content6"
      "content7"
      "content8";
  }
}
</style>
