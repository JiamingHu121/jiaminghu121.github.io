---
layout: page
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
  {
    avatar: './image/hj.jpg',
    name: '黄菊',
    title: '博士后',
    links: [
      { icon: 'github', link: 'https://scholar.google.com/citations?hl=en&user=O4S9gP0AAAAJ' },
      { icon: 'twitter', link: '' }
    ]
  },
  {
    avatar: './image/dxy.jpg',
    name: '董欣月',
    title: '博士后',
    links: [
      { icon: 'github', link: 'https://www.researchgate.net/profile/Xinyue-Dong-5' },
      { icon: 'twitter', link: '' }
    ]
  },
  {
    avatar: './image/yjt.jpg',
    name: '杨珺婷',
    title: '博士生',
    links: [
      { icon: 'github', link: 'https://github.com/scilover' },
      { icon: 'twitter', link: '' }
    ]
  },
  {
    avatar: './image/cxx.jpg',
    name: '陈潇潇',
    title: '博士生',
    links: [
      { icon: 'github', link: 'https://www.researchgate.net/profile/Xiaoxiao-Chen-26' },
      { icon: 'twitter', link: '' }
    ]
  },
  {
    avatar: './image/yyb.jpg',
    name: '袁誉博',
    title: '博士生',
    links: [
      { icon: 'github', link: 'https://github.com/YuboYuanAAA' },
      { icon: 'twitter', link: '' }
    ]
  },
  {
    avatar: './image/hjm.jpg',
    name: '胡家鸣',
    title: '博士生',
    links: [
      { icon: 'github', link: 'https://scholar.google.com/citations?hl=en&user=syAjLw8AAAAJ&view_op=list_works&sortby=pubdate#' },
      { icon: 'twitter', link: '' }
    ]
  }
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>
      Our Team
    </template>
    <template #lead>
      A Collaborative & Diverse Group.
    </template>
  </VPTeamPageTitle>
  <VPTeamMembers
    :members="members"
  />
</VPTeamPage>
