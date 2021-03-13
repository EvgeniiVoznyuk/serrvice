<template>
  <div class="main">
    <Navbar />
    <HomeSection />
    <ServiceSection />
    <Contacts />
    <Form />
  </div>
</template>

<script>
import HomeSection from '@/components/HomeSection.vue';
import ServiceSection from '@/components/ServiceSection.vue';
import Contacts from '@/components/Contacts.vue';
import Form from '@/components/Form.vue';
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'Main',
  components: {
    Navbar,
    HomeSection,
    ServiceSection,
    Contacts,
    Form,
  },
};
</script>
