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
    <template #heading>Chulalongkorn University</template>

    Bachelor of Science, Computer Science<br>
    2014 - 2018
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>DST Worldwide Services (SS&C)</template>

    Software Developer<br>
    June 2018 - Oct 2019
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Accenture</template>

    Application Development Analyst<br>
    Nov 2019 - Aug 2021
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Liberty Mutal Insurance (LMG)</template>

    Assistant Manager, Technology-App Dev & Eng<br>
    Sep 2021 - Jul 2022
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Yim Platform</template>

    Senior Software Engineer<br>
    Jul 2022 - Present
  </WelcomeItem>
</template>
