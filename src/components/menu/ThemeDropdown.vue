<template>
  <div title="Change Theme" class="dropdown dropdown-end">
    <div tabindex="0" class="btn gap-1 normal-case btn-ghost">
      <SwatchIcon
        class="inline-block h-5 w-5 stroke-current md:h-6 md:w-6"
      ></SwatchIcon>
      <span class="hidden md:inline">Theme</span>
      <ChevronDownIcon
        class="ml-1 hidden h-6 w-6 fill-current opacity-60 sm:inline-block"
      ></ChevronDownIcon>
    </div>
    <div
      class="menu dropdown-content bg-base-200 text-base-content rounded-t-box rounded-b-box top-px max-h-96 h-[70vh] w-52 overflow-y-auto shadow-2xl mt-16"
    >
      <div class="grid grid-cols-1 gap-3 p-3" tabindex="0">
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2 outline"
          data-set-theme="light"
          data-act-class="outline"
        >
          <div
            data-theme="light"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">light</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="dark"
          data-act-class="outline"
        >
          <div
            data-theme="dark"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">dark</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="cupcake"
          data-act-class="outline"
        >
          <div
            data-theme="cupcake"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">cupcake</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="bumblebee"
          data-act-class="outline"
        >
          <div
            data-theme="bumblebee"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">bumblebee</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="emerald"
          data-act-class="outline"
        >
          <div
            data-theme="emerald"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">emerald</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="corporate"
          data-act-class="outline"
        >
          <div
            data-theme="corporate"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">corporate</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="synthwave"
          data-act-class="outline"
        >
          <div
            data-theme="synthwave"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">synthwave</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="retro"
          data-act-class="outline"
        >
          <div
            data-theme="retro"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">retro</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="cyberpunk"
          data-act-class="outline"
        >
          <div
            data-theme="cyberpunk"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">cyberpunk</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="valentine"
          data-act-class="outline"
        >
          <div
            data-theme="valentine"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">valentine</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="halloween"
          data-act-class="outline"
        >
          <div
            data-theme="halloween"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">halloween</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="garden"
          data-act-class="outline"
        >
          <div
            data-theme="garden"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">garden</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="forest"
          data-act-class="outline"
        >
          <div
            data-theme="forest"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">forest</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="aqua"
          data-act-class="outline"
        >
          <div
            data-theme="aqua"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">aqua</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="lofi"
          data-act-class="outline"
        >
          <div
            data-theme="lofi"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">lofi</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="pastel"
          data-act-class="outline"
        >
          <div
            data-theme="pastel"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">pastel</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="fantasy"
          data-act-class="outline"
        >
          <div
            data-theme="fantasy"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">fantasy</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="wireframe"
          data-act-class="outline"
        >
          <div
            data-theme="wireframe"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">wireframe</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="black"
          data-act-class="outline"
        >
          <div
            data-theme="black"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">black</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="luxury"
          data-act-class="outline"
        >
          <div
            data-theme="luxury"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">luxury</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="dracula"
          data-act-class="outline"
        >
          <div
            data-theme="dracula"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">dracula</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="cmyk"
          data-act-class="outline"
        >
          <div
            data-theme="cmyk"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">cmyk</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="autumn"
          data-act-class="outline"
        >
          <div
            data-theme="autumn"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">autumn</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="business"
          data-act-class="outline"
        >
          <div
            data-theme="business"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">business</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="acid"
          data-act-class="outline"
        >
          <div
            data-theme="acid"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">acid</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="lemonade"
          data-act-class="outline"
        >
          <div
            data-theme="lemonade"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">lemonade</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="night"
          data-act-class="outline"
        >
          <div
            data-theme="night"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">night</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="coffee"
          data-act-class="outline"
        >
          <div
            data-theme="coffee"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">coffee</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2"
          data-set-theme="winter"
          data-act-class="outline"
        >
          <div
            data-theme="winter"
            class="bg-base-100 text-base-content w-full cursor-pointer font-sans"
          >
            <div class="grid grid-cols-5 grid-rows-3">
              <div
                class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4"
              >
                <div class="flex-grow text-sm font-bold">winter</div>
                <div class="flex flex-shrink-0 flex-wrap gap-1">
                  <div class="bg-primary w-2 rounded"></div>
                  <div class="bg-secondary w-2 rounded"></div>
                  <div class="bg-accent w-2 rounded"></div>
                  <div class="bg-neutral w-2 rounded"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { ChevronDownIcon } from "@heroicons/vue/24/solid";
import { SwatchIcon } from "@heroicons/vue/24/solid";

export default {
  name: "ThemeDropdown",
  components: {
    ChevronDownIcon,
    SwatchIcon,
  },
  mounted() {
    const dropdownContent = document.querySelectorAll(".dropdown-content>div");
    dropdownContent.forEach((element) => {
      element.addEventListener("click", () => {
        document.activeElement.blur();
      });
    });
  },
};
</script>
