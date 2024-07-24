<script setup>
import Header from "./components/Header.vue";
import News from "./components/News.vue";
</script>

<template>
  <Header />
  <div class="flex w-full flex-col items-center h-screen relative">
    <div class="max-w-6xl w-full ml-14">
      <News
        tag="Nouveau"
        msg="Les concours TikTok sont disponibles, faites un tirage au sort depuis les commentaires de vos vidéos !"
        class="mt-4"
      />
      <h1
        class="font-black bg-gradient-to-r from-[#197ce7] to-[#23bbfe] bg-clip-text text-transparent text-5xl w-1/2 mt-16"
      >
        Vous allez adorer <br />
        organiser des concours.
      </h1>
      <h2 class="text-xl w-1/2 mt-8 text-[#4b5563]">
        De leur création au tirage au sort, gérez l'intégralité de vos concours
        sur les réseaux sociaux depuis Pickaw.
      </h2>
      <div class="flex logo mt-4">
        <svg
          class="svg-inline--fa fa-x-twitter fa-fw fa-ltr me-2 sm:me-4 text-sm sm:text-2xl text-social-x-twitter"
          style=""
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="x-twitter"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
        >
          <path
            class=""
            style=""
            fill="currentColor"
            d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"
          ></path>
        </svg>
        <svg
          class="svg-inline--fa fa-facebook fa-fw fa-ltr me-2 sm:me-4 text-sm sm:text-2xl text-social-facebook"
          style=""
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="facebook"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
        >
          <path
            class=""
            style=""
            fill="currentColor"
            d="M512 256C512 114.6 397.4 0 256 0S0 114.6 0 256C0 376 82.7 476.8 194.2 504.5V334.2H141.4V256h52.8V222.3c0-87.1 39.4-127.5 125-127.5c16.2 0 44.2 3.2 55.7 6.4V172c-6-.6-16.5-1-29.6-1c-42 0-58.2 15.9-58.2 57.2V256h83.6l-14.4 78.2H287V510.1C413.8 494.8 512 386.9 512 256h0z"
          ></path>
        </svg>
        <svg
          class="svg-inline--fa fa-instagram fa-fw fa-ltr me-2 sm:me-4 text-sm sm:text-2xl text-social-instagram"
          style=""
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="instagram"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        >
          <path
            class=""
            style=""
            fill="currentColor"
            d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"
          ></path>
        </svg>
        <svg
          class="svg-inline--fa fa-youtube fa-fw fa-ltr me-2 sm:me-4 text-sm sm:text-2xl text-social-youtube"
          style=""
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="youtube"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 576 512"
        >
          <path
            class=""
            style=""
            fill="currentColor"
            d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z"
          ></path>
        </svg>
        <svg
          class="svg-inline--fa fa-tiktok fa-fw fa-ltr me-2 sm:me-4 text-sm sm:text-2xl text-social-tiktok"
          style=""
          aria-hidden="true"
          focusable="false"
          data-prefix="fab"
          data-icon="tiktok"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        >
          <path
            class=""
            style=""
            fill="currentColor"
            d="M448,209.91a210.06,210.06,0,0,1-122.77-39.25V349.38A162.55,162.55,0,1,1,185,188.31V278.2a74.62,74.62,0,1,0,52.23,71.18V0l88,0a121.18,121.18,0,0,0,1.86,22.17h0A122.18,122.18,0,0,0,381,102.39a121.43,121.43,0,0,0,67,20.14Z"
          ></path>
        </svg>
      </div>
      <a
        href="#"
        class="bg-gradient-to-r from-[#197ce7] to-[#23bbfe] text-white font-bold px-2 py-1 rounded-full mt-8 inline-block"
        >Essayer la démo</a
      >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        id="Calque_1"
        viewBox="0 0 100.57 104.79"
        class="absolute top-0 -right-16 -z-30"
      >
        <linearGradient
          id="SVGID_1_"
          x1="55.2978"
          x2="79.849"
          y1="54.9843"
          y2="54.9843"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0" stop-color="#d500f9" />
          <stop offset=".9895" stop-color="#2979ff" />
        </linearGradient>
        <path
          fill="url(#SVGID_1_)"
          d="M79.85 76.27l-15.3.13-9.25-42.71 15.3-.12z"
        />
        <linearGradient
          id="SVGID_2_"
          x1="5.2912"
          x2="77.012"
          y1="39.1892"
          y2="39.1892"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0" stop-color="#d500f9" />
          <stop offset=".9895" stop-color="#2979ff" />
        </linearGradient>
        <path
          fill="url(#SVGID_2_)"
          d="M20.59 70.55l-15.3.13L61.71 7.83l15.3-.13z"
        />
        <linearGradient
          id="SVGID_3_"
          x1="5.2912"
          x2="96.0619"
          y1="83.1773"
          y2="83.1773"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0" stop-color="#d500f9" />
          <stop offset=".9895" stop-color="#2979ff" />
        </linearGradient>
        <path
          fill="url(#SVGID_3_)"
          d="M96.06 95.67l-15.3.13L5.29 70.68l15.3-.13z"
        />
        <linearGradient
          id="SVGID_4_"
          x1="20.5919"
          x2="96.0619"
          y1="51.6851"
          y2="51.6851"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0" stop-color="#ea80fc" />
          <stop offset=".9895" stop-color="#40c4ff" />
        </linearGradient>
        <path
          fill="url(#SVGID_4_)"
          d="M77.01 7.7l19.05 87.98-75.47-25.13L77.01 7.7zm-33.8 56.38l36.64 12.2-9.25-42.71-27.39 30.51"
        />
        <g opacity=".74">
          <linearGradient
            id="SVGID_5_"
            x1="5.2912"
            x2="96.0619"
            y1="83.1773"
            y2="83.1773"
            gradientUnits="userSpaceOnUse"
          >
            <stop offset="0" stop-color="#d500f9" />
            <stop offset=".9895" stop-color="#2979ff" />
          </linearGradient>
          <path
            fill="url(#SVGID_5_)"
            d="M96.06 95.67l-15.3.13L5.29 70.68l15.3-.13z"
          />
        </g>
      </svg>
    </div>
    <section class="mt-16">
      <div
        class="bg-white w-screen flex justify-center reassure border-b border-[#f0f9ff]"
      >
        <div
          class="max-w-6xl flex gap-8 flex-wrap justify-center items-center my-6"
        >
          <a href="#"> <img src="./assets/cdiscount.png" alt="cdiscount" /></a>
          <a href="#"> <img src="./assets/jv.png" alt="jv" class="" /> </a>
          <a href="#"> <img src="./assets/fdj.png" alt="fdj" /> </a>
          <a href="#"> <img src="./assets/microsoft.png" alt="microsoft" /> </a>
          <a href="#"> <img src="./assets/netflix.png" alt="netflix" /> </a>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            xml:space="preserve"
            viewBox="0 0 600 600"
            class="h-6 md:h-[2.25rem] mx-3 md:mx-5"
            alt="PSG"
          >
            <defs>
              <clipPath id="q" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-365.57 719.79h850.39v-850.4h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="m" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-611.97 633.03h850.4v-850.4h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="f" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-244.79 684.4h850.4v-850.39h-850.4Z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="g" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-263.7 696.64h850.4v-850.4h-850.4Z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="h" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-316.91 688.33h850.4v-850.4h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="i" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-407.25 722.38h850.4v-850.4h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="j" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-453.44 703.1h850.4v-850.4h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="k" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-515.34 689.5h850.4v-850.39h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="n" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-644.43 598.57h850.4v-850.39h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="e" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-204.46 650.94h850.4v-850.4h-850.4Z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="p" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-192.6 596.32h850.39v-850.39h-850.4Z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="l" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-588.54 651.19h850.39v-850.4h-850.4Z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <clipPath id="o" clipPathUnits="userSpaceOnUse">
                <path
                  d="M-564.42 666.97h850.4v-850.4h-850.4z"
                  style="stroke-width: 0.999998"
                />
              </clipPath>
              <linearGradient id="c">
                <stop offset="0" style="stop-color: #dd4b44; stop-opacity: 1" />
                <stop
                  offset=".2"
                  style="stop-color: #de5448; stop-opacity: 1"
                />
                <stop
                  offset=".35"
                  style="stop-color: #db3d39; stop-opacity: 1"
                />
                <stop
                  offset=".49"
                  style="stop-color: #cc2c2e; stop-opacity: 1"
                />
                <stop
                  offset=".75"
                  style="stop-color: #ae2826; stop-opacity: 1"
                />
                <stop offset="1" style="stop-color: #8a211b; stop-opacity: 1" />
              </linearGradient>
              <linearGradient id="b">
                <stop offset="0" style="stop-color: #2277b6; stop-opacity: 1" />
                <stop
                  offset=".1"
                  style="stop-color: #4086c2; stop-opacity: 1"
                />
                <stop
                  offset=".22"
                  style="stop-color: #1b73b3; stop-opacity: 1"
                />
                <stop
                  offset=".54"
                  style="stop-color: #124783; stop-opacity: 1"
                />
                <stop
                  offset=".78"
                  style="stop-color: #003e73; stop-opacity: 1"
                />
                <stop offset="1" style="stop-color: #002448; stop-opacity: 1" />
              </linearGradient>
              <linearGradient
                id="r"
                xlink:href="#c"
                x1="215.4"
                x2="325.32"
                y1="341.28"
                y2="143.6"
                gradientTransform="matrix(1.25 0 0 -1.25 .02 600)"
                gradientUnits="userSpaceOnUse"
              />
              <radialGradient
                id="d"
                xlink:href="#b"
                cx="184.6"
                cy="139.95"
                r="300"
                fx="184.6"
                fy="139.95"
                gradientTransform="matrix(1.1354319 1.1268333 -1.0165344 1.0242913 98.86 -199.01)"
                gradientUnits="userSpaceOnUse"
              />
              <path
                id="a"
                d="m-267.37-6.85-4.85 23.83-4.85-23.83V-51.6h-25.21v14.54h-9.7v-14.54h-14.55v-9.7h14.55v-14.55h9.7v14.55h25.2V-86.5h-14.54v-9.7h14.55v-14.55h9.7v14.55h14.54v9.7h-14.54v25.2h25.2v-14.54h9.7v14.55h14.55v9.7h-14.54v14.54h-9.7v-14.54h-25.21V-6.85z"
                style="
                  fill: #fcef3c;
                  fill-opacity: 1;
                  stroke: #000;
                  stroke-width: 3.80701542;
                  stroke-miterlimit: 4;
                  stroke-dasharray: none;
                  stroke-opacity: 1;
                  display: inline;
                "
              />
            </defs>
            <path
              d="M300 0C134.57 0 0 134.59 0 299.99 0 465.4 134.57 600 300 600s300-134.59 300-300.01C600 134.59 465.43 0 300 0"
              style="
                fill: url(#d);
                fill-opacity: 1;
                fill-rule: nonzero;
                stroke: none;
              "
            />
            <path
              d="M401.44 72.42a256.65 256.65 0 0 0-13.22-5.46l-26.45 63.63c4.47 1.67 8.88 3.5 13.19 5.5zM298.68 63.47h25.62a11.38 11.38 0 0 1 0 22.75h-25.62zm0 34.94h17.45l15.05 23.8a177.87 177.87 0 0 1 17.58 4.1L330.7 97.56c10.36-2.76 18.89-11.88 18.89-22.7 0-13-12.31-23.57-25.3-23.57h-39.54v68.56c4.6-.36 9.21-.57 13.9-.57h.03zM132.65 130.99l18.77-20.6a11.37 11.37 0 0 1 16.8 15.31l-18.76 20.62zm41.44 37.74-15.62-14.21 19.33-21.3c8.77-9.59 8.77-25.02-.86-33.78-9.6-8.76-25.21-7.55-33.98 2.05l-28.7 31.6 50.02 45.57c3.12-3.45 6.43-6.74 9.8-9.93M435.27 110.97c10.32-2.43 29.27 16.4 32.91 29.17 3-2.29 9.72-7.22 9.72-7.22-8.03-22.8-39.94-45.62-55.08-31.33-9 8.5-3.9 21.57 3.95 29.83l7.62 8.03c7.77 8.17 14.55 16.3 8.31 21.48-6.64 5.5-25.26-8.29-36.45-31.96l-10 7.57c2.38 6.22 7.78 15.24 15.02 22.89 8.22 8.64 17.17 14.28 25.2 15.86 6.3 1.23 12.57.28 16.71-3.55 10.34-9.6 6.57-23.55-9.67-40.65l-6.71-7.07c-7.48-7.88-4.43-12.36-1.53-13.05M220.56 77.9l19.39 22.24a208.1 208.1 0 0 0-20.58 7.21m4.15-44.62c-4.9 1.55-9.74 3.26-14.5 5.14l-5.17 78.1c4.64-2.83 9.4-5.45 14.28-7.87l.74-18.2c9.4-4.16 19.24-7.6 29.36-10.26l12 13.76a179.62 179.62 0 0 1 16.08-2.71z"
              style="
                fill: #fff;
                fill-opacity: 1;
                fill-rule: nonzero;
                stroke: none;
                stroke-width: 1.25;
              "
            />
            <g style="stroke-width: 1.82658">
              <path
                d="m0 0 4.13-3.88L16.3 2.06 28.57-8.62l-3.91-13.17 4.61-3.56 11.09 38.94-4.39 3.82zm21.5 4.5 12.43 6.04L30.13-3z"
                clip-path="url(#e)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 139.01 465.37)"
              />
              <path
                d="m0 0 4.33-2.92 20.18 31.36-4.34 2.92z"
                clip-path="url(#f)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 168.45 489.8)"
              />
              <path
                d="m0 0 4.46-2.65 12.93 25.18.08-.04 6.29-35.42 4.55-2.12 16.73 32.71-4.59 2.47L27.73-4.7l-.08.04-6.24 35.03-4.6 2.47z"
                clip-path="url(#g)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 182.26 498.73)"
              />
              <path
                d="m0 0 11.92-4.26L1.7-34.37l4.89-1.76L16.82-6l11.93-4.26 1.7 5.02L1.7 5.02Z"
                clip-path="url(#h)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 221.1 492.66)"
              />
              <path
                d="M0 0c-.2-12.54 9.72-19.45 19.32-19.61 9.03-.15 16.2 4.16 16.3 10.79l.16 9.8-16.5.27-.1-5.31 11.33-.19-.07-4.13c-.04-3.15-4.55-6.03-10.8-5.92-9.11.16-14.58 6.73-14.46 13.97.12 7.72 5.74 14.02 15.3 13.86 6.52-.11 9.25-3.55 11-5.34l3.66 3.72c-2.08 2.1-6.52 6.8-15.11 6.94h-.39C8.32 18.86.16 10.42 0 0"
                clip-path="url(#i)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 287.04 517.52)"
              />
              <path
                d="m0 0 5.11-36.53L35.2-32.1l-.73 5.26-24.96-3.67-1.56 11.15 12.12 1.78-.73 5.28-12.13-1.8-1.34 9.6L29.93-.98l-.75 5.27z"
                clip-path="url(#j)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 320.76 503.44)"
              />
              <path
                d="m0 0-20.31-6.26L-9.94-41.6l4.97 1.45-4.34 14.83 12.82 3.96 11.2-12.58 5.43 2L8.89-19.5c2.83 1.13 7.13 5.09 4.88 12.76C12.19-1.38 8.39.68 4.27.68 2.86.68 1.4.44 0 0m-13.86-9.82L1.49-5.1c2.86.88 6.14.82 7.31-3.2 1-3.43-.52-6.06-4.25-7.2l-15.35-4.75Z"
                clip-path="url(#k)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 365.95 493.52)"
              />
              <path
                d="m0 0 7.6-39.7 4.62 3.02-2.53 13.36 13.1 9.56 11.15-6.99 4.51 3.7L4.7 3.4Zm6-3.72 11.88-7.1-9.24-6.74z"
                clip-path="url(#l)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 419.38 465.55)"
              />
              <path
                d="m0 0 24.51-27.02 3.87 3.53L3.8 3.61Z"
                clip-path="url(#m)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 436.48 452.3)"
              />
              <path
                d="m0 0 20.35-18.75-.07-.07-34.67 2.44-3.47-3.95L9-45.1l3.64 3.8-20.6 19 .06.07 35.04-2.45 3.1 3.95L3.47 3.96Z"
                clip-path="url(#n)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 460.18 427.15)"
              />
              <path
                d="m0 0-.78-26.16-21.12 14.71-4.64-2.41 15.75-33.2 4.7 2.15-10.9 23.6.1.05L4.01-35.8l.8 25.88.1.05 12.25-22.95 4.5 2.6L4.62 2.41Z"
                clip-path="url(#o)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 401.77 477.07)"
              />
              <path
                d="M0 0a7.54 7.54 0 0 1-3-5.12c-.47-3.3.82-7.45 3.48-11.1l3.84-5.25c2.97-4.06 5.84-8.32 5.24-11.68a4.78 4.78 0 0 0-2.21-3.26 4.15 4.15 0 0 0-2.32-.67c-5.21 0-14.03 9.52-18.36 23.15l-.09.25-3.79-3.64-.07-.08.03-.09c.84-3.4 3.1-8.91 6.92-14.14 4-5.48 8.57-9.28 12.85-10.69C3.9-42.77 5.25-43 6.55-43c1.87 0 3.54.5 4.8 1.45a8.8 8.8 0 0 1 3.66 5.9c.65 4.35-1.62 10.1-6.7 17.06l-3.39 4.65c-2.7 3.71-2.59 6.13-2.01 7.5a3.57 3.57 0 0 0 3.4 2.2c6.18 0 14.93-10.5 17.2-18.65l.06-.21.18.11c1.28.76 2.78 1.63 3.7 2.16l.1.07-.03.12C24.58-9.4 13.42 1.66 5.01 1.66A8.07 8.07 0 0 1 0 0"
                clip-path="url(#p)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 130.36 425.5)"
              />
              <path
                d="m0 0 12.84-2.9 1.15 5.25L1.18 5.31Z"
                clip-path="url(#q)"
                style="
                  fill: #fff;
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 1.82658;
                "
                transform="matrix(.72996342 0 0 -.72996253 256.62 515.63)"
              />
            </g>
            <path
              d="M300 21.45A278.55 278.55 0 0 0 21.45 300 278.55 278.55 0 0 0 300 578.55 278.55 278.55 0 0 0 578.55 300 278.55 278.55 0 0 0 300 21.45Zm0 11.02A267.52 267.53 0 0 1 567.53 300 267.52 267.53 0 0 1 300 567.53 267.52 267.53 0 0 1 32.47 300 267.52 267.53 0 0 1 300 32.47Z"
              style="
                fill: #fff;
                stroke: none;
                stroke-width: 2;
                stroke-linecap: square;
              "
            />
            <g style="stroke-width: 0.999999">
              <g style="stroke-width: 0.999999">
                <path
                  d="m305.23 429.7-5.45-6.33-5.46 6.33-.21.6a20.9 20.9 0 0 0 5.17 6.64l.5.26.5-.26a20.98 20.98 0 0 0 5.19-6.64l-.24-.6M310.46 395.3c0-6.25-8.2-25.78-10.67-25.78l-.62.26c-2.98 2.43-10.05 19.7-10.05 25.53 0 4.67 9.43 16.98 9.43 23.67l1.24 1.24 1.24-1.24v-.05c.04-6.69 9.43-18.95 9.43-23.62M294.46 418.4c-4.43-11.67-12.05-18.05-20-18.05a10.87 10.87 0 0 0-10.86 10.85c0 6 5.84 9.86 10.86 10.86 1.62.33 3.5-.66 4.6-1.9.89-1 1.8-2.74 1.09-3.88-.25-.4-.97-.05-1.38-.27-1.52-.8-3.65-1.92-3.65-3.64 0-1.71 1.94-3.53 3.65-3.62 5.68-.29 9.86 3.43 13.26 10.74v.05l.03.05 1.21.71 1.33-1.36-.14-.54M324.75 400.35c-7.93 0-15.58 6.38-20 18.05l-.13.54 1.34 1.38 1.19-.73.02-.05.03-.03c3.38-7.33 7.57-11.05 13.26-10.76 1.7.09 3.62 1.91 3.62 3.62 0 1.71-2.1 2.84-3.62 3.64-.42.23-1.15-.14-1.4.27-.72 1.15.21 2.9 1.11 3.9 1.1 1.23 2.96 2.2 4.58 1.88 5.02-1 10.86-4.86 10.86-10.86 0-6-4.86-10.85-10.86-10.85"
                  style="
                    fill: #c2a24e;
                    fill-opacity: 1;
                    fill-rule: nonzero;
                    stroke: none;
                    stroke-width: 1.25;
                  "
                  transform="matrix(.9999969 0 0 1.0000028 .6 -1.01)"
                />
              </g>
              <path
                d="M299.8 136.74a164.27 164.27 0 0 0-164.28 164.27 164.27 164.27 0 0 0 164.27 164.27A164.27 164.27 0 0 0 464.06 301 164.27 164.27 0 0 0 299.8 136.74Zm-21.73 12.58c-7.02 97.66-47.89 169.93-114.95 220.33a153.24 153.24 0 0 1-16.57-68.64 153.24 153.24 0 0 1 131.52-151.69Zm43.44 0a153.24 153.24 0 0 1 131.53 151.69 153.24 153.24 0 0 1-16.57 68.64c-67.07-50.4-107.94-122.67-114.96-220.33Zm-21.73 200.54c35.8 0 64.82 27.87 64.82 62.23a79 79 0 0 1-6.34 30.25 153.24 153.24 0 0 1-58.47 11.91 153.24 153.24 0 0 1-58.48-11.91 78.96 78.96 0 0 1-6.35-30.25c0-34.36 29.03-62.23 64.82-62.23z"
                style="
                  fill: #fff;
                  stroke: none;
                  stroke-width: 2.00001;
                  stroke-linecap: square;
                "
                transform="matrix(.9999969 0 0 1.0000028 .21 -1.01)"
              />
              <path
                d="M299.8 147.77a153.24 153.24 0 0 0-14.05.92c-1.16 57.7-15.32 107.57-39.17 149.42h106.47c-23.85-41.85-38.01-91.72-39.17-149.42a153.24 153.24 0 0 0-14.09-.92zm-56.71 156.31c-18.57 30.8-43.3 57.94-71.25 80.68A153.24 153.24 0 0 0 219.1 431c-.69-3.96-1.06-8-1.06-12.14 0-42.22 36.6-76.44 81.77-76.44 45.18 0 81.78 34.22 81.78 76.44 0 4.13-.37 8.16-1.05 12.1a153.24 153.24 0 0 0 47.22-46.23c-27.94-22.73-52.66-49.86-71.22-80.65H299.8z"
                style="
                  fill: url(#r);
                  fill-opacity: 1;
                  fill-rule: nonzero;
                  stroke: none;
                  stroke-width: 0.999999;
                "
                transform="matrix(.9999969 0 0 1.0000028 .21 -1.01)"
              />
            </g>
          </svg>
          <a href="#"> <img src="./assets/fnac.png" alt="fnac" /> </a>
          <a href="#"> <img src="./assets/unibet.png" alt="unibet" /> </a>
          <a href="#"> <img src="./assets/binance.png" alt="binance" /> </a>
        </div>
      </div>
    </section>
    <section class="bg-[#f0f9ff] flex w-full justify-center h-full py-24">
      <div class="flex w-full max-w-6xl md:mt-16 mt-32 justify-between">
        <div class="w-full">
          <img
            src="./assets/manage-contests.png"
            class="absolute left-16 w-2/5"
          />
        </div>
        <div class="flex flex-col w-4/5 text-right pr-4">
          <h3
            class="font-medium bg-gradient-to-r from-[#197ce7] to-[#23bbfe] bg-clip-text text-transparent text-5xl w-full"
          >
            Gérez vos concours sur une seule plateforme.
          </h3>
          <p class="my-8 text-[#4b5563] text-xl">
            Planifiez, configurez, prévisualisez, tirez au sort et suivez les
            statistiques de vos concours sur Pickaw en un clin d'oeil.
          </p>
          <p class="text-[#4b5563] text-xl">
            Déjà sur Facebook, Twitter, YouTube, Instagram et TikTok. Et
            prochainement disponible sur bien d'autres plateformes.
          </p>
          <a
            href="#"
            class="text-[#21A9F7] text-xl font-semibold flex justify-end mt-4 hover:text-[#0075BE] duration-300"
            >En savoir plus
            <svg
              class="svg-inline--fa fa-circle-arrow-right fa-fw ms-3 w-4"
              style=""
              aria-hidden="true"
              focusable="false"
              data-prefix="fad"
              data-icon="circle-arrow-right"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <g class="fa-duotone-group" style="">
                <path
                  class="fa-secondary"
                  style=""
                  fill="#D5F4FF"
                  d="M0 256a256 256 0 1 0 512 0A256 256 0 1 0 0 256zM281 385c-9.4 9.4-24.6 9.4-33.9 0s-9.4-24.6 0-33.9l71-71L136 280c-13.3 0-24-10.7-24-24s10.7-24 24-24l182.1 0-71-71c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0L393 239c9.4 9.4 9.4 24.6 0 33.9L281 385z"
                ></path>
                <path
                  class="fa-primary"
                  style=""
                  fill="#21a9f7"
                  d="M393 239c9.4 9.4 9.4 24.6 0 33.9L281 385c-9.4 9.4-24.6 9.4-33.9 0s-9.4-24.6 0-33.9l71-71L136 280c-13.3 0-24-10.7-24-24s10.7-24 24-24l182.1 0-71-71c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0L393 239z"
                ></path>
              </g>
            </svg>
          </a>
        </div>
      </div>
    </section>
    <section class="bg-white flex w-full justify-center h-full py-24">
      <div class="flex w-full max-w-6xl md:mt-16 mt-32 justify-between">
        <div class="flex flex-col w-4/5 text-left pl-4">
          <h3
            class="font-medium bg-gradient-to-r from-[#197ce7] to-[#23bbfe] bg-clip-text text-transparent text-5xl w-full"
          >
            Le tirage au sort par excellence.
          </h3>
          <p class="my-8 text-[#4b5563] text-xl">
            Pickaw est la seule plateforme vous assurant une très haute qualité
            de tirage au sort parmi toutes les participations pour chacun de vos
            concours.
          </p>
          <p class="text-[#4b5563] text-xl">
            Tirez au sort vos concours Facebook, Twitter, YouTube, Instagram et
            TikTok en toute transparence avec une multitude de fonctionnalités,
            maintenant.
          </p>
          <a
            href="#"
            class="text-[#21A9F7] text-xl font-semibold flex mt-4 hover:text-[#0075BE] duration-300"
            >En savoir plus
            <svg
              class="svg-inline--fa fa-circle-arrow-right fa-fw ms-3 w-4"
              style=""
              aria-hidden="true"
              focusable="false"
              data-prefix="fad"
              data-icon="circle-arrow-right"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <g class="fa-duotone-group" style="">
                <path
                  class="fa-secondary"
                  style=""
                  fill="#D5F4FF"
                  d="M0 256a256 256 0 1 0 512 0A256 256 0 1 0 0 256zM281 385c-9.4 9.4-24.6 9.4-33.9 0s-9.4-24.6 0-33.9l71-71L136 280c-13.3 0-24-10.7-24-24s10.7-24 24-24l182.1 0-71-71c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0L393 239c9.4 9.4 9.4 24.6 0 33.9L281 385z"
                ></path>
                <path
                  class="fa-primary"
                  style=""
                  fill="#21a9f7"
                  d="M393 239c9.4 9.4 9.4 24.6 0 33.9L281 385c-9.4 9.4-24.6 9.4-33.9 0s-9.4-24.6 0-33.9l71-71L136 280c-13.3 0-24-10.7-24-24s10.7-24 24-24l182.1 0-71-71c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0L393 239z"
                ></path>
              </g>
            </svg>
          </a>
        </div>
        <div class="w-full">
          <img
            src="./assets/manage-contests.png"
            class="absolute right-16 w-2/5"
          />
        </div>
      </div>
    </section>
    <section class="bg-[#f0f9ff] flex w-full justify-center h-full py-32">
      <div class="flex w-full max-w-6xl md:mt-16 mt-32 justify-between">
        <div class="w-full">
          <img
            src="./assets/manage-contests.png"
            class="absolute left-16 w-2/5"
          />
        </div>
        <div class="flex flex-col w-4/5 text-right pr-4">
          <h3
            class="font-medium bg-gradient-to-r from-[#197ce7] to-[#23bbfe] bg-clip-text text-transparent text-5xl w-full"
          >
            Des offres adaptées à vos besoins.
          </h3>
          <p class="my-8 text-[#4b5563] text-xl">
            La base gratuite de Pickaw vous permet d'importer et tirer au sort
            autant de concours que vous voulez. Tout simplement.
          </p>
          <p class="text-[#4b5563] text-xl">
            Consultez nos abonnements pour bénéficier de plus de fonctionnalités
            lors de vos concours et tirages.
          </p>
          <a
            href="#"
            class="text-[#21A9F7] text-xl font-semibold flex justify-end mt-4 hover:text-[#0075BE] duration-300"
            >En savoir plus
            <svg
              class="svg-inline--fa fa-circle-arrow-right fa-fw ms-3 w-4"
              style=""
              aria-hidden="true"
              focusable="false"
              data-prefix="fad"
              data-icon="circle-arrow-right"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <g class="fa-duotone-group" style="">
                <path
                  class="fa-secondary"
                  style=""
                  fill="#D5F4FF"
                  d="M0 256a256 256 0 1 0 512 0A256 256 0 1 0 0 256zM281 385c-9.4 9.4-24.6 9.4-33.9 0s-9.4-24.6 0-33.9l71-71L136 280c-13.3 0-24-10.7-24-24s10.7-24 24-24l182.1 0-71-71c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0L393 239c9.4 9.4 9.4 24.6 0 33.9L281 385z"
                ></path>
                <path
                  class="fa-primary"
                  style=""
                  fill="#21a9f7"
                  d="M393 239c9.4 9.4 9.4 24.6 0 33.9L281 385c-9.4 9.4-24.6 9.4-33.9 0s-9.4-24.6 0-33.9l71-71L136 280c-13.3 0-24-10.7-24-24s10.7-24 24-24l182.1 0-71-71c-9.4-9.4-9.4-24.6 0-33.9s24.6-9.4 33.9 0L393 239z"
                ></path>
              </g>
            </svg>
          </a>
        </div>
      </div>
    </section>
    <footer>
      <div
        class="bg-gradient-to-r from-[#197ce7] to-[#23bbfe] w-screen py-20 flex flex-col items-center gap-8 relative -z-20"
      >
        <img
          src="./assets/triangle.svg"
          alt="triangle"
          class="absolute -top-[700px] w-1/3 right-28"
        />
        <h2 class="text-white text-4xl">
          Créez et tirez au sort vos concours dès maintenant !
        </h2>
        <a
          href="#"
          class="bg-white px-5 py-3 rounded-full drop-shadow text-[#21a9f7] font-bold hover:text-black hover:duration-500 hover:-translate-y-1"
          >Découvrir Pickaw</a
        >
      </div>
    </footer>
  </div>
</template>

<style scoped>
.logo svg {
  height: 1.5rem;
}

.reassure a img {
  width: 100px;
  height: 50px;
  object-fit: contain;
}

.reassure a:nth-child(2) img {
  height: 30px;
}
</style>
