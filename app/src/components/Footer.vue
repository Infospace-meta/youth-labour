<template>
  <section class="bg-gray-50">
    <div class="md:max-w-xl lg:max-w-7xl mx-auto py-5 text-gray-500">
      <div
        class="grid grid-cols-1 justify-content-start place-items-start lg:grid lg:grid-cols-3 justify-content-start lg:place-items-start gap-3 py-10"
      >
        <div class="px-5">
          <router-link to="/">
            <div class="h-3/4 w-3/4">
              <img
                src="../assets/images/seasonal_logo.webp"
                alt="seasonal_jobs"
                loading="lazy"
              />
            </div>
          </router-link>
        </div>

        <div
          class="flex flex-col justify-start items-start lg:flex lg:flex-col lg:justify-start lg:items-start gap-3"
        >
          <!-- phone -->
          <div
            class="flex justify-center items-center lg:flex lg:justify-start lg:items-start gap-2 px-3"
          >
            <div
              class="rounded-full bg-gray-200 p-2 hover:bg-white"
              title="+44 7399 413391"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="#2E7D32"
                class="bi bi-telephone hover:block"
                viewBox="0 0 16 16"
              >
                <path
                  d="M3.654 1.328a.678.678 0 0 0-1.015-.063L1.605 2.3c-.483.484-.661 1.169-.45 1.77a17.6 17.6 0 0 0 4.168 6.608 17.6 17.6 0 0 0 6.608 4.168c.601.211 1.286.033 1.77-.45l1.034-1.034a.678.678 0 0 0-.063-1.015l-2.307-1.794a.68.68 0 0 0-.58-.122l-2.19.547a1.75 1.75 0 0 1-1.657-.459L5.482 8.062a1.75 1.75 0 0 1-.46-1.657l.548-2.19a.68.68 0 0 0-.122-.58zM1.884.511a1.745 1.745 0 0 1 2.612.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.68.68 0 0 0 .178.643l2.457 2.457a.68.68 0 0 0 .644.178l2.189-.547a1.75 1.75 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.6 18.6 0 0 1-7.01-4.42 18.6 18.6 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877z"
                />
              </svg>
            </div>
            <p class="mt-1 text-black">+44 7399 413391</p>
          </div>

          <!-- e-mail -->
          <div
            class="flex justify-center items-center lg:flex lg:justify-start lg:items-start gap-2 px-3"
          >
            <div
              class="rounded-full bg-gray-200 p-2 hover:bg-white"
              title="info@seasonaljobsuk.com"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="#2E7D32"
                class="bi bi-envelope-at"
                viewBox="0 0 16 16"
              >
                <path
                  d="M2 2a2 2 0 0 0-2 2v8.01A2 2 0 0 0 2 14h5.5a.5.5 0 0 0 0-1H2a1 1 0 0 1-.966-.741l5.64-3.471L8 9.583l7-4.2V8.5a.5.5 0 0 0 1 0V4a2 2 0 0 0-2-2zm3.708 6.208L1 11.105V5.383zM1 4.217V4a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v.217l-7 4.2z"
                />
                <path
                  d="M14.247 14.269c1.01 0 1.587-.857 1.587-2.025v-.21C15.834 10.43 14.64 9 12.52 9h-.035C10.42 9 9 10.36 9 12.432v.214C9 14.82 10.438 16 12.358 16h.044c.594 0 1.018-.074 1.237-.175v-.73c-.245.11-.673.18-1.18.18h-.044c-1.334 0-2.571-.788-2.571-2.655v-.157c0-1.657 1.058-2.724 2.64-2.724h.04c1.535 0 2.484 1.05 2.484 2.326v.118c0 .975-.324 1.39-.639 1.39-.232 0-.41-.148-.41-.42v-2.19h-.906v.569h-.03c-.084-.298-.368-.63-.954-.63-.778 0-1.259.555-1.259 1.4v.528c0 .892.49 1.434 1.26 1.434.471 0 .896-.227 1.014-.643h.043c.118.42.617.648 1.12.648m-2.453-1.588v-.227c0-.546.227-.791.573-.791.297 0 .572.192.572.708v.367c0 .573-.253.744-.564.744-.354 0-.581-.215-.581-.8Z"
                />
              </svg>
            </div>
            <p class="mt-1 text-black">info@seasonaljobsuk.com</p>
          </div>
        </div>

        <div
          class="flex flex-col justify-start items-start lg:flex lg:flex-col lg:justify-start lg:items-start gap-3"
        >
          <!-- whatsApp -->
          <div
            class="flex justify-center items-center lg:flex lg:justify-start lg:items-start gap-2 px-3"
          >
            <div
              class="rounded-full bg-gray-200 p-2 hover:bg-white"
              title="+254 796 309986"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="#2E7D32"
                class="bi bi-whatsapp"
                viewBox="0 0 16 16"
              >
                <path
                  d="M13.601 2.326A7.85 7.85 0 0 0 7.994 0C3.627 0 .068 3.558.064 7.926c0 1.399.366 2.76 1.057 3.965L0 16l4.204-1.102a7.9 7.9 0 0 0 3.79.965h.004c4.368 0 7.926-3.558 7.93-7.93A7.9 7.9 0 0 0 13.6 2.326zM7.994 14.521a6.6 6.6 0 0 1-3.356-.92l-.24-.144-2.494.654.666-2.433-.156-.251a6.56 6.56 0 0 1-1.007-3.505c0-3.626 2.957-6.584 6.591-6.584a6.56 6.56 0 0 1 4.66 1.931 6.56 6.56 0 0 1 1.928 4.66c-.004 3.639-2.961 6.592-6.592 6.592m3.615-4.934c-.197-.099-1.17-.578-1.353-.646-.182-.065-.315-.099-.445.099-.133.197-.513.646-.627.775-.114.133-.232.148-.43.05-.197-.1-.836-.308-1.592-.985-.59-.525-.985-1.175-1.103-1.372-.114-.198-.011-.304.088-.403.087-.088.197-.232.296-.346.1-.114.133-.198.198-.33.065-.134.034-.248-.015-.347-.05-.099-.445-1.076-.612-1.47-.16-.389-.323-.335-.445-.34-.114-.007-.247-.007-.38-.007a.73.73 0 0 0-.529.247c-.182.198-.691.677-.691 1.654s.71 1.916.81 2.049c.098.133 1.394 2.132 3.383 2.992.47.205.84.326 1.129.418.475.152.904.129 1.246.08.38-.058 1.171-.48 1.338-.943.164-.464.164-.86.114-.943-.049-.084-.182-.133-.38-.232"
                />
              </svg>
            </div>
            <p class="mt-1 text-black">+254 796 309986</p>
          </div>

          <!-- location -->
          <div
            class="flex justify-start items-start lg:flex lg:justify-start lg:items-start gap-2 px-3"
          >
            <div
              class="rounded-full bg-gray-200 p-2 hover:bg-white"
              title="Seasonal Jobs ltd. 128 City Road, London."
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="#2E7D32"
                class="bi bi-geo-alt"
                viewBox="0 0 16 16"
              >
                <path
                  d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10"
                />
                <path
                  d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6"
                />
              </svg>
            </div>
            <p class="mt-1 text-black">
              Seasonal Jobs ltd. 128 City Road, London.
            </p>
          </div>
        </div>
      </div>
      
        <div
          class="grid grid-cols-1 justify-content-center place-content-center bg-gray-100 sm:grid sm:grid-cols-3 sm:justify-content-center sm:place-content-center px-10 lg:px-20 gap-10 lg:gap-16 py-10"
        >
          <div
            class="flex flex-col justify-center items-center lg:grid lg:grid-cols-1 lg:justify-content-center lg:place-content-center space-y-3"
          >
            <ul
              class="flex flex-col justify-center items-center lg:flex lg:flex-col lg:justify-center lg:items-center space-y-2"
            >
              <li
                class="hover:underline hover:font-bold hover:text-black text-black"
              >
                <router-link to="/register">Register</router-link>
              </li>
              <li
                class="hover:underline hover:font-bold hover:text-black text-black"
              >
                <a href="http://www.youthfund.go.ke" target="_blank"
                  >YouthFund</a
                >
              </li>
            </ul>
          </div>
          <div
            class="flex flex-col justify-center items-center lg:grid lg:grid-cols-1 lg:justify-content-center lg:place-content-center space-y-3"
          >
            <ul
              class="flex flex-col justify-center items-center lg:flex lg:flex-col lg:justify-center lg:items-center space-y-2"
            >
              <li
                class="hover:underline hover:font-bold hover:text-black text-black"
              >
                <router-link to="/contact">FAQs</router-link>
              </li>
              <li
                class="hover:underline hover:font-bold hover:text-black text-black"
              >
                <router-link to="/contact">Support</router-link>
              </li>
            </ul>
          </div>
          <div
            class="flex flex-col justify-center items-center lg:flex lg:flex-col lg:justify-center lg:items-center space-y-3"
          >
            <ul
              class="flex flex-col justify-center items-center lg:flex lg:flex-col lg:justify-center lg:items-center space-y-2"
            >
              <li
                class="hover:underline hover:font-bold hover:text-black text-black"
              >
                <router-link to="/tcs">Terms of Use</router-link>
              </li>
              <li
                class="hover:underline hover:font-bold hover:text-black text-black"
              >
                <router-link to="/privacypolicy">Privacy Policy</router-link>
              </li>
            </ul>
          </div>
        </div>

        <!-- <footercalltoaction /> -->
        <hr />
        <!-- bottom part -->
        <div
          class="grid grid-cols-1 justify-center items-center md:grid md:grid-cols-1 md:justify-between md:items-center lg:grid lg:grid-cols-1 lg:justify-between lg:items-center mx-5 py-5 space-y-3"
        >
          <!-- bottom_right part -->
          <div
            class="grid grid-cols-1 justify-center items-center text-gray-500 space-y-2"
          >
            <div
              class="flex justify-center items-center lg:flex lg:justify-center lg:items-center space-x-1"
            >
              &copy;2024. All Rights Reserved
            </div>
            <p
              class="flex justify-center items-center lg:flex lg:justify-center lg:items-center"
            >
              Created by Lish Technologies
            </p>
          </div>
        </div>
      
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped></style>
