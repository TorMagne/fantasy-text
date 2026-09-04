<template>
  <main class="flex min-w-0 flex-1 flex-col">
    <!-- Scene -->
    <section class="flex-1 bg-game-bg p-6">
      <div
        class="flex h-full items-center justify-center border border-game-border-dim bg-game-panel"
      >
        <div class="text-center">
          <span class="font-fantasy text-xs uppercase tracking-[0.18em] text-game-gold">
            The Outskirts
          </span>

          <h1 class="mt-3 font-fantasy text-3xl text-game-white">The Forest Road</h1>

          <p class="mx-auto mt-3 max-w-lg font-narrative text-lg text-game-text-dim">
            A narrow road disappears between ancient trees. The wind carries the distant sound of
            something moving through the undergrowth.
          </p>
        </div>
      </div>
    </section>

    <!-- Event / Terminal -->
    <section class="shrink-0 border-t border-game-border bg-game-panel">
      <div class="border-b border-game-border px-5 py-3">
        <span class="font-fantasy text-xs uppercase tracking-[0.14em] text-game-gold-light">
          Event
        </span>
      </div>

      <div class="p-5">
        <p class="font-narrative text-xl text-game-text">
          You hear something moving behind the trees.
        </p>

        <p class="mt-2 font-narrative text-lg text-game-text-dim">What do you do?</p>

        <div class="mt-5 flex gap-3">
          <button
            class="cursor-pointer border border-game-border-gold bg-game-panel-2 px-5 py-2.5 font-fantasy text-xs uppercase tracking-[0.1em] text-game-gold-light hover:bg-game-panel-3"
          >
            Investigate
          </button>

          <button
            class="cursor-pointer border border-game-border-dim bg-game-panel-2 px-5 py-2.5 font-fantasy text-xs uppercase tracking-[0.1em] text-game-text-dim hover:border-game-border-gold hover:text-game-text"
          >
            Hide
          </button>

          <button
            class="cursor-pointer border border-game-border-dim bg-game-panel-2 px-5 py-2.5 font-fantasy text-xs uppercase tracking-[0.1em] text-game-text-dim hover:border-game-border-gold hover:text-game-text"
          >
            Keep Walking
          </button>
        </div>
      </div>
    </section>
  </main>
</template>
