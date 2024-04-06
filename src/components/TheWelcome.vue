<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Bio Data</template>
    Perkenalkan Nama saya Raviki Triaulian, lahir di Pekanbaru, RIAU 20 Juni 2003. Saat ini, saya
    sedang menempuh pendidikan sebagai mahasiswa di Universitas Islam Riau, Jurusan saya yaitu
    Teknik Informatika.
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
    Saya pernah menempuh pendidikan di :
    <li>TK Pembina 1 Pekanbaru</li>
    <li>
      <a
        href="https://data.sekolah-kita.net/sekolah/SD%20KARTIKA%20I-9%20SAIL_196090"
        target="_blank"
        rel="noopener"
        >SD Kartika 1-9</a
      >
    </li>
    <li>
      <a
        href="https://dapo.kemdikbud.go.id/sekolah/07A7B6F7E86E8A9E31A1"
        target="_blank"
        rel="noopener"
        >SMPN 5 Pekanbaru</a
      >
    </li>
    <li>
      <a href="https://sman1pekanbaru.sch.id/" target="_blank" rel="noopener">SMAN 1 Pekanbaru</a>
    </li>
    <li><a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a></li>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>
    keterampilan merupakan kunci sukses dalam berinteraksi, berkolaborasi, dan beradaptasi di dunia
    profesional.
    <ul>
      <li>HTML</li>
      <li>MySql</li>
      <li>Javascript</li>
      <li>C++</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman</template>
    Saya tidak akan menyia-nyiakan kesempatan untuk terus tampil dan berkembang di setiap pengalaman
    yang saya alami.
    <ul>
      <li>Perwakilan Tim SepakBola RIAU U-15 di Yogyakarta</li>
      <li>ProPlayer di bidang E-Sport</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
    terdapat Email dan No HP yg saya cantumkan untuk dapat menghubungi saya <br />
    Email : ravikitriaulian07@gmail.com<br />
    No HP : 0823-8367-7020
  </WelcomeItem>
</template>
