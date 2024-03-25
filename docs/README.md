---
pageClass: home-page
# some data for the components

name: Zixin Wang 王梓昕
profile: /zixin.jpg
socials:
- title: google scholar
  icon: /icons/gs.svg
  link: https://scholar.google.com/citations?user=6qxfN_4AAAAJ&hl=en



cv: /CV_Zixin_Wang_Academic.pdf
bio: 3rd-year Master Student at Zhejiang University (ZJU)
email: zixin_wang AT zju DOT edu DOT cn
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I am a Master student in the [Department of Pyschology and Behavioral Sciences](http://www.psych.zju.edu.cn/) at [Zhejiang University](https://www.zju.edu.cn/). I obtained my Bachelor's degree in Psychology at [Southwest University](http://www.swu.edu.cn/), China.

Previously, I was a research assitant at [Virginia Tech](https://cs.vt.edu/), advised by [Dr. Yaxing Yao](http://www.yaxingyao.com/), [Southwest University](http://www.swu.edu.cn/), advised by [Dr. Qinghua He](http://he-lab.cn/).

I am interested in usable security and privacy, and HCI. I use quantitative (e.g., survey) and qualitative (e.g., interview, content analysis) methods in my research.

## Publications

### <font color=red>Usable Privacy and Security</font>
- **[USEC ’24]**
Tu Le, **Zixin Wang**, Danny Yuxing Huang, Yaxing Yao, and Yuan Tian. 2023.
Towards Real-time Voice Interaction Data Collection Monitoring and Ambient Light Privacy Notification for Voice-controlled Services.
*In Workshop on Usable Security and Privacy (USEC)*.

- **[USENIX Security ’23]**
**Zixin Wang**, Danny Yuxing Huang, and Yaxing Yao. 2023.
[Exploring Tenants’ Preferences of Privacy Negotiation in Airbnb](https://www.usenix.org/system/files/usenixsecurity23-wang-zixin.pdf).
*In 32nd USENIX Security Symposium*.

- **[USEC ’23]**
Stefany Cruz, Logan Danek, Shinan Liu, Christopher Kraemer, **Zixin Wang**, Nick Feamster, Danny Yuxing Huang, Yaxing Yao, and Josiah Hester. 2023.
[Augmented Reality’s Potential for Identifying and Mitigating Home Privacy Leaks](https://arxiv.org/pdf/2301.11998.pdf).
*In Workshop on Usable Security and Privacy (USEC)*.


## Services
**Conference reviewer**: CHI Late-breaking Work 2023, 2024, CSCW 2024, IMX 2024








<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img
          width 100%
          max-width 400px

</style>
