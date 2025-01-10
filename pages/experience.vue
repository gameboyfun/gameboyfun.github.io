<template>
  <div class="absolute MartianMono p-4 flex flex-col gap-4">
    <BlurCard class="flex justify-center items-center text-center">
      <h1 class="prose text-7xl">Work Experience</h1>
    </BlurCard>
    <WorkExperience
      v-for="{
        companyImg,
        company,
        start,
        end,
        responsibility,
        projects,
        tools,
      } in workExperience"
      :key="company"
      :company-img="companyImg"
      :company="company"
      :start="start"
      :end="end"
      :responsibility="responsibility"
      :projects="projects"
      :tools="tools"
    />
    <BlurCard class="flex justify-center items-center text-center">
      <h1 class="prose text-7xl">Internship</h1>
    </BlurCard>
    <WorkExperience
      v-for="{
        companyImg,
        company,
        start,
        end,
        responsibility,
        projects,
        tools,
      } in internship"
      :key="company"
      :company-img="companyImg"
      :company="company"
      :start="start"
      :end="end"
      :responsibility="responsibility"
      :projects="projects"
      :tools="tools"
    />
    <BlurCard class="flex justify-center items-center text-center">
      <h1 class="prose text-7xl">Freelance</h1>
    </BlurCard>
    <WorkExperience
      v-for="{
        companyImg,
        company,
        start,
        end,
        responsibility,
        projects,
        tools,
      } in freelance"
      :key="company"
      :company-img="companyImg"
      :company="company"
      :start="start"
      :end="end"
      :responsibility="responsibility"
      :projects="projects"
      :tools="tools"
    />
    <BlurCard class="flex justify-center items-center text-center">
      <h1 class="prose text-7xl">Resume</h1>
    </BlurCard>
    <BlurCard class="flex justify-center items-center text-center space-y-2">
      <img class="custom-a4-image" src="/resume.jpg" />
      <button id="btn" class="ui-btn" @click="downloadPDF(resumeUrl)">
        <span>Download</span>
      </button>
    </BlurCard>
  </div>
</template>

<script>
import WorkExperience from '../components/workExperience.vue'
import BlurCard from '../components/blurCard.vue'
import 'assets/css/ui-button.css'

export default {
  components: { WorkExperience, BlurCard },
  data() {
    return {
      resumeUrl: '/resume.pdf',
      workExperience: [
        {
          companyImg: '/tcs-logo.png',
          company: 'Tata Consultancy Services (Thailand) Ltd.',
          start: 'Jan 2025',
          end: 'Present',
          responsibility: [
            `Specialized in the investment module within Agile methodology,
          implementing thorough unit testing to achieve an 80% code coverage
          goal for all components during the iterative development phase at TTB
          Bank Project ONE App.`,
            `Developed a web application leveraging React.js and Next.js,
          incorporating a micro frontend architecture. Conducted unit tests
          using Jest.`,
            `Addressed and resolved production issues to maintain uninterrupted
          system functionality.`,
          ],
          projects: [
            'TTB Oneapp (Investment Squad)',
            'Tablet Platform (Investment Squad)',
          ],
          tools: [
            'react',
            'next',
            'javascript',
            'typescript',
            'jest',
            'postman',
            'flutter',
            'git',
            'html',
            'css',
            'dart',
            'bitbucket',
            'atlassian',
            'jira',
            'redux',
            'vscode',
          ],
        },
        {
          companyImg: '/the-prodigy-logo.jpg',
          company: 'The Prodigy (Thailand) Public Company Limited',
          start: 'Jan 2024',
          end: 'Dec 2024',
          responsibility: [
            `Specialized in the investment module within Agile methodology,
          implementing thorough unit testing to achieve an 80% code coverage
          goal for all components during the iterative development phase at TTB
          Bank Project ONE App.`,
            `Developed a web application leveraging React.js and Next.js,
          incorporating a micro frontend architecture. Conducted unit tests
          using Jest.`,
            `Addressed and resolved production issues to maintain uninterrupted
          system functionality.`,
          ],
          projects: [
            'TTB Oneapp (Investment Squad)',
            'Tablet Platform (Investment Squad)',
          ],
          tools: [
            'react',
            'next',
            'javascript',
            'typescript',
            'jest',
            'postman',
            'flutter',
            'git',
            'html',
            'css',
            'dart',
            'bitbucket',
            'atlassian',
            'jira',
            'redux',
            'vscode',
          ],
        },
        {
          companyImg: '/cnes-consulting-logo.jpg',
          company: 'Cnes-Consulting co.,Ltd',
          start: 'Jan 2021',
          end: 'Dec 2023',
          responsibility: [
            'Led eCommerce initiatives for major brands including Boots Thailand, Bangkok Drug Store, and TV Direct, driving customer engagement and business growth.',
            'Developed responsive, high-performance web applications using React.js, Next.js, Vue.js, and Nuxt.js to ensure cross-platform accessibility.',
            'Delivered strategic insights and solutions for the Department of Trade Negotiations, enhancing operational efficiencies and aligning with trade and policy objectives.',
            'Conducted comprehensive analyses to identify and resolve technical and operational challenges, ensuring uninterrupted functionality and user satisfaction.',
          ],
          projects: [
            'Boots Thailand',
            'Bangkok Drug Store',
            'TV Direct',
            'Department of Trade Negotiations',
          ],
          tools: [
            'vue',
            'nuxt',
            'react',
            'next',
            'javascript',
            'bootstrap4',
            'tailwind',
            'git',
            'html',
            'css',
            'postman',
            'github',
            'gitlab',
            'vscode',
            'docker',
          ],
        },
        {
          companyImg: '/epic-consulting-logo.jpg',
          company: 'EPIC Consulting Co., Ltd.',
          start: 'Jun 2020',
          end: 'Dec 2020',
          responsibility: [
            'Demonstrated proficiency in software debugging, with a focus on the telecommunications industry.',
            'Created software and applications utilizing Angular, HTML, CSS, and Ionic 3.',
            'Deployed Java web services on-site at AIS.',
          ],
          projects: ['AIS iFarm', 'GSB Backoffice', 'Delivery Rider App'],
          tools: [
            'angular',
            'ionic',
            'javascript',
            'typescript',
            'bootstrap4',
            'tailwind',
            'git',
            'html',
            'css',
            'java',
            'github',
            'vscode',
          ],
        },
      ],
      internship: [
        {
          companyImg: '/panelplus-logo.png',
          company: 'Panel Plus Company Limited',
          start: 'Jun 2019',
          end: 'Dec 2019',
          responsibility: [
            'Developed the PanelPlus Helpdesk application, a responsive mobile solution to streamline and support helpdesk operations.',
            'Utilized Flutter to create a cross-platform application with efficient and consistent performance on both iOS and Android.',
            'Collaborated with team members to design, implement, and optimize user interfaces and back-end functionality.',
          ],
          projects: ['Panelplus Helpdesk Application'],
          tools: [
            'angular',
            'flutter',
            'dart',
            'javascript',
            'typescript',
            'bootstrap4',
            'html',
            'css',
            'postman',
            'vscode',
          ],
        },
      ],
      freelance: [
        {
          companyImg: '/double-a-logo.png',
          company: 'Double A (1991) Public Co., Ltd.',
          responsibility: [
            'Developed web application with Vue.js, HTML, CSS.',
            'Engaged with clients to understand requirements for landing pages and CMS.',
          ],
          projects: [
            'Double A Fastprint Landing Page',
            'Double A Fastprint Backoffice',
          ],
          tools: [
            'vue',
            'nuxt',
            'javascript',
            'bootstrap4',
            'html',
            'css',
            'postman',
            'github',
            'vscode',
          ],
        },
        {
          companyImg:
            '/the-cremation-welfare-of-the-ministry-of-public-health.png',
          company: 'The Cremation Welfare of The Ministry of Public Health',
          responsibility: [
            'Developed web application with Vue.js, HTML, CSS.',
            'Engaged with clients to understand requirements for landing pages and CMS.',
          ],
          projects: ['Financial and Accounting System'],
          tools: [
            'vue',
            'nuxt',
            'javascript',
            'bootstrap4',
            'html',
            'css',
            'postman',
            'github',
            'vscode',
          ],
        },
      ],
    }
  },
  methods: {
    downloadPDF(url) {
      const link = document.createElement('a')
      link.href = url // Path to the PDF file in the static folder
      link.download = 'Thipakorn Kaewsuwan - Resume' // Optional: set a custom file name for download
      link.click()
    },
  },
}
</script>

<style>
.custom-a4-image {
  height: 100vh; /* Full viewport height */
  width: calc(100vh * (210 / 297)); /* Sets width based on A4 aspect ratio */
  object-fit: contain; /* Ensures the entire image fits within the set dimensions */
}
</style>
