<script lang="ts">
  export let imgsrc: string = "";
  export let headingData: string = "";
  export let textData: string = "";
  export let buttonText = "";
  export let bgColor = "";
  export let ct = "";
  export let ht = "";
  export let pt = "";
  export let bt = "";
</script>

<div class="flex">
  <div class="w-1/2">
    <img src={imgsrc} alt="error" class="object-cover w-full h-full" />
  </div>

  <div class="{bgColor} w-1/2">
    <center class={ct}>
      <h1 class={ht}>{headingData}</h1>
      <p class={pt}>
        {textData}
      </p>
    </center>
    <center>
      <button class={bt}>
        {buttonText}
      </button>
    </center>
  </div>
</div>
