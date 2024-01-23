<script lang="ts">
  export let licon: string = "";
  export let logo: string = "";
</script>

<div class="my-10 mx-7">
  <div class="flex justify-between items-center">
    <div class="flex space-x-6 font-bold">
      <img src={logo} alt="error" class="h-7 w-8" />
      <p>MENU</p>
      <p>REWARDS</p>
      <p>GIFT CARDS</p>
    </div>
    <div class="flex space-x-8 items-center">
      <div class="flex space-x-1 items-center">
        <img src={licon} alt="error" class="h-6" />
        <p class="font-serif font-medium">Find a store</p>
      </div>
      <div class="flex space-x-3 items-center">
        <button
          class="border rounded-3xl border-black text-black px-3 py-0.5 font-serif font-medium hover:bg-slate-100"
        >
          Sign in
        </button>
        <button
          class="border rounded-3xl bg-black text-white px-3 py-0.5 font-serif font-bold hover:bg-neutral-700"
        >
          Join now
        </button>
      </div>
    </div>
  </div>
</div>
