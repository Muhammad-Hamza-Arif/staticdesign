<template>
  <div class="max-w-7xl mx-auto">
    <!-- header -->
    <header class="flex justify-between items-center mt-10 px-8">
      <div>
        <svg
          aria-hidden="true"
          viewBox="0 0 183 48"
          class="h-11 w-auto text-slate-900"
        >
          <path
            fill="#3B82F6"
            fill-rule="evenodd"
            d="M1.172 21.172a4 4 0 000 5.656l20 20a4 4 0 105.656-5.656l-20-20a4 4 0 00-5.656 0z"
            clip-rule="evenodd"
          ></path>
          <path
            fill="#93C5FD"
            fill-rule="evenodd"
            d="M26.828 6.828a4 4 0 10-5.656-5.656l-19 19A3.987 3.987 0 015 19a3.98 3.98 0 012.827 1.172L10.657 23 26.828 6.828z"
            clip-rule="evenodd"
          ></path>
          <path
            fill="#0F172A"
            d="M52 32V15.2h5.736c1.968 0 3.584.352 4.848 1.056 1.28.688 2.224 1.664 2.832 2.928.624 1.248.936 2.72.936 4.416 0 1.696-.312 3.176-.936 4.44-.608 1.248-1.552 2.224-2.832 2.928-1.264.688-2.88 1.032-4.848 1.032H52zm3.072-2.64h2.52c1.408 0 2.52-.224 3.336-.672a3.958 3.958 0 001.752-1.968c.352-.864.528-1.904.528-3.12 0-1.2-.176-2.232-.528-3.096a3.944 3.944 0 00-1.752-1.992c-.816-.464-1.928-.696-3.336-.696h-2.52V29.36zm18.263 2.928c-1.2 0-2.264-.256-3.192-.768a5.559 5.559 0 01-2.184-2.16c-.529-.928-.793-2-.793-3.216 0-1.232.257-2.328.769-3.288a5.687 5.687 0 012.16-2.232c.927-.544 2.016-.816 3.264-.816 1.168 0 2.2.256 3.096.768a5.407 5.407 0 012.088 2.112c.511.88.767 1.864.767 2.952 0 .176-.008.36-.023.552 0 .192-.009.392-.025.6h-9.047c.063.928.383 1.656.96 2.184.591.528 1.303.792 2.136.792.623 0 1.143-.136 1.56-.408.431-.288.752-.656.96-1.104h3.12a5.68 5.68 0 01-1.128 2.064 5.423 5.423 0 01-1.92 1.44c-.753.352-1.609.528-2.569.528zm.024-9.984a3.23 3.23 0 00-1.992.648c-.577.416-.945 1.056-1.105 1.92h5.928c-.047-.784-.335-1.408-.864-1.872-.527-.464-1.183-.696-1.967-.696zm12.927 9.984c-1.216 0-2.288-.264-3.216-.792a5.851 5.851 0 01-2.208-2.208c-.528-.944-.792-2.024-.792-3.24 0-1.216.264-2.296.792-3.24A5.851 5.851 0 0183.07 20.6c.928-.528 2-.792 3.216-.792 1.52 0 2.8.4 3.84 1.2 1.04.784 1.704 1.872 1.992 3.264h-3.24a2.299 2.299 0 00-.96-1.344c-.464-.336-1.016-.504-1.656-.504-.848 0-1.568.32-2.16.96-.592.64-.888 1.528-.888 2.664 0 1.136.296 2.024.888 2.664.592.64 1.312.96 2.16.96.64 0 1.192-.16 1.656-.48.48-.32.8-.776.96-1.368h3.24c-.288 1.344-.952 2.424-1.992 3.24-1.04.816-2.32 1.224-3.84 1.224zm12.903 0c-1.2 0-2.264-.256-3.192-.768a5.559 5.559 0 01-2.184-2.16c-.528-.928-.792-2-.792-3.216 0-1.232.256-2.328.768-3.288a5.687 5.687 0 012.16-2.232c.928-.544 2.016-.816 3.264-.816 1.168 0 2.2.256 3.096.768a5.407 5.407 0 012.088 2.112c.512.88.768 1.864.768 2.952 0 .176-.008.36-.024.552 0 .192-.008.392-.024.6h-9.048c.064.928.384 1.656.96 2.184.592.528 1.304.792 2.136.792.624 0 1.144-.136 1.56-.408.432-.288.752-.656.96-1.104h3.12a5.68 5.68 0 01-1.128 2.064 5.423 5.423 0 01-1.92 1.44c-.752.352-1.608.528-2.568.528zm.024-9.984a3.23 3.23 0 00-1.992.648c-.576.416-.944 1.056-1.104 1.92h5.928c-.048-.784-.336-1.408-.864-1.872-.528-.464-1.184-.696-1.968-.696zm7.096 14.976V20.096h2.736l.336 1.704c.384-.528.888-.992 1.512-1.392.64-.4 1.464-.6 2.472-.6 1.12 0 2.12.272 3 .816a5.846 5.846 0 012.088 2.232c.512.944.768 2.016.768 3.216 0 1.2-.256 2.272-.768 3.216a5.894 5.894 0 01-2.088 2.208c-.88.528-1.88.792-3 .792-.896 0-1.68-.168-2.352-.504a4.24 4.24 0 01-1.632-1.416v6.912h-3.072zm6.408-7.68c.976 0 1.784-.328 2.424-.984.64-.656.96-1.504.96-2.544s-.32-1.896-.96-2.568c-.64-.672-1.448-1.008-2.424-1.008-.992 0-1.808.336-2.448 1.008-.624.656-.936 1.504-.936 2.544s.312 1.896.936 2.568c.64.656 1.456.984 2.448.984zM125.36 32c-1.248 0-2.248-.304-3-.912-.752-.608-1.128-1.688-1.128-3.24v-5.184h-2.04v-2.568h2.04l.36-3.192h2.712v3.192h3.216v2.568h-3.216v5.208c0 .576.12.976.36 1.2.256.208.688.312 1.296.312h1.488V32h-2.088zm5.014-13.752c-.56 0-1.024-.168-1.392-.504-.352-.336-.528-.76-.528-1.272s.176-.928.528-1.248c.368-.336.832-.504 1.392-.504.56 0 1.016.168 1.368.504.368.32.552.736.552 1.248s-.184.936-.552 1.272c-.352.336-.808.504-1.368.504zM128.838 32V20.096h3.072V32h-3.072zm12.518.288c-1.696 0-3.152-.36-4.368-1.08a7.383 7.383 0 01-2.808-3.048c-.656-1.312-.984-2.824-.984-4.536 0-1.712.328-3.224.984-4.536.656-1.312 1.592-2.336 2.808-3.072 1.216-.736 2.672-1.104 4.368-1.104 2.016 0 3.664.504 4.944 1.512 1.296.992 2.104 2.392 2.424 4.2h-3.384c-.208-.912-.656-1.624-1.344-2.136-.672-.528-1.568-.792-2.688-.792-1.552 0-2.768.528-3.648 1.584-.88 1.056-1.32 2.504-1.32 4.344 0 1.84.44 3.288 1.32 4.344.88 1.04 2.096 1.56 3.648 1.56 1.12 0 2.016-.24 2.688-.72.688-.496 1.136-1.176 1.344-2.04h3.384c-.32 1.728-1.128 3.08-2.424 4.056-1.28.976-2.928 1.464-4.944 1.464zm14.287 0c-1.152 0-2.192-.264-3.12-.792a5.957 5.957 0 01-2.184-2.184c-.528-.944-.792-2.032-.792-3.264 0-1.232.272-2.312.816-3.24a5.905 5.905 0 012.184-2.208c.928-.528 1.968-.792 3.12-.792 1.136 0 2.16.264 3.072.792a5.68 5.68 0 012.184 2.208c.544.928.816 2.008.816 3.24 0 1.232-.272 2.32-.816 3.264a5.727 5.727 0 01-2.184 2.184c-.928.528-1.96.792-3.096.792zm0-2.664c.8 0 1.496-.296 2.088-.888.592-.608.888-1.504.888-2.688 0-1.184-.296-2.072-.888-2.664-.592-.608-1.28-.912-2.064-.912-.816 0-1.52.304-2.112.912-.576.592-.864 1.48-.864 2.664 0 1.184.288 2.08.864 2.688.592.592 1.288.888 2.088.888zM163.046 32V20.096h2.712l.24 2.016a4.21 4.21 0 011.584-1.68c.704-.416 1.528-.624 2.472-.624 1.472 0 2.616.464 3.432 1.392.816.928 1.224 2.288 1.224 4.08V32h-3.072v-6.432c0-1.024-.208-1.808-.624-2.352-.416-.544-1.064-.816-1.944-.816-.864 0-1.576.304-2.136.912-.544.608-.816 1.456-.816 2.544V32h-3.072zm13.714 0v-9.336h-1.632v-2.568h1.632v-1.392c0-1.44.36-2.464 1.08-3.072.736-.608 1.728-.912 2.976-.912h1.32v2.616h-.84c-.528 0-.904.104-1.128.312-.224.208-.336.56-.336 1.056v1.392h2.568v2.568h-2.568V32h-3.072z"
          ></path>
        </svg>
      </div>
      <ul class="flex gap-2 text-blue-600">
        <li>04-06 of April, 2022</li>
        <li class="h-1.5 w-1.5 bg-blue-500 mt-2.5"></li>
        <li>Los Angeles, CA</li>
      </ul>
      <button class="bg-blue-600 px-3 py-3 rounded-lg font-bold text-white">
        Get your tickets
      </button>
    </header>

    <!-- hero-section -->
    <div class="mt-32 mx-auto max-w-7xl px-8 max-h-[578px] text-start">
      <h1 class="font-bold text-7xl max-w-3xl mx-auto text-blue-600">
        A design conference for the dark side.
      </h1>
      <p class="text-2xl mt-5 max-w-3xl mx-auto text-blue-900">
        The next generation of web users are tech-savvy and suspicious. They
        know how to use dev tools, they can detect a phishing scam from a mile
        away, and they certainly aren’t accepting any checks from Western Union.
      </p>
      <p class="text-2xl mt-5 max-w-3xl mx-auto text-blue-900">
        At DeceptiConf you’ll learn about the latest dark patterns being
        developed to trick even the smartest visitors, and you’ll learn how to
        deploy them without ever being detected.
      </p>
      <div class="flex space-x-14 mt-10 max-w-3xl mx-auto">
        <div>
          <p class="text-blue-600">Speakers</p>
          <span class="font-semibold text-2xl text-blue-900">18</span>
        </div>
        <div>
          <p class="text-blue-600">People Attending</p>
          <span class="font-semibold text-2xl text-blue-900">2,091</span>
        </div>
        <div>
          <p class="text-blue-600">Venue</p>
          <span class="font-semibold text-2xl text-blue-900"
            >Staples Center</span
          >
        </div>
        <div>
          <p class="text-blue-600">Location</p>
          <span class="font-semibold text-2xl text-blue-900">Los Angeles</span>
        </div>
      </div>
    </div>

    <div class="max-w-7xl mx-auto px-8 mt-20 flex">
      <div class="flex flex-col text-start ">
        <div class="ml-4 pl-8 border-l-2 border-slate-500">
          <span class="text-sm leading-6 text-blue-600 font-mono font-semibold"
            >Opening Day</span
          >
          <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8">
            April 4
          </p>
        </div>
        <br />
        <div class="ml-4 pl-8 border-l-2 border-slate-500">
          <span class="text-sm leading-6 font-mono font-semibold"
            >Speakers & Workshops</span
          >
          <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8">
            April 5
          </p>
        </div>
        <br />
        <div class="ml-4 pl-8 border-l-2 border-slate-500">
          <span class="text-sm leading-6 font-mono font-semibold"
            >Interviews</span
          >
          <p class="text-2xl text-blue-900 font-semibold tracking-tight mb-8">
            April 6
          </p>
        </div>
      </div>
      <div class="grid grid-cols-3 gap-4">
        <div
          v-for="i in items"
          :key="i"
          class="block max-w-[18rem] rounded-lg bg-white"
        >
          <div>
            <img class="rounded-t-lg" :src="i.image" alt="" />
          </div>
          <div class="justify-start text-left mb-20">
            <h3
              class="mt-8 font-display text-xl font-bold tracking-tight text-slate-900"
            >
              {{ i.name }}
            </h3>
            <p class="mt-1 text-base tracking-tight text-slate-500">
              {{ i.title }}
            </p>
          </div>
        </div>
      </div>

    </div>

    <!-- 2nd-hero-section -->
    <div class="max-w-7xl mx-auto px-8 mt-48">
      <div class="max-w-3xl pr-24 text-start">
        <h2 class="text-4xl font-medium text-blue-600">
          Our three day schedule is jam-packed with brilliant, creative, evil
          geniuses.
        </h2>
        <p class="mt-4 text-2xl text-blue-900">
          The worst people in our industry giving the best talks you’ve ever
          seen. Nothing will be recorded and every attendee has to sign an NDA
          to watch the talks.
        </p>
      </div>
      <div class="max-w-7xl mx-auto mt-14">
        <div class="grid grid-cols-3 gap-x-8">
          <section>
            <h3 class="text-2xl font-semibold text-blue-900 text-start">April 4</h3>
            <p class="mt-1.5 text-blue-900 text-start">
              The first day of the conference is focused on dark patterns for
              ecommerce.
            </p>
            <div
              class="mt-10 px-10 py-14 bg-blue-100 text-center shadow-blue-900"
            >
              <li class="list-none">
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
            </div>
          </section>
          <section>
            <h3 class="text-2xl font-semibold text-blue-900 text-start">April 4</h3>
            <p class="mt-1.5 text-blue-900 text-start">
              The first day of the conference is focused on dark patterns for
              ecommerce.
            </p>
            <div
              class="mt-10 px-10 py-14 bg-blue-100 text-center shadow-blue-900"
            >
              <li class="list-none">
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
            </div>
          </section>
          <section>
            <h3 class="text-2xl font-semibold text-blue-900 text-start">April 4</h3>
            <p class="mt-1.5 text-blue-900 text-start">
              The first day of the conference is focused on dark patterns for
              ecommerce.
            </p>
            <div
              class="mt-10 px-10 py-14 bg-blue-100 text-center shadow-blue-900"
            >
              <li class="list-none">
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
              <li class="list-none mt-8">
                <div class="mx-auto mb-8 h-px w-48 bg-indigo-500/10"></div>
                <h4 class="text-lg font-semibold text-blue-900">
                  Steven McHail
                </h4>
                <p class="mt-1 text-blue-900">Not so one-time payments</p>
                <p class="mt-1 text-sm text-slate-500">
                  <time datetime="">9:00AM</time>
                  -
                  <time datetime="">10:00AM</time>
                </p>
              </li>
            </div>
          </section>
        </div>
      </div>
    </div>

    <!-- 3rd-hero-section -->
    <div class="max-w-7xl mx-auto mt-20">
      <h2
        class="mx-auto max-w-2xl text-blue-900 font-medium text-5xl text-center"
      >
        Current sponsorships for our workshops and speakers.
      </h2>
      <div class="mt-20 grid grid-cols-3 max-w-3xl gap-y-7 gap-x-36 mx-auto">
        <div>
          <img
            src="https://keynote.tailwindui.com/_next/static/media/transistor.a1e38d49.svg"
            alt=""
          />
        </div>
        <div>
          <img
            src="https://keynote.tailwindui.com/_next/static/media/tuple.2f54ed03.svg"
            alt=""
          />
        </div>
        <div>
          <img
            src="https://keynote.tailwindui.com/_next/static/media/statickit.2e06fcea.svg"
            alt=""
          />
        </div>
        <div>
          <img
            src="https://keynote.tailwindui.com/_next/static/media/mirage.e12f40ad.svg"
            alt=""
          />
        </div>
        <div>
          <img
            src="	https://keynote.tailwindui.com/_next/static/media/laravel.6faebf7c.svg"
            alt=""
          />
        </div>
        <div>
          <img
            src="https://keynote.tailwindui.com/_next/static/media/statamic.923101b6.svg"
            alt=""
          />
        </div>
      </div>
    </div>

    <!-- last-section -->
    <section class="mt-20">
      <div class="mx-auto max-w-7xl px-8 rounded-3xl">
        <div class="bg-indigo-100 px-16 py-36">
          <div class="mx-auto grid gap-x-32 max-w-4xl grid-cols-2">
            <div class="max-w-4xl text-start">
              <p class="text-4xl font-medium text-blue-900">
                Stay up to date
              </p>
              <p class="mt-4 text-lg text-blue-900">
                Get updates on all of our events and be the first to get
                notified when tickets go on sale.
              </p>
            </div>
            <form class="text-start">
              <h3 class="text-lg font-semibold text-blue-900">
                Sign up to our newsletter
              </h3>
              <div
                class="mt-5 flex rounded-3xl bg-white py-2.5 pr-2.5 shadow-xl shadow-blue-900/5"
              >
                <input
                  type="email"
                  placeholder="Email address"
                  class="-my-2.5 flex-auto bg-transparent pl-6 pr-2.5 text-slate-900 placeholder:text-slate-400"
                /><button
                  class="rounded-2xl bg-blue-600 p-4 font-semibold text-white hover:bg-blue-500"
                  type="submit"
                >
                  Sign up today
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- footer -->
    <footer class="mt-20">
      <div class="mx-auto max-w-7xl px-8 flex items-center justify-between">
        <svg
          aria-hidden="true"
          viewBox="0 0 183 48"
          class="h-12 w-auto text-slate-900"
        >
          <path
            fill="#3B82F6"
            fill-rule="evenodd"
            d="M1.172 21.172a4 4 0 000 5.656l20 20a4 4 0 105.656-5.656l-20-20a4 4 0 00-5.656 0z"
            clip-rule="evenodd"
          ></path>
          <path
            fill="#93C5FD"
            fill-rule="evenodd"
            d="M26.828 6.828a4 4 0 10-5.656-5.656l-19 19A3.987 3.987 0 015 19a3.98 3.98 0 012.827 1.172L10.657 23 26.828 6.828z"
            clip-rule="evenodd"
          ></path>
          <path
            fill="#0F172A"
            d="M52 32V15.2h5.736c1.968 0 3.584.352 4.848 1.056 1.28.688 2.224 1.664 2.832 2.928.624 1.248.936 2.72.936 4.416 0 1.696-.312 3.176-.936 4.44-.608 1.248-1.552 2.224-2.832 2.928-1.264.688-2.88 1.032-4.848 1.032H52zm3.072-2.64h2.52c1.408 0 2.52-.224 3.336-.672a3.958 3.958 0 001.752-1.968c.352-.864.528-1.904.528-3.12 0-1.2-.176-2.232-.528-3.096a3.944 3.944 0 00-1.752-1.992c-.816-.464-1.928-.696-3.336-.696h-2.52V29.36zm18.263 2.928c-1.2 0-2.264-.256-3.192-.768a5.559 5.559 0 01-2.184-2.16c-.529-.928-.793-2-.793-3.216 0-1.232.257-2.328.769-3.288a5.687 5.687 0 012.16-2.232c.927-.544 2.016-.816 3.264-.816 1.168 0 2.2.256 3.096.768a5.407 5.407 0 012.088 2.112c.511.88.767 1.864.767 2.952 0 .176-.008.36-.023.552 0 .192-.009.392-.025.6h-9.047c.063.928.383 1.656.96 2.184.591.528 1.303.792 2.136.792.623 0 1.143-.136 1.56-.408.431-.288.752-.656.96-1.104h3.12a5.68 5.68 0 01-1.128 2.064 5.423 5.423 0 01-1.92 1.44c-.753.352-1.609.528-2.569.528zm.024-9.984a3.23 3.23 0 00-1.992.648c-.577.416-.945 1.056-1.105 1.92h5.928c-.047-.784-.335-1.408-.864-1.872-.527-.464-1.183-.696-1.967-.696zm12.927 9.984c-1.216 0-2.288-.264-3.216-.792a5.851 5.851 0 01-2.208-2.208c-.528-.944-.792-2.024-.792-3.24 0-1.216.264-2.296.792-3.24A5.851 5.851 0 0183.07 20.6c.928-.528 2-.792 3.216-.792 1.52 0 2.8.4 3.84 1.2 1.04.784 1.704 1.872 1.992 3.264h-3.24a2.299 2.299 0 00-.96-1.344c-.464-.336-1.016-.504-1.656-.504-.848 0-1.568.32-2.16.96-.592.64-.888 1.528-.888 2.664 0 1.136.296 2.024.888 2.664.592.64 1.312.96 2.16.96.64 0 1.192-.16 1.656-.48.48-.32.8-.776.96-1.368h3.24c-.288 1.344-.952 2.424-1.992 3.24-1.04.816-2.32 1.224-3.84 1.224zm12.903 0c-1.2 0-2.264-.256-3.192-.768a5.559 5.559 0 01-2.184-2.16c-.528-.928-.792-2-.792-3.216 0-1.232.256-2.328.768-3.288a5.687 5.687 0 012.16-2.232c.928-.544 2.016-.816 3.264-.816 1.168 0 2.2.256 3.096.768a5.407 5.407 0 012.088 2.112c.512.88.768 1.864.768 2.952 0 .176-.008.36-.024.552 0 .192-.008.392-.024.6h-9.048c.064.928.384 1.656.96 2.184.592.528 1.304.792 2.136.792.624 0 1.144-.136 1.56-.408.432-.288.752-.656.96-1.104h3.12a5.68 5.68 0 01-1.128 2.064 5.423 5.423 0 01-1.92 1.44c-.752.352-1.608.528-2.568.528zm.024-9.984a3.23 3.23 0 00-1.992.648c-.576.416-.944 1.056-1.104 1.92h5.928c-.048-.784-.336-1.408-.864-1.872-.528-.464-1.184-.696-1.968-.696zm7.096 14.976V20.096h2.736l.336 1.704c.384-.528.888-.992 1.512-1.392.64-.4 1.464-.6 2.472-.6 1.12 0 2.12.272 3 .816a5.846 5.846 0 012.088 2.232c.512.944.768 2.016.768 3.216 0 1.2-.256 2.272-.768 3.216a5.894 5.894 0 01-2.088 2.208c-.88.528-1.88.792-3 .792-.896 0-1.68-.168-2.352-.504a4.24 4.24 0 01-1.632-1.416v6.912h-3.072zm6.408-7.68c.976 0 1.784-.328 2.424-.984.64-.656.96-1.504.96-2.544s-.32-1.896-.96-2.568c-.64-.672-1.448-1.008-2.424-1.008-.992 0-1.808.336-2.448 1.008-.624.656-.936 1.504-.936 2.544s.312 1.896.936 2.568c.64.656 1.456.984 2.448.984zM125.36 32c-1.248 0-2.248-.304-3-.912-.752-.608-1.128-1.688-1.128-3.24v-5.184h-2.04v-2.568h2.04l.36-3.192h2.712v3.192h3.216v2.568h-3.216v5.208c0 .576.12.976.36 1.2.256.208.688.312 1.296.312h1.488V32h-2.088zm5.014-13.752c-.56 0-1.024-.168-1.392-.504-.352-.336-.528-.76-.528-1.272s.176-.928.528-1.248c.368-.336.832-.504 1.392-.504.56 0 1.016.168 1.368.504.368.32.552.736.552 1.248s-.184.936-.552 1.272c-.352.336-.808.504-1.368.504zM128.838 32V20.096h3.072V32h-3.072zm12.518.288c-1.696 0-3.152-.36-4.368-1.08a7.383 7.383 0 01-2.808-3.048c-.656-1.312-.984-2.824-.984-4.536 0-1.712.328-3.224.984-4.536.656-1.312 1.592-2.336 2.808-3.072 1.216-.736 2.672-1.104 4.368-1.104 2.016 0 3.664.504 4.944 1.512 1.296.992 2.104 2.392 2.424 4.2h-3.384c-.208-.912-.656-1.624-1.344-2.136-.672-.528-1.568-.792-2.688-.792-1.552 0-2.768.528-3.648 1.584-.88 1.056-1.32 2.504-1.32 4.344 0 1.84.44 3.288 1.32 4.344.88 1.04 2.096 1.56 3.648 1.56 1.12 0 2.016-.24 2.688-.72.688-.496 1.136-1.176 1.344-2.04h3.384c-.32 1.728-1.128 3.08-2.424 4.056-1.28.976-2.928 1.464-4.944 1.464zm14.287 0c-1.152 0-2.192-.264-3.12-.792a5.957 5.957 0 01-2.184-2.184c-.528-.944-.792-2.032-.792-3.264 0-1.232.272-2.312.816-3.24a5.905 5.905 0 012.184-2.208c.928-.528 1.968-.792 3.12-.792 1.136 0 2.16.264 3.072.792a5.68 5.68 0 012.184 2.208c.544.928.816 2.008.816 3.24 0 1.232-.272 2.32-.816 3.264a5.727 5.727 0 01-2.184 2.184c-.928.528-1.96.792-3.096.792zm0-2.664c.8 0 1.496-.296 2.088-.888.592-.608.888-1.504.888-2.688 0-1.184-.296-2.072-.888-2.664-.592-.608-1.28-.912-2.064-.912-.816 0-1.52.304-2.112.912-.576.592-.864 1.48-.864 2.664 0 1.184.288 2.08.864 2.688.592.592 1.288.888 2.088.888zM163.046 32V20.096h2.712l.24 2.016a4.21 4.21 0 011.584-1.68c.704-.416 1.528-.624 2.472-.624 1.472 0 2.616.464 3.432 1.392.816.928 1.224 2.288 1.224 4.08V32h-3.072v-6.432c0-1.024-.208-1.808-.624-2.352-.416-.544-1.064-.816-1.944-.816-.864 0-1.576.304-2.136.912-.544.608-.816 1.456-.816 2.544V32h-3.072zm13.714 0v-9.336h-1.632v-2.568h1.632v-1.392c0-1.44.36-2.464 1.08-3.072.736-.608 1.728-.912 2.976-.912h1.32v2.616h-.84c-.528 0-.904.104-1.128.312-.224.208-.336.56-.336 1.056v1.392h2.568v2.568h-2.568V32h-3.072z"
          ></path>
        </svg>
        <p class="mt-6 text-base text-slate-500 md:mt-0">
          Copyright ©
          <!-- -->2023<!-- -->
          DeceptiConf, LLC. All rights reserved.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
    data(){
      return{
        items: [
        {
          name: "Steven McHail",
          title: "Designer at Globex Corporation",
          image:
            "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fsteven-mchail.4e94472e.jpg&w=640&q=75",
        },
        {
          name: "Jaquelin Isch",
          title: "UX Design at InGen",
          image:
            "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fjaquelin-isch.880e5248.jpg&w=640&q=75",
        },
        {
          name: "Dianne Guilianelli",
          title: "General Manager at Initech",
          image:
            "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdianne-guilianelli.b4c5891f.jpg&w=640&q=75",
        },
        {
          name: "Ronni Cantadore",
          title: "Design Engineer at Weyland-Yutani",
          image:
            "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fronni-cantadore.0d04b7fe.jpg&w=640&q=75",
        },
        {
          name: "Erhart Cockrin",
          title: "Product Lead at Cyberdyne",
          image:
            "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Ferhart-cockrin.3697fef6.jpg&w=640&q=75",
        },
        {
          name: "Parker Johnson",
          title: "UI Designer at MomCorp",
          image:
            "https://keynote.tailwindui.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fparker-johnson.3f6d7276.jpg&w=640&q=75",
        },
      ],
      }
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
