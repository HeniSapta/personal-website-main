<script>
export default {
  data(){return{
    educations: [
      {
        year: "Sept 2022 - Juli 2026",
        univ: "Amikom Yogyakarta",
        location: "Yogyakarta",
        degree: "Bachelor",
        field: "Informatics",
        description: [
          "Studied data analysis, software development, web development, database management, information systems, and UI/UX.",
          "Developed a Laundry Information System as an academic project to improve operational efficiency and data management.",
          "Designed a mobile application based on User Experience (UX) principles using a user-centered design approach.",
          "Participated in the KOSABANGSA Program by contributing to digital solutions that support the transformation and digitalization of MSMEs.",
          "I graduated from Amikom University with 3.79 GPA.",
        ]
      },
    ]
  }}
}
</script>

<template>
  <section>
    <h2 class="text-secondary fw-bolder mb-4">Education</h2>

    <div v-for="education of educations" class="card shadow border-0 rounded-4 mb-5">
      <div class="card-body px-3 px-md-5 py-5">
        <div class="row align-items-center gx-5">
          <div class="col text-center text-lg-start mb-4 mb-lg-0">
            <div class="p-4 rounded-4">
              <div class="text-secondary fw-bolder mb-2">{{education.year}}</div>
              <div class="mb-2">
                <div class="small fw-bolder">{{education.univ}}</div>
                <div class="small text-muted">{{education.location}}</div>
              </div>
              <div class="fst-italic">
                <div class="small text-muted">{{education.degree}}</div>
                <div class="small text-muted">{{education.field}}</div>
              </div>
            </div>
          </div>
          <div class="col-lg-8">
            <div>
              <ul class="mb-0">
                <li v-for="desc of education.description">
                  {{desc}}
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>