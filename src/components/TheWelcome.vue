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
    <template #heading>Tentang Saya</template>
    Nama saya Kayla,saya lahir di Muara Enim,Sumatera Selatan pada 07 Oktober 2003
    Saat ini, saya tengah menempuh pendidikan sebagai mahasiswi di Universitas Islam Riau, yang berlokasi di Jalan Kaharuddin Nst, Pekanbaru. Sedang berada di semester 4, saya mengambil jurusan Teknik Informatika di institusi tersebut.
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
Saya pernah menempuh pendidikan di :
    <li>TK Mutiara Hati</li>
      <li><a href="https://dapo.kemdikbud.go.id/sekolah/0E2DFC935742CD6D05FE" target="_blank" rel="noopener">SD Cendana Batam</a></li>
      <li><a href="https://smpn1tembilahan.sch.id/" target="_blank" rel="noopener">SMPN 1 Tembilahan Kota</a></li>
      <li><a href="https://sman14pekanbaru.sch.id/" target="_blank" rel="noopener">SMAN 14 Pekanbaru</a></li>
      <li><a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a></li>

  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>
    keterampilan merupakan kunci sukses dalam berinteraksi, berkolaborasi, dan beradaptasi di dunia profesional.
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
Saya tidak akan menyia-nyiakan kesempatan untuk belajar dan berkembang dari setiap pengalaman yang saya alami.
    <ul>
    <li>Anggota Paduan suara</li>
      <li>Berorganisasi di Paskibraka</li>
</ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
untuk menghubungi saya kalian dapat mengontak di bawah ini
   sosmed Instagram :<a href="https://www.instagram.com/aurorakaylaaa" target="_blank">aurorakaylaaa </a
    ><br />
    Email : aurorakayla@gmail.com<br/>
    No HP : 082169972635
  </WelcomeItem>
</template>