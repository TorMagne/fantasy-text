<template>
  <header class="flex items-center bg-game-panel px-6 py-4 text-game-text">
    <!-- Logo -->
    <div>
      <h1 class="font-fantasy text-xl tracking-[0.12em] text-game-gold-light">REALMS OF ELYNDOR</h1>
    </div>

    <!-- Character -->
    <section class="ml-12">
      <div class="flex items-center gap-4">
        <h2 class="font-fantasy text-game-white">Rowan</h2>

        <span class="text-sm text-game-text-dim"> Level 4 </span>

        <div class="text-xs text-game-text-muted">
          <span class="mr-2">320 / 600</span>
          <span>XP</span>
        </div>
      </div>

      <div class="mt-1 w-100">
        <div class="mt-1 h-2 overflow-hidden border border-game-border-dim bg-game-panel-3">
          <div class="h-full bg-game-gold" style="width: 53.33%" />
        </div>
      </div>
    </section>

    <!-- Resources -->
    <section class="ml-auto mr-12 flex items-center gap-8">
      <div class="flex items-center gap-2">
        <span class="text-game-danger">
          <LucideHeart :size="20" fill="currentColor" class="text-game-danger" />
        </span>
        <span class="text-sm">84 / 100</span>
      </div>

      <div class="flex items-center gap-2">
        <span class="text-game-gold">
          <LucideCoins :size="20" class="text-game-gold-light" />
        </span>
        <span class="text-sm">382</span>
      </div>
    </section>

    <!-- Actions -->
    <section class="flex items-center gap-5 text-game-text-dim">
      <button class="transition hover:text-game-gold-light cursor-pointer">
        <LucideMail :size="20" />
      </button>

      <button class="transition hover:text-game-gold-light cursor-pointer">
        <LucideBell :size="20" />
      </button>

      <button class="transition hover:text-game-gold-light cursor-pointer">
        <LucideCog :size="20" />
      </button>
    </section>
  </header>
</template>
