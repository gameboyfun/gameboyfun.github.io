<template>
  <div>
    <div class="text-sky-400">qweqweqwe</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      fullName: 'Your Full Name',
      jobTitle: 'Your Job Title',
      aboutMe: 'Write a brief description about yourself here.',
      experiences: [
        {
          position: 'Job Position',
          company: 'Company Name',
          startDate: 'Start Date',
          endDate: 'End Date',
          responsibilities: [
            'Responsibility 1',
            'Responsibility 2',
            'Responsibility 3',
          ],
        },
      ],
      educationList: [
        {
          degree: 'Degree',
          institution: 'Institution Name',
          startDate: 'Start Date',
          endDate: 'End Date',
        },
      ],
      email: 'yourname@example.com',
      phone: '123-456-7890',
    }
  },
}
</script>
