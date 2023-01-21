<script setup lang="ts">
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
    <template #heading
      >I'm <a href="http://magicseth.com">MagicSeth</a></template
    >
    I'm remaking the internet for kids.
    <p>As a solo founder, sometimes I just need to bounce ideas around.</p>
    <p>So I built this so I could spitball ideas in the middle of the night.</p>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Privacy</template>
    <p>Your transcripts are logged on my server. They will never be sold.</p>

    <p>
      I made this for myself, but I wanted to share it with you.
    </p></WelcomeItem
  >

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Support</template>
    I need support!
    <p>
      An AI co-founder isn't going to cut it for what I'm aiming to do: rebuild
      the whole internet for kids... so reach out to
      <a href="mailto:wannachat@magicseth.com">wannachat@magicseth.com</a> if
      you might want to be a human co-founder!
    </p>
  </WelcomeItem>
</template>
