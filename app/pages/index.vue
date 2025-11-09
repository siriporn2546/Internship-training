<template>
  <v-app>
    <v-main class="bg-grey-lighten-5">
      <v-container class="text-center py-12">

        <v-card
          class="mx-auto pa-6 pa-md-10"
          max-width="700"
          rounded="xl"
          elevation="4"
        >
          <!-- Avatar -->
          <v-avatar
            size="140"
            class="mx-auto mb-6"
          >
            <img
              src="https://i.ibb.co/dwqZ0Hzs/500727362-2163750410769761_3822210232682275755-n.jpg"
              alt="Profile"
              style="object-fit: cover; width: 100%; height: 100%;"
            />
          </v-avatar>

          <!-- Heading -->
          <h3 class="text-h4 text-md-h3 font-weight-bold mb-3">
            สวัสดีค่ะ 👋✨ 
            <span class="text-light-blue-lighten-2"><h3>  
            </h3>หนูชื่อ องุ่น (A-ngun)</span>
          </h3>

          <!-- Subtitle -->
          <p class="text-dark-darken-1 text-subtitle-1 mb-8">
            นักศึกษาฝึกงานด้าน <strong>Frontend Developer</strong> 👩‍💻
          </p>

          <!-- Button -->
          <v-btn
            color="light-blue-lighten-2"
            variant="flat"
            rounded="lg"
            size="large"
            prepend-icon="mdi-arrow-right-thin"
            to="/about"
          >
            ดูข้อมูลเพิ่มเติม
          </v-btn>

          <!-- Social Links -->
          <div class="mt-12">
            <p class="text-grey-darken-1 mb-4">ติดตามหนูได้ที่นี่นะคะ 👇</p>
            <v-btn
              icon="mdi-github"
              href="https://github.com/your-username"
              target="_blank"
              variant="text"
              class="mx-2"
              color="light-blue-lighten-1"
            ></v-btn>
            <v-btn
              icon="mdi-linkedin"
              href="https://linkedin.com/in/your-username"
              target="_blank"
              variant="text"
              class="mx-2"
              color="light-blue-lighten-1"
            ></v-btn>
            <v-btn
              icon="mdi-email"
              href="mailto:your-email@gmail.com"
              target="_blank"
              variant="text"
              class="mx-2"
              color="light-blue-lighten-1"
            ></v-btn>
          </div>
        </v-card>

      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
// ไม่ต้องใส่อะไรเลย! Vuetify ทำงานอัตโนมัติแล้ว
</script>