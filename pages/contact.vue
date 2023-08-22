<template>
  <div class="">

    <div class="tw-mt-4 lg:tw-mx-0 tw-aspect-w-16  tw-overflow-hidden tw-h-full" data-aos="fade-up">

      <iframe class=""
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d63800.26059361784!2d30.057428788649723!3d-1.94642533671203!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x19dca5a86d814c61%3A0x7d3b83e12b1c11a9!2sNorrsken%20House%20Kigali!5e0!3m2!1sfr!2srw!4v1684802051331!5m2!1sfr!2srw"
        width="100%" height="600" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>




    <div class="lg:tw-mx-8 tw-bottom-0 tw-left-0 tw-px-8 tw-py-12">
      <div class="lg:tw-flex lg:tw-flex-row sm:tw-flex sm:tw-flex-col lg:tw-justify-betwen lg:tw-gap-12">

        <div class="tw-text-lg tw-transform tw--translate-y-40 sm:tw-text-lg lg:tw-w-1/2 tw-mb-12">
          <div class="">
            <form class="tw-bg-white lg:tw-mt-0 tw-shadow-2xl tw-rounded-xl tw-px-8 tw-py-12"
              v-on:submit.prevent="sendMessage">

              <div class="tw-w-full tw-md:w-1/2">
                <label class="tw-block tw-font-extrabold tw-mb-1" for="name">
                  Name
                </label>

                <input type="name" name="name" id="email" placeholder="John Doe" v-model="contact.name"
                  class="tw-block tw-bg-gray-300 tw-placeholder-gray-500 tw-w-full  tw-text-black tw-shadow-xl tw-rounded-lg tw-outline-none  tw-mb-1 tw-p-3"
                  required>
              </div>

              <div class="tw-w-full tw-md:w-1/2">
                <label class="tw-block tw-font-extrabold tw-mb-1" for="email">
                  Email Address
                </label>

                <input type="email" name="email" id="email" placeholder="email@example.com" v-model="contact.email"
                  class="tw-block  tw-bg-gray-300 tw-placeholder-gray-500 tw-w-full  tw-text-black tw-shadow-xl tw-rounded-lg tw-outline-none  tw-mb-1 tw-p-3"
                  required>
              </div>


              <div class="tw-w-full tw-md:w-1/2">
                <label class="tw-block tw-font-extrabold tw-mb-1" for="number">
                  Phone Number
                </label>

                <input type="text" name="number" id="number" placeholder="+228 91 58 50 75" v-model="contact.phone"
                  class="tw-block  tw-bg-gray-300 tw-placeholder-gray-500 tw-w-full  tw-text-black tw-shadow-xl tw-rounded-lg tw-outline-none  tw-mb-1 tw-p-3"
                  required>
              </div>


              <div class="tw-w-full tw-md:w-1/2">
                <label class="tw-block tw-font-extrabold tw-mb-1" for="text">
                  Company
                </label>

                <input type="text" name="text" id="text" placeholder="Enter your company here" v-model="contact.company"
                  class="tw-block  tw-bg-gray-300 tw-placeholder-gray-500 tw-w-full  tw-text-black tw-shadow-xl tw-rounded-lg  tw-outline-none  tw-mb-1 tw-p-3"
                  required>
              </div>

              <div class="tw-w-full tw-md:w-1/2">
                <label class="tw-block tw-font-extrabold tw-mb-1" for="text">
                  Position
                </label>

                <input type="text" name="text" id="text" placeholder="Enter your position here" v-model="contact.position"
                  class="tw-block tw-bg-gray-300 tw-placeholder-gray-500 tw-rounded-lg tw-w-full  tw-text-black tw-shadow-lg tw-outline-none  tw-mb-1 tw-p-3"
                  required>
              </div>




              <div class="tw-w-full tw-mb-8">
                <label class="tw-block tw-font-extrabold tw-mb-1" for="message">
                  Message
                </label>

                <textarea id="message" rows="3" name="message" v-model="contact.message"
                  class="tw-block  tw-bg-gray-300 tw-placeholder-gray-500 tw-w-full tw-text-black tw-p-4  tw-shadow-lg tw-rounded-lg  tw-outline-none tw-appearance-none  tw-mb-1 tw-py-3"
                  placeholder="Enter your message here." required></textarea>
              </div>

              <button
                class="tw-group bg-color tw-shadow-lg tw-rounded-lg tw-relative tw-h-12 tw-mt-4 tw-cursor-pointer hover:tw-transform hover:tw-translate-x-2 hover:tw-transition-transform hover:tw-duration-300 hover:tw-shadow-2xl-blue-600 hover:tw-shadow-2xl-lg tw-w-48 tw-overflow-hidden tw-rounded-lg tw-text-lg tw-shadow-2xl-2xl">
                <div
                  class="tw-absolute tw-inset-0 tw-w-full bg-color tw--transition-all tw-duration-[250ms] tw-ease-out group-hover:tw-w-full">
                </div>
                <span class="tw-relative tw-inline-flex tw-items-center tw-gap-2 tw-text-white group-hover:tw-text-white">
                  Send

                </span>
              </button>
            </form>


          </div>
        </div>

        <div class="lg:tw-mt-8 lg:tw-w-1/2 tw-items-center">
          <h1 class="tw-text-black tw-text-5xl tw-font-extrabold">
            How can <span class="text-color">we help?</span>
          </h1>
          <p class="tw-text-black tw-text-xl tw-mt-2">
            Reach out to me anytime and I will get back to you within 24 hours.
          </p>

          <div class="tw-mt-4">
            <section class="tw-bg-gray-100 tw-shadow-2xl tw-rounded-lg tw-py-8">
              <div class="tw-container">
                <h2 class="tw-text-3xl tw-font-extrabold tw-mb-6">Frequently Asked Questions</h2>
                <div class="tw-space-y-6">
                  <div v-for="(item, index) in faqItems" :key="index" class="tw-border-b tw-border-gray-300 tw-pb-4">
                    <div class="tw-flex tw-justify-between tw-items-center">
                      <h3 class="tw-text-md text-color tw-font-bold">{{ item.question }}</h3>
                      <button @click="toggleAnswer(index)"
                        class="tw-text-gray-600 tw-hover:text-gray-800 focus:tw-outline-none">
                        {{ item.expanded ? 'Collapse' : 'Expand' }}
                      </button>
                    </div>
                    <p v-show="item.expanded" class="tw-text-gray-600 tw-mt-2">{{ item.answer }}</p>
                  </div>
                </div>
              </div>
            </section>
          </div>




        </div>



      </div> <!-- end hero -->



      <div class="tw-grid lg:tw-grid-cols-3 tw-gap-6 lg:tw-gap-8 md:tw-gap-8">
        <div class="tw-shadow-2xl tw-shadow-gray-800 tw-rounded-lg bg-color tw-block tw-cursor-pointer tw-w-full">

          <div class="tw-px-12 tw-p-4 tw-text-left tw-h-[fit-content] lg:tw-h-full lg:tw-my-8">

            <h1 class="tw-font-extrabold tw-text-xl tw-text-white tw-pt-2">
              Mobile Application
            </h1>
            <div class="tw-mt-8">
              <p class="tw-font-medium tw-text-md tw-text-white tw-text-justify">
                Incentivizing Users to Participate in Recycling Efforts
              </p>

            </div>
          </div>

        </div>

        <div
          class="tw-shadow-2xl tw-rounded-lg tw-shadow-gray-800 tw-bg-white hover-bg hover:tw-text-white tw-block tw-cursor-pointer tw-w-full">


          <div class="tw-px-12 tw-p-4 tw-text-left tw-h-[fit-content] lg:tw-h-full lg:tw-my-8">


            <h1 class="tw-font-extrabold tw-text-xl tw-text-black hover:tw-text-white">
              Circular Economy
            </h1>
            <div class="tw-mt-8">
              <p class="tw-font-medium tw-text-md tw-text-black tw-text-justify hover:tw-text-white">
                Transforming Plastic Waste into Valuable Resources
              </p>
            </div>


          </div>
        </div>

        <div class="tw-shadow-2xl tw-shadow-gray-800 tw-rounded-lg bg-color tw-block tw-cursor-pointer tw-w-full">

          <div class="tw-px-12 tw-p-4 tw-text-left tw-h-[fit-content] lg:tw-h-full lg:tw-my-8">
            <h1 class="tw-font-extrabold tw-text-xl tw-text-white tw-pt-2">
              Smart Bin
            </h1>
            <div class="tw-mt-8">
              <p class="tw-font-medium tw-text-md tw-text-white tw-text-justify">
                Serving as a Plastic Waste Collection Point and Provides Data.
              </p>

            </div>
          </div>

        </div>
      </div>





    </div>


  </div>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
const swal = require('sweetalert2')

export default {
  data() {
    return {
      title: 'Nous contacter Page',
      contact: {
        name: "",
        phone: "",
        email: "",
        message: "",
      },

      faqItems: [
        {
          question: "What is Tailwind CSS?",
          answer: "Tailwind CSS is a utility-first CSS framework...",
          expanded: false,
        },
        {
          question: "What is Tailwind CSS?",
          answer: "Tailwind CSS is a utility-first CSS framework...",
          expanded: false,
        },
        {
          question: "What is Tailwind CSS?",
          answer: "Tailwind CSS is a utility-first CSS framework...",
          expanded: false,
        },
        {
          question: "What is Tailwind CSS?",
          answer: "Tailwind CSS is a utility-first CSS framework...",
          expanded: false,
        },
        // Add more FAQ items
      ],



    }
  },

  head() {
    return {
      title: 'Nous contacter Page',

    }
  },

  computed: {
    breadcrumbItems() {
      const items = [{
        text: 'Home',
        href: '/',
      },
      {
        text: 'Contact Us',

      },

      ];

      return items.map((item) => ({
        ...item,
        disabled: !item.href,
      }));
    },
  },

  mounted() {
    if (!this.initialized) {
      AOS.init({
        once: true,
        duration: 2000
      });
      this.initialized = true;
    }
  },

  methods: {

    toggleAnswer(index) {
      this.faqItems[index].expanded = !this.faqItems[index].expanded;
    },
    async sendMessage(contact) {
      try {
        const response = await fetch('/api/v1/send-email', {
          method: 'POST',
          body: JSON.stringify({
            contact: {
              name: this.contact.name,
              phone: this.contact.phone,
              email: this.contact.email,
              message: this.contact.message,
            }
          }),
          headers: {
            'Content-Type': 'application/json'
          }
        });
        const data = await response.json();
        if (response.ok) {
          new swal({
            title: 'Message envoyé!',
            text: 'Votre message a été envoyé avec succès.',
            icon: 'success',
            button: 'Fermer',
          });
        }
        return data;
      } catch (error) {
        console.error('Error sending message:', error);
        new swal({
          title: 'Erreur!',
          text: 'Une erreur s\'est produite lors de l\'envoi de votre message.',
          icon: 'error',
          button: 'Fermer',
        });
      }
    }



  },
}

</script>

<style scoped>
.bg-image {
  background-image: url(https://img.freepik.com/premium-photo/african-american-practitioner-assistant-with-protective-face-mask-against-coroanvirus_482257-26733.jpg?w=740);
  background-size: cover;
  height: 100%;
  width: 100%;
}

.bg-color {
  background-color: #0B2447;
}

:hover.hover-bg {
  background-color: #0B2447;
}


.text-color {
  color: #0B2447;
}


button {
  color: black
}
</style>
