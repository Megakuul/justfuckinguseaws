<svelte:head>
  <title>Just use AWS</title>
  <meta name="description" content="Don't overthink just switch your production workload to AWS!" />
  <meta
    property="og:description"
    content="Don't overthink just switch your production workload to AWS!"
  />
  <link rel="canonical" href="https://justfuckinguseaws.ch" />
  <meta property="og:title" content="Just use AWS" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://justfuckinguseaws.ch/favicon.png" />
</svelte:head>

<div class="w-full flex flex-col justify-center items-center gap-32">
  <div class="w-full bg-yellow-600/80 h-6">
    <h2 class="text-center">
      This website is not affiliated by AWS in any way; we just try to make the world a bit more
      scalable.
    </h2>
  </div>
  <div class="w-full flex flex-row items-center justify-around">
    <h1 class="text-9xl font-bold flex flex-col items-start text-black/80">
      <span>JUST</span>
      <span>FUCKING</span>
      <span>use <b class="font-extrabold text-yellow-600">AWS</b></span>
    </h1>

    <div
      class="w-1/3 min-w-96 text-xl bg-slate-300/20 border-[0.05rem] border-slate-900 rounded-2xl p-8"
    >
      <p>
        I've been using AWS lately and all I can say is: it's incredible! Since I started using it,
        I was able to afford multiple superyachts.
      </p>
      <br />
      <p class="text-slate-800/80">~ Jeff Bezos himself</p>
    </div>
  </div>

  <div class="w-full bg-slate-900 mb-20">
    <h2 class="text-2xl font-semibold text-slate-50/80 text-center">
      Stop waiting for an
      <span class="text-amber-300/80">Asteroid</span>
      to hit your datacenter; Start building
      <b class="text-yellow-600">MULTI-AZ</b>
      from day one!
    </h2>
  </div>

  <h2 class="text-5xl font-bolds text-slate-950/90">Scale Comparison</h2>
  <div class="xl:min-w-6xl mx-5 flex flex-col xl:flex-row items-center justify-around gap-6">
    <div
      class="w-full flex flex-col gap-2 text-xl p-4 rounded-2xl border-slate-950 border-[0.05rem]"
    >
      <h3 class="font-bold text-4xl text-red-700/80">Hetzner</h3>
      <hr />
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Availability:</b>
        <span>No Multi-AZ</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Reliability:</b>
        <span>Not so good</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Services:</b>
        <span>Wannabe AWS services</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>AI:</b>
        <span>No</span>
      </div>
    </div>
    <div
      class="w-full flex flex-col gap-2 text-xl p-4 rounded-2xl border-slate-950 border-[0.05rem]"
    >
      <h3 class="font-bold text-4xl text-yellow-600/80">AWS</h3>
      <hr />
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Availability:</b>
        <span>Always Available</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Reliability:</b>
        <span>Very Reliable</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Services:</b>
        <span>If it exists, it is on AWS</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>AI:</b>
        <span>Yeeessss</span>
      </div>
    </div>
    <div
      class="w-full flex flex-col gap-2 text-xl p-4 rounded-2xl border-slate-950 border-[0.05rem]"
    >
      <h3 class="font-bold text-4xl text-black">Vercel</h3>
      <hr />
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Availability:</b>
        <span>Mostly Available*</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Reliability:</b>
        <span>Mostly Reliable*</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>Services:</b>
        <span>Some Soydev stuff</span>
      </div>
      <div class="flex flex-row items-center gap-4 justify-between">
        <b>AI:</b>
        <span>YES YES YES YES</span>
      </div>
    </div>
  </div>
  <p>* the underlying platform is ALWAYS available / reliable</p>

  <blockquote class="flex flex-col items-start mx-10 gap-8 max-w-[1000px] my-32">
    <p class="text-5xl font-semibold text-start text-slate-950/80">
      We just need to achieve communism before Cost Explorer synchronizes.
    </p>
    <p class="text-slate-800/80 text-3xl">~ Karl Marx (I guess)</p>
  </blockquote>
</div>
