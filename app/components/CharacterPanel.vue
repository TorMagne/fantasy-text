<template>
  <aside class="flex w-72 shrink-0 flex-col border-l border-game-border bg-game-panel">
    <!-- Character -->
    <section class="border-b border-game-border p-5">
      <div class="flex items-center justify-between">
        <div>
          <h2 class="font-fantasy text-lg text-game-white">Rowan</h2>

          <span class="text-xs text-game-text-muted"> Level 4 </span>
        </div>

        <span
          class="flex h-9 w-9 items-center justify-center border border-game-border-gold font-fantasy text-game-gold"
        >
          4
        </span>
      </div>

      <!-- XP -->
      <div class="mt-5">
        <div class="mb-2 flex justify-between text-[10px] uppercase tracking-[0.1em]">
          <span class="text-game-text-muted"> Experience </span>

          <span class="text-game-text-dim"> 320 / 600 </span>
        </div>

        <div class="h-2 bg-game-panel-3">
          <div class="h-full bg-game-gold" style="width: 53.33%" />
        </div>
      </div>
    </section>

    <!-- Attributes -->
    <section class="border-b border-game-border px-5 py-4">
      <div class="mb-3 font-fantasy text-xs uppercase tracking-[0.14em] text-game-gold-light">
        Attributes
      </div>

      <div class="space-y-2.5">
        <!-- Strength -->
        <div class="flex items-center justify-between">
          <div class="flex items-center gap-2.5">
            <LucideSword :size="14" class="text-game-danger" />

            <span class="text-xs text-game-text-muted"> Strength </span>
          </div>

          <span class="font-fantasy text-sm text-game-text"> 4 </span>
        </div>

        <!-- Wisdom -->
        <div class="flex items-center justify-between">
          <div class="flex items-center gap-2.5">
            <LucideBookOpen :size="14" class="text-game-info" />

            <span class="text-xs text-game-text-muted"> Wisdom </span>
          </div>

          <span class="font-fantasy text-sm text-game-text"> 3 </span>
        </div>

        <!-- Agility -->
        <div class="flex items-center justify-between">
          <div class="flex items-center gap-2.5">
            <LucideWind :size="14" class="text-game-success" />

            <span class="text-xs text-game-text-muted"> Agility </span>
          </div>

          <span class="font-fantasy text-sm text-game-text"> 5 </span>
        </div>

        <!-- Luck -->
        <div class="flex items-center justify-between">
          <div class="flex items-center gap-2.5">
            <LucideClover :size="14" class="text-game-gold" />

            <span class="text-xs text-game-text-muted"> Luck </span>
          </div>

          <span class="font-fantasy text-sm text-game-gold-light"> 7 </span>
        </div>
      </div>
    </section>

    <!-- Equipment -->
    <section class="border-b border-game-border p-5">
      <div class="mb-4 font-fantasy text-xs uppercase tracking-[0.14em] text-game-gold-light">
        Equipment
      </div>

      <div class="grid grid-cols-3 gap-2">
        <div
          class="flex h-16 items-center justify-center border border-game-border bg-game-panel-2 text-xl"
        >
          🗡
        </div>

        <div
          class="flex h-16 items-center justify-center border border-game-border bg-game-panel-2 text-xl"
        >
          🧥
        </div>

        <div
          class="flex h-16 items-center justify-center border border-game-border bg-game-panel-2 text-xl"
        >
          🧿
        </div>
      </div>
    </section>

    <!-- Inventory -->
    <section class="p-5">
      <div class="mb-4 flex items-center justify-between">
        <span class="font-fantasy text-xs uppercase tracking-[0.14em] text-game-gold-light">
          Inventory
        </span>

        <span class="text-[10px] text-game-text-muted"> 8 / 20 </span>
      </div>

      <div class="grid grid-cols-4 gap-2">
        <div
          class="flex h-12 items-center justify-center border border-game-border bg-game-panel-2"
        >
          🧪
        </div>

        <div
          class="flex h-12 items-center justify-center border border-game-border bg-game-panel-2"
        >
          🌿
        </div>

        <div
          class="flex h-12 items-center justify-center border border-game-border bg-game-panel-2"
        >
          🗺
        </div>

        <div
          class="flex h-12 items-center justify-center border border-game-border bg-game-panel-2"
        >
          🥖
        </div>

        <div class="h-12 border border-game-border-dim bg-game-panel" />
        <div class="h-12 border border-game-border-dim bg-game-panel" />
        <div class="h-12 border border-game-border-dim bg-game-panel" />
        <div class="h-12 border border-game-border-dim bg-game-panel" />
      </div>
    </section>
  </aside>
</template>
