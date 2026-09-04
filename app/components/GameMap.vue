```vue
<template>
  <aside class="flex min-h-full w-64 shrink-0 flex-col border-r border-game-border bg-game-panel">
    <!-- Header -->
    <div class="shrink-0 border-b border-game-border px-5 py-4">
      <div class="flex items-center gap-2">
        <Map class="text-game-gold" :size="17" />

        <span class="font-fantasy text-xs uppercase tracking-[0.14em] text-game-gold-light">
          World Map
        </span>
      </div>
    </div>

    <!-- Map -->
    <div class="flex-1 p-5">
      <div class="flex flex-col items-center">
        <button
          class="flex h-14 w-14 items-center justify-center border border-game-gold bg-game-panel-3 text-game-gold-light"
        >
          <Compass :size="22" />
        </button>

        <span class="mt-3 font-fantasy text-[11px] uppercase tracking-[0.1em] text-game-text">
          The Outskirts
        </span>

        <span class="mt-1 text-[10px] text-game-text-muted"> Current location </span>
      </div>

      <div class="mt-16 flex flex-col items-center">
        <button
          class="flex h-12 w-12 items-center justify-center border border-game-border bg-game-panel-2 text-game-text-dim hover:border-game-gold hover:text-game-gold"
        >
          <TreePine :size="19" />
        </button>

        <span class="mt-3 font-fantasy text-[10px] uppercase tracking-[0.1em] text-game-text-dim">
          Whispering Woods
        </span>
      </div>

      <div class="mt-16 flex flex-col items-center opacity-40">
        <div
          class="flex h-12 w-12 items-center justify-center border border-game-border-dim bg-game-panel"
        >
          <Lock :size="17" />
        </div>

        <span class="mt-3 font-fantasy text-[10px] uppercase tracking-[0.1em] text-game-text-muted">
          Unknown
        </span>
      </div>
    </div>

    <!-- Current Location -->
    <div class="shrink-0 border-t border-game-border px-5 py-4">
      <div class="mb-2 flex items-center gap-2">
        <MapPin :size="14" class="text-game-gold" />

        <span class="font-fantasy text-[10px] uppercase tracking-[0.14em] text-game-gold-light">
          Current Location
        </span>
      </div>

      <h3 class="font-fantasy text-sm text-game-text">The Outskirts</h3>

      <p class="mt-1 text-xs leading-relaxed text-game-text-muted">
        The road leading into the wilds of Elyndor.
      </p>
    </div>
  </aside>
</template>
``` The only thing you need to make sure of is that `MapPin` is available through your Nuxt Lucide
setup, just like `Map`, `Compass`, `TreePine`, and `Lock`.
