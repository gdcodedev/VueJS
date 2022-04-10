<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>About me</template>
    Technology lover, father, husband and gamer in his spare time. Front-end
    developer. With knowledge of Javascript and learning more about VueJS.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Certificate</template>

    Introduction to Cybersecurity This project is served and bundled wit
    <a
      href="https://www.credly.com/badges/9e3a8f66-20d0-4647-8b2c-370171a9f89e?source=linked_in_profilehttps://vitejs.dev/guide/features.html"
      target="_blank"
      >Introduction to Cybersecurity</a
    >
    The holder of this credential has introductory knowledge of cybersecurity,
    including the global implications of cyber threats.

    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Web Developer</template>
    <a
      href="https://www.linkedin.com/in/guilherme-cardoso-53123563/details/certifications/"
      target="_blank"
      >Web Developer</a
    >
    The above certificate attests that Guilherme Da Costa Cardoso successfully
    completed the bootcamp HTML Web Developer on 03/04/2021 at Digital
    Innovation One. The certificate indicates that the entire bootcamp has been
    completed, as validated by the student. Get official tools and libraries for
    your project:
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Foundations for Amazon S3</template>
    <a
      href="https://www.linkedin.com/in/guilherme-cardoso-53123563/details/certifications/"
      target="_blank"
      >Foundations for Amazon S3
    </a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Introduction to the JAVA Ecosystem</template>
    <a href="https://www.dio.me/certificate/C9B2392E/share" target="_blank"
      >Introduction to the JAVA Ecosystem
    </a>
  </WelcomeItem>
</template>
