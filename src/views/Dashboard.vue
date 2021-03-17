<template>
  <div id="Dashboard">
    <v-app class="bg-dark">
      <v-main>
        <dashboardLayout />
        <v-row class="m-0">
          <v-col md="12" cols="12">
            <v-row class="m-0">
              <v-col md="4" cols="12">
                Dashboard
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-main>
    </v-app>
  </div>
</template>

<script>
import dashboardLayout from "../components/DashboardLayout";

export default {
  name: "Dashboard",
  components: {
    dashboardLayout,
  },
};
</script>

<style></style>
