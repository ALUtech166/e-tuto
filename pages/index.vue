<template>
  <div>
    <section class="lg:tw-mx-12 tw-mx-8">
      <div class="bg-image tw-py-20 tw-rounded-lg tw-shadow-2xl tw-shadow-gray-900 tw-h-full tw-w-full">
        <div class="tw-w-full tw-h-full tw-flex tw-flex-col lg:tw-flex-row tw-p-12">
          <div class="tw-text-left tw-px-8 tw-h-full">
            <h1 class="tw-text-black tw-text-5xl tw-font-extrabold lg:tw-w-3/4">
              Expert Online Tutoring
            </h1>
            <h1 class="text-color tw-mt-4 tw-text-5xl tw-font-extrabold lg:tw-w-3/4">
              for College and High School Success
            </h1>

            <p class="tw-text-black tw-text-xl lg:tw-w-3/4 tw-mt-4">
              Unlock your academic potential with ScholarLink, your premier destination for personalized online tutoring
              services.
            </p>

          </div>

          <v-img class="tw-rounded-lg tw-cursor-pointer tw-tranform tw-translate-x-10"
            src="https://img.freepik.com/free-photo/happy-successful-business-leader-signing-agreement_74855-2307.jpg?w=740&t=st=1691964166~exp=1691964766~hmac=d5d7276414cb4e587af8d6041fda464481b830a76440ded812c21257a469136e"
            width="350px"></v-img>
        </div>
      </div>

      <div
        class="bg-color tw-shadow-2xl tw-rounded-lg tw-shadow-gray-800 lg:tw-mx-24 tw-mx-8 tw-transform tw--translate-y-20 tw-bottom-0 tw-left-0 tw-px-8 tw-py-6">



        <!-- component -->
        <div class="tw-flex tw-flex-col tw-p-4 tw-py-8 tw-m-h-screen">

          <div
            class="tw-bg-white tw-shadow-2xl tw-items-center tw-justify-between tw-w-full tw-flex tw-rounded-full tw-shadow-gray-900 tw-p-3 tw-mb-4 tw-sticky"
            style="top: 5px">



            <v-autocomplete v-model="selectedItem1" :items="items1" label="Item 1" />
            <v-autocomplete v-model="selectedItem2" :items="items2" label="Item 2" />
            <v-autocomplete v-model="selectedItem3" :items="items3" label="Item 3" />
            <div class="bg-color tw-p-4 hover:tw-bg-blue-400 tw-cursor-pointer tw-mx-2 tw-rounded-full">

              <svg class="tw-w-6 tw-h-6 tw-text-white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
                fill="currentColor">
                <path fill-rule="evenodd"
                  d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                  clip-rule="evenodd" />
              </svg>

            </div>

          </div>



        </div>

      </div>
    </section>


    <section class="lg:tw-mx-12 tw-mx-8 tw-p-6">
      <v-row>
        <v-col class="" md="4" lg="4">
          <div class="">
            <div class="tw-bg-white tw-rounded-lg">

              <div class=" tw-p-4 tw-pt-12">
                <h1 class="text-color tw-text-4xl tw-font-extrabold tw-text-justify tw-pt-24">
                  We Choose Use
                </h1>

                <p class="tw-text-sm tw-text-gray-600 tw-font-medium tw-text-justify tw-pt-3">
                  Experience the forefront of education through e-tuto—an innovative platform seamlessly blending dynamic
                  interactivity with expert guidance
                </p>
              </div>

            </div>
          </div>
        </v-col>
        <v-col class="" cols="12" md="4" lg="4">

          <div class="">
            <div class="tw-flex tw-flex-col">

              <div class="tw-flex lg:tw-flex-row tw-flex-col tw-gap-4 tw-shadow-gray-400 tw-shadow-xl tw-p-6 tw-rounded-lg">
                <svg width="75" fill="#000000" version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 31.459 31.46" xml:space="preserve"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <g> <path d="M8.946,4.912l-0.364-0.25l17.209-1.868L25.77,2.601L8.335,4.493L8.034,4.285l17.409-1.903l-0.021-0.193L7.789,4.118 l-0.334-0.23l17.679-1.956l-0.021-0.193L7.208,3.719L6.835,3.462l17.907-1.991l-0.021-0.192L6.592,3.294L6.187,3.016l0.579-0.059 L25.19,0.953L24.514,0L4.368,2.135v0.292v0.778v25.659l3.649,2.575v0.021l19.072-1.935l0.004-26.453L8.946,4.912z M23.981,14.762 l-11.365,1.236v-6.4l11.365-1.237V14.762z"></path> </g> </g></svg>
                <div class="">
                  <h1 class="text-color tw-text-xl tw-font-extrabold tw-text-justify">
                    Leadership Excellence
                  </h1>
                  <span class="tw-text-sm tw-text-gray-600 tw-font-medium tw-text-justify tw-pt-3">
                    Choose e-tuto for Business Leadership and unlock a transformative learning journey. 
                  </span>
                </div>

              </div>


              <div class="tw-flex lg:tw-flex-row tw-flex-col tw-gap-4 tw-shadow-gray-400 tw-shadow-xl tw-p-6 tw-rounded-lg tw-mt-8">
              <svg width="75" fill="#000000" version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 27.32 27.32" xml:space="preserve"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <g> <g> <path d="M1.29,25.669V25.64l4.825-9.713c0.116,0.032,0.237,0.058,0.364,0.058c0.193,0,0.375-0.045,0.54-0.118l4.248,4.521 c-0.13,0.203-0.208,0.443-0.208,0.705c0,0.725,0.588,1.312,1.313,1.312s1.313-0.589,1.313-1.312c0-0.403-0.185-0.759-0.47-1 l2.58-5.314h0.462v-0.16h-0.384l2.264-4.664c0.086,0.018,0.174,0.026,0.266,0.026c0.26,0,0.5-0.076,0.703-0.206l4.549,4.29 c-0.105,0.188-0.17,0.401-0.17,0.634c0,0.725,0.588,1.312,1.312,1.312s1.312-0.588,1.312-1.312c0-0.725-0.588-1.313-1.312-1.313 c-0.259,0-0.499,0.077-0.701,0.206l-4.55-4.289c0.104-0.189,0.169-0.402,0.169-0.633c0-0.727-0.587-1.315-1.312-1.315 c-0.698,0-1.264,0.547-1.305,1.233h-0.021v0.161h0.021c0.021,0.368,0.195,0.694,0.461,0.919l-4.921,10.141 c-0.085-0.019-0.175-0.027-0.266-0.027c-0.23,0-0.444,0.064-0.632,0.169L7.523,15.46c0.146-0.191,0.237-0.426,0.258-0.682h0.544 v-0.16H7.787c-0.03-0.701-0.601-1.26-1.308-1.26c-0.708,0-1.279,0.559-1.308,1.26h-0.15v0.16h0.156 c0.027,0.322,0.163,0.611,0.378,0.825l-2.687,5.407H2.377v0.162h0.411L1.29,24.189V0.364H0v26.592h27.32v-1.287H1.29z"></path> <rect x="26.168" y="2.581" width="0.323" height="0.16"></rect> <rect x="18.238" y="2.581" width="0.66" height="0.16"></rect> <rect x="3.699" y="2.581" width="0.661" height="0.16"></rect> <rect x="19.561" y="2.581" width="0.66" height="0.16"></rect> <rect x="5.021" y="2.581" width="0.661" height="0.16"></rect> <rect x="14.273" y="2.581" width="0.66" height="0.16"></rect> <rect x="12.951" y="2.581" width="0.661" height="0.16"></rect> <rect x="16.916" y="2.581" width="0.661" height="0.16"></rect> <rect x="15.596" y="2.581" width="0.66" height="0.16"></rect> <rect x="2.376" y="2.581" width="0.662" height="0.16"></rect> <rect x="8.985" y="2.581" width="0.661" height="0.16"></rect> <rect x="24.846" y="2.581" width="0.661" height="0.16"></rect> <rect x="20.881" y="2.581" width="0.661" height="0.16"></rect> <rect x="11.628" y="2.581" width="0.662" height="0.16"></rect> <rect x="10.308" y="2.581" width="0.661" height="0.16"></rect> <rect x="22.203" y="2.581" width="0.66" height="0.16"></rect> <rect x="6.343" y="2.581" width="0.66" height="0.16"></rect> <rect x="23.525" y="2.581" width="0.66" height="0.16"></rect> <rect x="7.664" y="2.581" width="0.661" height="0.16"></rect> <rect x="1.394" y="2.581" width="0.323" height="0.16"></rect> <rect x="26.327" y="8.587" width="0.321" height="0.161"></rect> <rect x="23.684" y="8.587" width="0.662" height="0.161"></rect> <rect x="22.361" y="8.587" width="0.66" height="0.161"></rect> <rect x="7.823" y="8.587" width="0.661" height="0.161"></rect> <rect x="6.501" y="8.587" width="0.661" height="0.161"></rect> <rect x="10.466" y="8.587" width="0.66" height="0.161"></rect> <rect x="21.04" y="8.587" width="0.662" height="0.161"></rect> <rect x="11.787" y="8.587" width="0.662" height="0.161"></rect> <rect x="25.005" y="8.587" width="0.661" height="0.161"></rect> <rect x="9.144" y="8.587" width="0.661" height="0.161"></rect> <rect x="15.752" y="8.587" width="0.661" height="0.161"></rect> <rect x="2.535" y="8.587" width="0.662" height="0.161"></rect> <rect x="14.432" y="8.587" width="0.661" height="0.161"></rect> <rect x="13.11" y="8.587" width="0.661" height="0.161"></rect> <rect x="3.857" y="8.587" width="0.661" height="0.161"></rect> <rect x="19.718" y="8.587" width="0.661" height="0.161"></rect> <rect x="5.179" y="8.587" width="0.661" height="0.161"></rect> <rect x="1.552" y="8.587" width="0.322" height="0.161"></rect> <rect x="26.168" y="14.617" width="0.323" height="0.16"></rect> <rect x="11.628" y="14.617" width="0.662" height="0.16"></rect> <rect x="12.951" y="14.617" width="0.661" height="0.16"></rect> <rect x="14.273" y="14.617" width="0.66" height="0.16"></rect> <rect x="18.238" y="14.617" width="0.66" height="0.16"></rect> <rect x="22.203" y="14.617" width="0.66" height="0.16"></rect> <rect x="19.561" y="14.617" width="0.66" height="0.16"></rect> <rect x="10.308" y="14.617" width="0.661" height="0.16"></rect> <rect x="16.916" y="14.617" width="0.661" height="0.16"></rect> <rect x="20.881" y="14.617" width="0.661" height="0.16"></rect> <rect x="2.376" y="14.617" width="0.662" height="0.16"></rect> <rect x="3.699" y="14.617" width="0.661" height="0.16"></rect> <rect x="8.985" y="14.617" width="0.661" height="0.16"></rect> <rect x="1.394" y="14.617" width="0.323" height="0.16"></rect> <rect x="26.168" y="21.011" width="0.323" height="0.162"></rect> <rect x="3.699" y="21.011" width="0.661" height="0.162"></rect> <rect x="14.273" y="21.011" width="0.66" height="0.162"></rect> <rect x="10.308" y="21.011" width="0.661" height="0.162"></rect> <rect x="5.021" y="21.011" width="0.661" height="0.162"></rect> <rect x="6.343" y="21.011" width="0.661" height="0.162"></rect> <rect x="7.665" y="21.011" width="0.661" height="0.162"></rect> <rect x="15.596" y="21.011" width="0.66" height="0.162"></rect> <rect x="8.986" y="21.011" width="0.661" height="0.162"></rect> <rect x="22.204" y="21.011" width="0.659" height="0.162"></rect> <rect x="23.525" y="21.011" width="0.66" height="0.162"></rect> <rect x="24.848" y="21.011" width="0.66" height="0.162"></rect> <rect x="19.561" y="21.011" width="0.662" height="0.162"></rect> <rect x="18.238" y="21.011" width="0.66" height="0.162"></rect> <rect x="20.882" y="21.011" width="0.661" height="0.162"></rect> <rect x="16.917" y="21.011" width="0.662" height="0.162"></rect> <rect x="1.394" y="21.011" width="0.323" height="0.162"></rect> </g> </g> </g></svg>                <div class="">
                  <h1 class="text-color tw-text-xl tw-font-extrabold tw-text-justify">
                    Leadership Excellence
                  </h1>
                  <span class="tw-text-sm tw-text-gray-600 tw-font-medium tw-text-justify tw-pt-3">
                    Choose e-tuto for Business Leadership and unlock a transformative learning journey. 
                  </span>
                </div>

              </div>



            </div>
          </div>
        </v-col>
        <v-col class="" cols="12" md="4" lg="4">

          <div>
            <div class="tw-flex tw-flex-col">

              <div class="tw-flex lg:tw-flex-row tw-flex-col tw-gap-4 tw-shadow-gray-400 tw-shadow-xl tw-p-6 tw-rounded-lg">
              <svg width="75" fill="#000000" version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 30.49 30.49" xml:space="preserve"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <g> <g> <polygon points="26.688,24.336 26.688,23.784 28.512,23.784 28.512,23.051 1.979,23.051 1.979,23.784 1.993,23.784 1.993,29.76 1.979,29.76 1.979,30.49 28.512,30.49 28.512,29.76 26.688,29.76 26.688,29.434 3.844,29.434 3.844,29.195 3.813,29.195 3.813,29.057 26.688,29.057 26.688,28.749 3.826,28.749 3.826,28.635 3.813,28.635 3.813,28.496 3.826,28.496 3.826,28.445 26.688,28.445 26.688,28.023 3.785,28.023 3.785,27.945 3.771,27.945 3.771,27.807 3.785,27.807 3.785,27.721 26.688,27.721 26.688,27.338 3.764,27.338 3.764,27.036 26.688,27.036 26.688,26.673 3.764,26.673 3.764,26.371 26.688,26.371 26.688,25.989 3.804,25.989 3.804,25.686 26.688,25.686 26.688,25.303 3.785,25.303 3.785,25.001 26.688,25.001 26.688,24.639 3.785,24.639 3.785,24.336 "></polygon> <polygon points="25.151,22.17 25.141,22.17 25.141,18.409 25.151,18.409 25.151,17.948 14.419,17.948 4.648,17.948 4.648,18.409 6.056,18.409 6.056,18.734 23.947,18.734 23.947,19.037 6.056,19.037 6.056,19.398 23.947,19.398 23.947,19.702 6.056,19.702 6.056,20.084 23.906,20.084 23.906,20.25 23.932,20.25 23.932,20.387 6.056,20.387 6.056,20.77 23.926,20.77 23.926,20.896 23.932,20.896 23.932,21.033 23.926,21.033 23.926,21.072 6.056,21.072 6.056,21.434 23.926,21.434 23.926,21.585 23.932,21.585 23.932,21.723 23.926,21.723 23.926,21.736 6.056,21.736 6.056,22.17 4.648,22.17 4.648,22.63 25.151,22.63 "></polygon> <path d="M8.292,17.382h13.901h0.001c0.652,0,1.201-0.323,1.542-0.909c0.449-0.771,0.444-1.878-0.015-2.688l-0.119-0.21 c-0.444-0.794-1.487-2.652-2.565-4.238c-0.363-0.531-0.727-1.027-1.056-1.477c-0.528-0.719-1.185-1.613-1.188-1.878 c0.039-1.165,0.012-3.922,0.002-4.773h0.688V0h-8.701v1.208h0.912c-0.011,0.851-0.036,3.607,0.004,4.771 c-0.006,0.267-0.663,1.161-1.191,1.88c-0.329,0.449-0.693,0.945-1.055,1.476c-1.078,1.585-2.12,3.444-2.567,4.238l-0.117,0.21 c-0.46,0.811-0.465,1.917-0.016,2.689C7.092,17.059,7.641,17.382,8.292,17.382z M7.637,14.277l0.119-0.215 c0.439-0.782,1.469-2.613,2.523-4.164c0.354-0.522,0.71-1.008,1.034-1.449c0.921-1.257,1.401-1.938,1.383-2.501 c-0.036-1.037-0.017-3.449-0.005-4.491h5.106c0.011,1.042,0.031,3.454-0.006,4.491c-0.02,0.562,0.461,1.245,1.383,2.501 c0.322,0.441,0.681,0.927,1.035,1.449c1.054,1.55,2.082,3.382,2.521,4.164l0.121,0.215c0.281,0.499,0.29,1.229,0.02,1.692 c-0.16,0.274-0.388,0.413-0.679,0.413h-13.9c-0.289,0-0.518-0.139-0.678-0.413C7.345,15.505,7.353,14.776,7.637,14.277z"></path> <path d="M9.109,16.133h0.87h3.229h4.07h3.251h0.852c0.385,0,0.705-0.19,0.908-0.535c0.263-0.454,0.26-1.104-0.011-1.581 l-0.069-0.125c-0.263-0.465-0.875-1.559-1.508-2.49c-0.164-0.24-0.324-0.461-0.479-0.672h-9.954 c-0.155,0.211-0.314,0.433-0.479,0.672c-0.634,0.931-1.247,2.024-1.509,2.49l-0.07,0.125c-0.271,0.477-0.272,1.126-0.009,1.581 C8.404,15.942,8.726,16.133,9.109,16.133z"></path> </g> </g> </g></svg>                <div class="">
                  <h1 class="text-color tw-text-xl tw-font-extrabold tw-text-justify">
                    Leadership Excellence
                  </h1>
                  <span class="tw-text-sm tw-text-gray-600 tw-font-medium tw-text-justify tw-pt-3">
                    Choose e-tuto for Business Leadership and unlock a transformative learning journey. 
                  </span>
                </div>

              </div>


              <div class="tw-flex lg:tw-flex-row tw-flex-col tw-gap-4 tw-shadow-gray-400 tw-shadow-xl tw-p-6 tw-rounded-lg tw-mt-8">
                <svg width="75" fill="#000000" version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 31.771 31.771" xml:space="preserve"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <g> <g> <path d="M31.771,20.319c0-0.474-0.279-0.87-0.676-1.066V11.9c0.09-0.034,0.146-0.119,0.145-0.214c0-0.095-0.062-0.179-0.149-0.21 L15.92,6.125c-0.194-0.069-0.406-0.069-0.601,0L0.15,11.477c-0.089,0.031-0.149,0.115-0.15,0.21s0.056,0.18,0.144,0.214 l15.148,5.896c0.211,0.081,0.444,0.081,0.655,0l14.102-5.492v6.947c-0.396,0.195-0.675,0.594-0.675,1.065 c0,0.492,0.3,0.919,0.729,1.102c-0.429,0.847-0.729,2.585-0.729,3.081c0,0.661,0.537,1.197,1.198,1.197 c0.66,0,1.197-0.536,1.197-1.197c0-0.496-0.301-2.234-0.729-3.081C31.47,21.238,31.771,20.811,31.771,20.319z"></path> <path d="M4.888,14.87c0.001,1.696,0.002,3.692,0.002,4.009c0,3.158,4.753,5.729,10.73,5.89c5.976-0.161,10.729-2.729,10.729-5.89 c0-0.315,0-2.312,0.002-4.009l-10.406,4.051c-0.211,0.082-0.444,0.082-0.655,0L4.888,14.87z"></path> </g> </g> </g></svg>                <div class="">
                  <h1 class="text-color tw-text-xl tw-font-extrabold tw-text-justify">
                    Leadership Excellence
                  </h1>
                  <span class="tw-text-sm tw-text-gray-600 tw-font-medium tw-text-justify tw-pt-3">
                    Choose e-tuto for Business Leadership and unlock a transformative learning journey. 
                  </span>
                </div>

              </div>



            </div>
          </div>
        </v-col>

      </v-row>



    </section>


    <section class="lg:tw-mx-12 tw-mx-8 tw-p-6 tw-pt-12">

      <v-row>
        <v-col class="" md="4" lg="4">
          <div class="">
            <div class="tw-bg-white tw-rounded-lg">

              <div class=" tw-p-4 tw-pt-4">
                <h1 class="text-color tw-text-4xl tw-font-extrabold tw-text-justify tw-pt-12">
                  We Create a World Class Development and Branding
                </h1>

                <p class="tw-text-md tw-text-gray-600 tw-font-medium tw-text-justify tw-pt-3">
                  Immerse yourself in the world of creativity through e-tuto's Creative Arts program. With our dynamic and interactive platform, expert artists guide you in mastering various disciplines. Whether it's painting, music, or digital design, e-tuto provides a space to nurture your artistic talent and explore innovative techniques.
                </p>

                <button
                class="tw-group bg-color tw-shadow-lg tw-rounded-lg tw-relative tw-h-12 tw-mt-4 tw-cursor-pointer hover:tw-transform hover:tw-translate-x-2 hover:tw-transition-transform hover:tw-duration-300 hover:tw-shadow-2xl-blue-600 hover:tw-shadow-2xl-lg tw-w-48 tw-overflow-hidden tw-rounded-lg tw-text-lg tw-shadow-2xl-2xl">
                <div
                  class="tw-absolute tw-inset-0 tw-w-full bg-color tw--transition-all tw-duration-[250ms] tw-ease-out group-hover:tw-w-full">
                </div>
                <span class="tw-relative tw-inline-flex tw-items-center tw-gap-2 tw-text-white group-hover:tw-text-white">
                  Get Started

                </span>
              </button>
              </div>

            </div>
          </div>
        </v-col>
        <v-col class="" cols="12" md="4" lg="4">

          <div class="">
            <v-img class="tw-rounded-lg tw-shadow-gray-400 tw-shadow-xl tw-cursor-pointer tw-tranform tw-translate-x-10"
            src="https://img.freepik.com/premium-photo/teacher-helping-student-class_236854-36174.jpg?w=360"
            width="350px"></v-img>
          </div>
        </v-col>
        <v-col class="" cols="12" md="4" lg="4">

          <div class="tw-mt-24">
            <v-img class="tw-rounded-lg tw-shadow-gray-400 tw-shadow-xl tw-cursor-pointer"
            src="https://img.freepik.com/free-photo/content-black-woman-with-short-hairstyle-dressed-denim-sarafan_273609-44942.jpg?w=360&t=st=1692383742~exp=1692384342~hmac=7d2c02ac977068f43970c3460f50534a3caadb82f0031e49e84efb66b24cc0aa"
            width="350px" height="425px"></v-img>
          
          </div>
        </v-col>

      </v-row>



    </section>

  </div>
</template>
<script>
import AOS from 'aos';
import 'aos/dist/aos.css';

export default {
  data() {
    return {
      initialized: false,
      posts: [],
      selectedItem1: null,
      selectedItem2: null,
      selectedItem3: null,
      items1: ['Option 1', 'Option 2', 'Option 3'],
      items2: ['Choice A', 'Choice B', 'Choice C'],
      items3: ['Apple', 'Banana', 'Orange']

    };
  },
  mounted() {
    this.initializeAOS();

  },


  destroyed() {
    AOS.refresh(); // Manually refresh AOS when the component is destroyed
  },

  methods: {
    search() {
      // Perform search logic here
      console.log('Search clicked')
    },
    initializeAOS() {
      if (!this.initialized) {
        AOS.init({
          once: true,
          duration: 2000
        });
        this.initialized = true;
      }
    },

  },
  head() {
    return {
      title: 'Welcome to Sheba Plastic Platform'
    };
  }
};

</script>



<style scoped>
button {
  border: 1px solid orangered;
  background-color: white;
}



.bg-color {
  background-color: rgb(255, 68, 0);
  color: white;
}

.bg-color-1 {
  background-color: orangered;
}

.bg-image {
  background-image: url('https://img.freepik.com/free-vector/happy-student-having-geography-lesson-with-his-tutor-flat_1284-63593.jpg?w=740&t=st=1691964054~exp=1691964654~hmac=55e502bffbca59e19a47cef88e0933efc23d310eb719b19f38e8604567cee293');
  background-size: cover;
  height: 100%;
}

.bg-image-1 {
  background-image: url('../assets/omapny.png');
  background-size: cover;
  height: 100%;
}


.text-color {
  color: orangered;
}

/* Popup */
.tw-modal {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-overlay {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-container {
  opacity: 0;
  visibility: hidden;
  transform: translateY(-50px);
  transition: all 0.3s ease-in-out;
}

.tw-modal .tw-modal-overlay {
  opacity: 1;
  visibility: visible;
}

.tw-modal.open {
  opacity: 1;
  visibility: visible;
}


/* Popup */
.tw-modal {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-overlay {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-container {
  opacity: 0;
  visibility: hidden;
  transform: translateY(-50px);
  transition: all 0.3s ease-in-out;
}

.tw-modal .tw-modal-overlay {
  opacity: 1;
  visibility: visible;
}

.tw-modal.open {
  opacity: 1;
  visibility: visible;
}

.tw-modal.open .tw-modal-container {
  transform: translateY(0);
  opacity: 1;
  visibility: visible;
}

/* Close button */
.tw-modal-close {
  cursor: pointer;
}

/* Animation */
@keyframes fadeIn {
  from {
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}

.animated {
  animation-duration: 0.3s;
  animation-fill-mode: both;
}

.fadeIn {
  animation-name: fadeIn;
}
</style>
