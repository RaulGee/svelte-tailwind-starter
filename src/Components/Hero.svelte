<script>
  import { link } from 'svelte-routing';
</script>

  <main>
    <div>
      <!-- Hero card -->
      <div class="relative">
        <div class="absolute inset-x-0 bottom-0 h-1/2 bg-gray-100"></div>
        <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
          <div class="relative shadow-xl sm:rounded-2xl sm:overflow-hidden">
            <div class="absolute inset-0">
              <video class="h-full w-full object-cover" autoplay muted loop>
                <source src="images/HeroVideo.mp4" type="video/mp4">
              </video>
              <div class="absolute inset-0 bg-gray-700" style="mix-blend-mode: multiply;"></div>
            </div>
            <div class="relative px-4 py-16 sm:px-6 sm:py-24 lg:py-32 lg:px-8">
              <h1 class="text-center text-4xl font-extrabold tracking-tight sm:text-5xl lg:text-6xl">
                <span class="block text-white">Hello, I'm <span class="text-blue-700">Raul Guirado</span></span>
                <span class="block text-indigo-200">Front End Web Developer</span>
              </h1>
              <p class="mt-6 max-w-lg mx-auto text-center text-xl text-indigo-200 sm:max-w-3xl">
                Let's work together to make your next project come to life!
              </p>
              <div class="mt-10 max-w-sm mx-auto sm:max-w-none sm:flex sm:justify-center">
                <div class="space-y-0 sm:space-y-0 sm:mx-auto sm:inline-grid sm:gap-5">
                  <a href="/mywork" use:link class="flex items-center justify-center px-4 py-3 border-4 border-transparent text-xl font-semibold rounded-md shadow-sm text-blue-100 bg-blue-700 hover:bg-blue-600 hover:border-transparent hover:text-blue-100 sm:px-8 hover:no-underline">
                    View My Work
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Logo cloud -->
      <div class="bg-gray-100">
        <div class="max-w-7xl mx-auto py-16 px-4 sm:px-6 lg:px-8">
          <p class="text-center text-sm font-semibold uppercase text-gray-500 tracking-wide">
            Skills & Knowledge
          </p>
          <div class="mt-6 grid grid-cols-2 gap-8 md:grid-cols-6 lg:grid-cols-5">
            <div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
              <svg class="w-20 h-20 md:w-24 md:h-24" viewBox="0 0 452 520">
                <title>HTML</title>
                <path fill='RGB(227,79,38)' d='M 41,460 L 0,0 451,0 410,460 225,512'/>
                <path fill='RGB(239,101,42)' d='M 226,472 L 375,431 410,37 226,37'/>
                <path fill='RGB(236,237,238)' d='M 226,208 L 151,208 146,150 226,150 226,94 84,94 99,265 226,265 z M 226,355 L162,338 158,293 102,293 109,382 226,414 z'/>
                <path fill='RGB(255,255,255)' d='M 226,265 L 295,265 288,338 226,355 226,414 341,382 357,208 226,208 z M 226,94 L226,150 362,150 367,94 z'/>
              </svg>
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
              <svg class="w-20 h-20 md:w-24 md:h-24" viewBox="0 0 452 520">
                <title>CSS</title>
                <path fill='RGB(12,115,184)' d='M 41,460 L 0,0 451,0 410,460 225,512'/>
                <path fill='RGB(48,169,220)' d='M 226,472 L 375,431 410,37 226,37'/>
                <path fill='RGB(236,237,238)' d='M 226,208 L 94,208 99,265 226,265 z M 226,94 L 84,94 89,150 226,150 z M 226,355 L 102,322 109,382 226,414 z'/>
                <path fill='RGB(255,255,255)' d='M 226,265 L 295,265 288,338 226,355 226,414 341,382 367,94 226,94 226,150 306,150 300,208 226,208 z'/>
              </svg>
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
              <svg class="w-20 h-20 md:w-24 md:h-24" viewBox="0 0 452 520">
                <title>Javascript</title>
                <path fill='RGB(229,162,40)' d='M 0,0 L 451,0 410,460 225,512 41,460'/>
                <path fill='RGB(241,191,38)' d='M 226,472 L375,431 410,37 226,37'/>
                <path fill='RGB(236,237,238)' d='M 226,94 L 113,94 102,265 226,265 226,208 160,208 165,150 226,150 z M 226,355 L 162,338 158,293 102,293 109,382 226,414 z'/>
                <path fill='RGB(255,255,255)' d='M 226,265 L 295,265 288,338 226,355 226,414 341,382 357,208 226,208 z M 226,94 L 339,94 357,180 301,180 293,150 226,150 z'/>
              </svg>
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 md:col-start-1 lg:col-span-1">
              <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" class="w-20 h-20 md:w-24 md:h-24" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" 
              preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 308">
                <path d="M239.682 40.707C211.113-.182 154.69-12.301 113.895 13.69L42.247 59.356a82.198 82.198 0 0 0-37.135 55.056a86.566 86.566 0 0 0 8.536 55.576a82.425 82.425 0 0 0-12.296 30.719a87.596 87.596 0 0 0 14.964 66.244c28.574 40.893 84.997 53.007 125.787 27.016l71.648-45.664a82.182 82.182 0 0 0 37.135-55.057a86.601 86.601 0 0 0-8.53-55.577a82.409 82.409 0 0 0 12.29-30.718a87.573 87.573 0 0 0-14.963-66.244" fill="#FF3E00"/><path d="M106.889 270.841c-23.102 6.007-47.497-3.036-61.103-22.648a52.685 52.685 0 0 1-9.003-39.85a49.978 49.978 0 0 1 1.713-6.693l1.35-4.115l3.671 2.697a92.447 92.447 0 0 0 28.036 14.007l2.663.808l-.245 2.659a16.067 16.067 0 0 0 2.89 10.656a17.143 17.143 0 0 0 18.397 6.828a15.786 15.786 0 0 0 4.403-1.935l71.67-45.672a14.922 14.922 0 0 0 6.734-9.977a15.923 15.923 0 0 0-2.713-12.011a17.156 17.156 0 0 0-18.404-6.832a15.78 15.78 0 0 0-4.396 1.933l-27.35 17.434a52.298 52.298 0 0 1-14.553 6.391c-23.101 6.007-47.497-3.036-61.101-22.649a52.681 52.681 0 0 1-9.004-39.849a49.428 49.428 0 0 1 22.34-33.114l71.664-45.677a52.218 52.218 0 0 1 14.563-6.398c23.101-6.007 47.497 3.036 61.101 22.648a52.685 52.685 0 0 1 9.004 39.85a50.559 50.559 0 0 1-1.713 6.692l-1.35 4.116l-3.67-2.693a92.373 92.373 0 0 0-28.037-14.013l-2.664-.809l.246-2.658a16.099 16.099 0 0 0-2.89-10.656a17.143 17.143 0 0 0-18.398-6.828a15.786 15.786 0 0 0-4.402 1.935l-71.67 45.674a14.898 14.898 0 0 0-6.73 9.975a15.9 15.9 0 0 0 2.709 12.012a17.156 17.156 0 0 0 18.404 6.832a15.841 15.841 0 0 0 4.402-1.935l27.345-17.427a52.147 52.147 0 0 1 14.552-6.397c23.101-6.006 47.497 3.037 61.102 22.65a52.681 52.681 0 0 1 9.003 39.848a49.453 49.453 0 0 1-22.34 33.12l-71.664 45.673a52.218 52.218 0 0 1-14.563 6.398" fill="#FFF"/>
              <title>Svelte</title>
              </svg>
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 md:col-start-3 lg:col-span-1">
              <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" class="w-20 h-20 md:w-24 md:h-24" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 154"><defs><linearGradient x1="-2.778%" y1="32%" x2="100%" y2="67.556%" id="IconifyId-177a54f4056-cc3432-50"><stop stop-color="#2298BD" offset="0%"/><stop stop-color="#0ED7B5" offset="100%"/></linearGradient></defs>
                <path d="M128 0C93.867 0 72.533 17.067 64 51.2C76.8 34.133 91.733 27.733 108.8 32c9.737 2.434 16.697 9.499 24.401 17.318C145.751 62.057 160.275 76.8 192 76.8c34.133 0 55.467-17.067 64-51.2c-12.8 17.067-27.733 23.467-44.8 19.2c-9.737-2.434-16.697-9.499-24.401-17.318C174.249 14.743 159.725 0 128 0zM64 76.8C29.867 76.8 8.533 93.867 0 128c12.8-17.067 27.733-23.467 44.8-19.2c9.737 2.434 16.697 9.499 24.401 17.318C81.751 138.857 96.275 153.6 128 153.6c34.133 0 55.467-17.067 64-51.2c-12.8 17.067-27.733 23.467-44.8 19.2c-9.737-2.434-16.697-9.499-24.401-17.318C110.249 91.543 95.725 76.8 64 76.8z" fill="url(#IconifyId-177a54f4056-cc3432-50)"/>
              <title>TailwindCSS</title>
              </svg>
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 md:col-start-5 lg:col-span-1">
              <svg class="w-20 h-20 md:w-24 md:h-24" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 256">
                <path d="M251.172 116.594L139.4 4.828c-6.433-6.437-16.873-6.437-23.314 0l-23.21 23.21l29.443 29.443c6.842-2.312 14.688-.761 20.142 4.693c5.48 5.489 7.02 13.402 4.652 20.266l28.375 28.376c6.865-2.365 14.786-.835 20.269 4.657c7.663 7.66 7.663 20.075 0 27.74c-7.665 7.666-20.08 7.666-27.749 0c-5.764-5.77-7.188-14.235-4.27-21.336l-26.462-26.462l-.003 69.637a19.82 19.82 0 0 1 5.188 3.71c7.663 7.66 7.663 20.076 0 27.747c-7.665 7.662-20.086 7.662-27.74 0c-7.663-7.671-7.663-20.086 0-27.746a19.654 19.654 0 0 1 6.421-4.281V94.196a19.378 19.378 0 0 1-6.421-4.281c-5.806-5.798-7.202-14.317-4.227-21.446L81.47 39.442l-76.64 76.635c-6.44 6.443-6.44 16.884 0 23.322l111.774 111.768c6.435 6.438 16.873 6.438 23.316 0l111.251-111.249c6.438-6.44 6.438-16.887 0-23.324" fill="#DE4C36"/>
                <title>Git</title>
              </svg>
            </div>
            <div class="col-span-1 flex justify-center md:col-span-2 md:col-start-3 lg:col-span-1">
          <svg class="w-20 h-20 md:w-24 md:h-24" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32">
            <defs><linearGradient id="IconifyId-177b9a12ff7-cdacfe-4" x1="-78" y1="525" x2="-78" y2="553" gradientTransform="translate(94 -523)" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#21c6b7"/><stop offset="1" stop-color="#4c9bbf"/>
            </linearGradient></defs>
            <path d="M22.292 11.717h-.01a.033.033 0 0 1-.017-.01a.08.08 0 0 1-.02-.068l.565-3.451l2.651 2.648L22.7 12a.069.069 0 0 1-.024.005h-.006s-.007 0-.014-.011a1.267 1.267 0 0 0-.364-.277zm3.844-.21l2.834 2.831c.589.588.883.882.991 1.222a1.355 1.355 0 0 1 .039.152l-6.772-2.864h-.011c-.027-.011-.059-.024-.059-.052s.032-.041.059-.052h.008zm3.748 5.114a5.3 5.3 0 0 1-.914 1.042l-3.194 3.19l-4.132-.86h-.022c-.036-.006-.076-.012-.076-.046a1.249 1.249 0 0 0-.479-.871c-.017-.017-.012-.043-.008-.068v-.01l.778-4.766v-.016c0-.036.011-.079.045-.079a1.265 1.265 0 0 0 .848-.486a.064.064 0 0 1 .02-.02a.1.1 0 0 1 .075.01zm-4.843 4.966l-5.253 5.248l.9-5.521v-.028c.007-.018.026-.025.045-.033h.009a1.355 1.355 0 0 0 .508-.377a.12.12 0 0 1 .066-.045a.074.074 0 0 1 .021 0zm-6.365 6.358l-.592.592l-6.546-9.451l-.008-.01a.063.063 0 0 1-.019-.044a.066.066 0 0 1 .016-.032l.007-.009c.02-.029.037-.058.056-.09l.015-.025a.1.1 0 0 1 .038-.043a.08.08 0 0 1 .053 0l7.253 1.494a.127.127 0 0 1 .056.024a.059.059 0 0 1 .014.031v.014a1.282 1.282 0 0 0 .749.844c.02.01.011.033 0 .057a.213.213 0 0 0-.011.033c-.087.553-.871 5.327-1.081 6.615zm-1.237 1.235a2.739 2.739 0 0 1-.985.752a1.459 1.459 0 0 1-.882 0c-.341-.108-.635-.4-1.224-.99l-6.574-6.567l1.717-2.661a.105.105 0 0 1 .029-.034a.078.078 0 0 1 .067 0a1.736 1.736 0 0 0 .521.077a1.786 1.786 0 0 0 .676-.137a.052.052 0 0 1 .055 0a.241.241 0 0 1 .021.024zm-10.3-7.438l-1.507-1.507l2.979-1.269a.069.069 0 0 1 .024 0c.025 0 .039.025.053.048l.01.016c.028.043.057.081.085.118l.009.012c.008.012 0 .024-.006.037zm-2.174-2.173l-1.908-1.906c-.325-.324-.56-.559-.723-.762l5.8 1.2h.022c.036.006.076.012.076.046s-.043.053-.08.068l-.017.007zM2 15.921a1.5 1.5 0 0 1 .066-.362c.108-.34.4-.634.991-1.222L5.5 11.9c.4.59 3.061 4.426 3.371 4.87l.01.013c.02.027.042.056.02.078a2 2 0 0 0-.289.385a.122.122 0 0 1-.036.045a.041.041 0 0 1-.031 0zm4.152-4.675l3.283-3.28c.309.135 1.432.609 2.436 1.033c.761.321 1.454.614 1.671.707a.08.08 0 0 1 .051.04a.073.073 0 0 1 0 .044a1.532 1.532 0 0 0-.033.315a1.46 1.46 0 0 0 .416 1.02c.022.021 0 .053-.019.081l-.01.015l-3.333 5.158a.108.108 0 0 1-.031.036a.081.081 0 0 1-.063 0a1.656 1.656 0 0 0-.4-.054a2.2 2.2 0 0 0-.381.046a.044.044 0 0 1-.039 0a.146.146 0 0 1-.033-.037zM10.1 7.3l4.251-4.246c.589-.588.883-.882 1.224-.99a1.459 1.459 0 0 1 .882 0c.341.108.635.4 1.224.99l.921.92l-3.025 4.681a.127.127 0 0 1-.03.035a.08.08 0 0 1-.066 0a1.652 1.652 0 0 0-.459-.065a1.533 1.533 0 0 0-.945.336c-.02.019-.049.007-.074 0c-.395-.175-3.466-1.472-3.903-1.661zm9.143-2.685l2.792 2.789l-.672 4.16v.011a.082.082 0 0 1-.006.028c-.007.015-.021.018-.036.021h-.016a1.329 1.329 0 0 0-.385.195l-.014.013a.043.043 0 0 1-.03.018a.065.065 0 0 1-.031-.005l-4.253-1.805h-.009c-.027-.011-.059-.024-.059-.052a1.6 1.6 0 0 0-.217-.653l-.009-.015c-.021-.034-.043-.069-.026-.1zM16.367 10.9l3.987 1.687a.092.092 0 0 1 .055.042a.072.072 0 0 1 0 .041a1.045 1.045 0 0 0-.021.192v.112c0 .027-.029.039-.055.05h-.009c-.631.269-8.868 3.777-8.88 3.777a.048.048 0 0 1-.038-.012c-.022-.021 0-.053.019-.081l.01-.015l3.277-5.067l.006-.009c.019-.031.041-.065.076-.065l.033.005a1.4 1.4 0 0 0 .206.02a1.483 1.483 0 0 0 1.236-.655a.113.113 0 0 1 .024-.029a.078.078 0 0 1 .074.007zM11.8 17.611l8.977-3.824a.037.037 0 0 1 .025.013a1.372 1.372 0 0 0 .13.112l.02.013c.018.011.037.022.038.041v.018l-.77 4.716v.019c0 .037-.01.079-.045.079a1.262 1.262 0 0 0-1 .618v.006a.1.1 0 0 1-.037.042a.088.088 0 0 1-.051 0l-7.159-1.475s-.12-.377-.128-.378z" fill="url(#IconifyId-177b9a12ff7-cdacfe-4)"/>
            <title>Netlify</title>
          </svg>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- More main page content here... -->
  </main>
