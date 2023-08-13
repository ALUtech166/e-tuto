<template>
  <div>
    <section class="lg:tw-mx-12 tw-mx-8">
      <div class="bg-image tw-py-24 tw-rounded-lg tw-shadow-2xl tw-shadow-gray-900 tw-h-full tw-w-full">
        <div
          class="tw-w-full tw-h-full tw-flex tw-flex-col lg:tw-flex-row tw-bg-black tw-bg-opacity-60 tw-p-12">
          <div class="tw-text-left tw-px-8 tw-h-full">
            <h1 class="tw-text-white tw-text-5xl tw-font-extrabold lg:tw-w-3/4">
              Expert Online Tutoring 
            </h1>
            <h1 class="text-color tw-mt-4 tw-text-5xl tw-font-extrabold lg:tw-w-3/4">
              for College and High School Success
            </h1>

            <p class="tw-text-white tw-text-xl lg:tw-w-3/4 tw-mt-4">
              Unlock your academic potential with ScholarLink, your premier destination for personalized online tutoring services.
            </p>

          </div>

          <v-img
            class="tw-rounded-lg tw-shadow-2xl  tw-cursor-pointer"
            src="https://img.freepik.com/free-photo/happy-successful-business-leader-signing-agreement_74855-2307.jpg?w=740&t=st=1691964166~exp=1691964766~hmac=d5d7276414cb4e587af8d6041fda464481b830a76440ded812c21257a469136e"
            width="400px"></v-img>
        </div>
      </div>

      <div
        class="bg-color tw-shadow-2xl tw-rounded-lg tw-shadow-gray-800 lg:tw-mx-24 tw-mx-8 tw-transform tw--translate-y-20 tw-bottom-0 tw-left-0 tw-px-8 tw-py-6">
     


  <!-- component -->
<div class="tw-flex tw-flex-col tw-p-4 tw-py-8 tw-m-h-screen">

<div class="tw-bg-white tw-shadow-2xl tw-items-center tw-justify-between tw-w-full tw-flex tw-rounded-full tw-shadow-gray-900 tw-p-2 tw-mb-5 tw-sticky" style="top: 5px">

  

    <v-autocomplete v-model="selectedItem1" :items="items1" label="Item 1" />
    <v-autocomplete v-model="selectedItem2" :items="items2" label="Item 2" />
    <v-autocomplete v-model="selectedItem3" :items="items3" label="Item 3" />
  <div class="bg-color tw-p-4 hover:tw-bg-blue-400 tw-cursor-pointer tw-mx-2 tw-rounded-full">

    <svg class="tw-w-6 tw-h-6 tw-text-white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
      <path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" clip-rule="evenodd" />
    </svg>

  </div>

</div>



</div>

      </div>
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
