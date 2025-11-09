<template>
  <v-main class="bg-grey-lighten-5 pa-4 pa-md-8">
    <v-container>

      <!-- 1. หัวข้อหลัก -->
      <h1 class="text-h4 text-md-h3 font-weight-bold mb-8 text-center text-light-blue-darken-1">
        เกี่ยวกับฉัน (About Me) 🌸
      </h1>

      <!-- 2. การ์ดแนะนำตัว (การ์ดแรก) -->
      <v-card
        class="mx-auto pa-4 pa-md-6 mb-8"
        max-width="900"
        rounded="xl"
        elevation="4"
      >
        <v-card-text>
          <p class="text-h6 text-md-h5 text-center font-weight-regular">
            สวัสดีค่ะ หนูชื่อ <strong>องุ่น (A-ngun)</strong> 👩‍💻
            <br>
            ปัจจุบันกำลังศึกษาในสาขาวิศวกรรมคอมพิวเตอร์
            มีความสนใจในด้าน <strong>Frontend Development</strong> และการออกแบบเว็บไซต์ให้ใช้งานง่ายค่ะถึงตอนนี้จะยังไม่เก่งแต่พร้อมเรียนีู่ยรู้และพัฒนาตัวเองอยู่เสมอค่ะ 😊
          </p>
        </v-card-text>
      </v-card>

 
      <v-row>

        
        <v-col cols="12" md="6">
          <v-card class="fill-height" rounded="xl" elevation="4">
            <v-card-title class="d-flex align-center pa-5">
              <v-icon icon="mdi-tools" color="light-blue-darken-1" start size="large"></v-icon>
              <span class="text-h6 font-weight-bold text-light-blue-darken-1">
                เพื่อฝึกทักษะ 
              </span>
            </v-card-title>
            <v-card-text class="pa-5">
              <!-- ใช้ v-chip-group + v-chip จะสวยงามกว่า list -->
              <v-chip-group>
              
                <v-chip color="light-blue-lighten-2" variant="flat" class="ma-1">Vue.js</v-chip>
                <v-chip color="light-blue-lighten-2" variant="flat" class="ma-1">Nuxt4</v-chip>
                <v-chip color="light-blue-lighten-2" variant="flat" class="ma-1">Vuetify</v-chip>
                <v-chip color="grey-lighten-2" variant="flat" class="ma-1">Tailwind CSS</v-chip>
              </v-chip-group>
            </v-card-text>
          </v-card>
        </v-col>

        <!-- 3.2 คอลัมน์ "เป้าหมาย" -->
        <v-col cols="12" md="6">
          <v-card class="fill-height" rounded="xl" elevation="2">
            <v-card-title class="d-flex align-center pa-5">
              <v-icon icon="mdi-bullseye-arrow" color="light-blue-darken-1" start size="large"></v-icon>
              <span class="text-h6 font-weight-bold text-light-blue-darken-1">
                เป้าหมายการฝึกงาน
              </span>
            </v-card-title>
            <v-card-text class="pa-5 text-body-1">
              ต้องการเรียนรู้การทำงานจริงในทีมพัฒนาเว็บ และพัฒนาทักษะในการเขียนโค้ดให้มีคุณภาพ พร้อมที่จะเติบโตในสายงานนี้ค่ะ
            </v-card-text>
          </v-card>
        </v-col>

      </v-row>

      <!-- 4. การ์ด "ติดต่อ" (แยกส่วน) -->
      <v-card
        class="mx-auto pa-4 pa-md-6 mt-8"
        max-width="900"
        rounded="xl"
        elevation="4"
      >
        <v-card-title class="d-flex align-center justify-center">
          <v-icon icon="mdi-email-heart-outline" color="light-blue-darken-1" start size="large"></v-icon>
          <span class="text-h6 font-weight-bold text-light-blue-darken-1">
            ติดต่อได้ที่นี่นะคะ 👇
          </span>
        </v-card-title>
        <v-card-text class="text-center text-h6">
          <p>
            <a href="mailto:siriporn.ni@rmuti.ac.th" class="contact-link">
              siriporn.ni@rmuti.ac.th
            </a>
          </p>
          <p>
            <a href="tel:0932938522" class="contact-link">
              093-293-8522
            </a>
          </p>
        </v-card-text>
      </v-card>

      <!-- 5. ปุ่มกลับหน้าแรก -->
      <div class="text-center mt-10">
        <v-btn
          to="/"
          color="light-blue-lighten-2"
          variant="flat"
          rounded="lg"
          size="large"
          prepend-icon="mdi-arrow-left-thin"
        >
          กลับหน้าแรก
        </v-btn>
      </div>

    </v-container>
  </v-main>
</template>

<script setup>
</script>

<style scoped>

.contact-link {
  color: #29B6F6; 
  text-decoration: none;
  font-weight: 500;
  transition: all 0.2s ease-in-out;
  display: inline-block;
}
.contact-link:hover {
  text-decoration: none;
  color: #0288D1; 
  transform: scale(1.05); 
}
</style>