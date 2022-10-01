---
pageClass: home-page
# some data for the components

name: Zixin Wang 王梓昕
profile: /zixin.jpg

socials:
  - title: Zixin Wang
    icon: "/icons/github.svg"
    link: https://github.com/mtobeiyf
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: https://www.instagram.com

cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: 2rd-year Master Student at ZJU
email: zixin_wang AT zju DOT edu
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I am Master student in the [Department of Pyschology and Behavioral Sciences](http://www.psych.zju.edu.cn/) at the [Zhejiang University](https://www.zju.edu.cn/). I obtained my Bachelor's degree in Psychology at [Southwest University](http://www.swu.edu.cn/), China.

## Research Interests
Human-Computer Interaction, Health Informatics, Decision Making, Behavioral Data Science

## News

- [08/2022] One paper accepted and one paper accepted to [HICSS](https://hicss.hawaii.edu/)! See you in Hawaii!
- [09/2021] I've decided to pursue my Master degree in the [ZJU](https://www.zju.edu.cn/), and spend the next 3 years in Hangzhou, China.
- [06/2020] I'm an Excellent College Graduate of Chongqing Province, China.
- [04/2020] One paper accepted to [Psychology:Techniques and Application](http://www.xljsyyy.com/)




## Awards & Honors

### Contests

- First place in **The Hogwarts House Cup**


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
