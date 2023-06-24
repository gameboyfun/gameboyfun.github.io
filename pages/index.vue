<template>
  <div class="landing-page flex flex-col items-center justify-center min-h-screen text-center font-sans">
    <div class="video-container">
      <video autoplay loop muted playsinline class="w-full h-full object-cover">
        <source src="/bg.mp4" type="video/mp4">
      </video>
    </div>

    <div class="content-container">
      <header class="animate-fade-in">
        <h1 class="text-4xl font-bold text-neon-green mb-4">{{ fullName }}</h1>
        <h2 class="text-xl text-neon-green">{{ jobTitle }}</h2>
      </header>

      <main class="animate-fade-in delay-200">
        <section class="my-8">
          <h3 class="text-2xl font-bold mb-2">About Me</h3>
          <p class="text-gray-700">{{ aboutMe }}</p>
        </section>

        <section class="my-8">
          <h3 class="text-2xl font-bold mb-2">Experience</h3>
          <ul class="list-none">
            <li v-for="(experience, index) in experiences" :key="index" class="mb-4">
              <h4 class="text-xl font-bold text-neon-green">{{ experience.position }}</h4>
              <p class="text-gray-700">{{ experience.company }}</p>
              <p class="text-gray-600">{{ experience.startDate }} - {{ experience.endDate }}</p>
              <ul class="list-disc ml-8">
                <li v-for="(responsibility, index) in experience.responsibilities" :key="index" class="text-gray-700">{{ responsibility }}</li>
              </ul>
            </li>
          </ul>
        </section>

        <section class="my-8">
          <h3 class="text-2xl font-bold mb-2">Education</h3>
          <ul class="list-none">
            <li v-for="(education, index) in educationList" :key="index" class="mb-4">
              <h4 class="text-xl font-bold text-neon-green">{{ education.degree }}</h4>
              <p class="text-gray-700">{{ education.institution }}</p>
              <p class="text-gray-600">{{ education.startDate }} - {{ education.endDate }}</p>
            </li>
          </ul>
        </section>
      </main>

      <footer class="mt-8 animate-fade-in delay-400">
        <p class="text-gray-600">{{ email }}</p>
        <p class="text-gray-600">{{ phone }}</p>
      </footer>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <div class="bg-white">
        123
      </div>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      fullName: "Your Full Name",
      jobTitle: "Your Job Title",
      aboutMe: "Write a brief description about yourself here.",
      experiences: [
        {
          position: "Job Position",
          company: "Company Name",
          startDate: "Start Date",
          endDate: "End Date",
          responsibilities: [
            "Responsibility 1",
            "Responsibility 2",
            "Responsibility 3"
          ]
        }
      ],
      educationList: [
        {
          degree: "Degree",
          institution: "Institution Name",
          startDate: "Start Date",
          endDate: "End Date"
        }
      ],
      email: "yourname@example.com",
      phone: "123-456-7890"
    };
  }
};
</script>

<style>
@keyframes fade-in {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.animate-fade-in {
  animation: fade-in 0.5s ease-out;
}

.video-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  z-index: -1;
  overflow: hidden;
}

.video-container video {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: auto;
  z-index: -1;
}

.content-container {
  position: relative;
  z-index: 1;
}

/* Neon Green color */
.text-neon-green {
  color: #00ff00;
}
</style>
