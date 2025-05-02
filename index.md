---
layout: home
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_home

# image for page specific usage
#img: ":home-heading.jpg"
# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
# don't forget that this is root index.html. If you disable this, there will be no index.html page to open
#published: false
#---
#
#{%- comment -%} Please delete below and place your page content here {%- endcomment -%}
#
#{%- include util/auto-content-generator.liquid -%}
#{{ website_info_text_first }}
#
#{{ website_info_text_second }}



---
{%- if site.data.conf.main.language_switch == false %}
<script>
  var userLang = navigator.language || navigator.userLanguage;
  if (userLang.startsWith('ko')) {
    window.location.href = '/ko/';
  }
</script>
{% endif %}

## Essential Habits to Become a Software Architect  
**To enhance your software design skills, adopting the right habits is essential!**  
This course explains the key habits necessary to become a successful software architect and provides a practical guide to implementing them.  

### Course Content  
- 7 essential habits every software architect must develop  
- Practical methods to apply these habits  

[![Software Architect Course Image]({{ ":habits-of-software-architect.png" }})](https://www.udemy.com/course/habits-of-software-architect/)  

👉 [Udemy Course: Essential Habits to Become a Software Architect](https://www.udemy.com/course/habits-of-software-architect/)  

🆓 **This course is free, so enroll without hesitation!**  

<div class="row about-divider">  
 <hr>  
</div>  

---

## Effective Programming with AI  
**How should developers adapt in the AI era?**  
This course provides a detailed guide on leveraging AI effectively in software development. Instead of using AI merely as a tool, learn how to accelerate development and maximize efficiency with strategic approaches.  

### Course Content  
- The evolving role of programmers in the AI era  
- Practical techniques for AI-assisted programming  
- Real-world examples demonstrating AI-powered development  

[![AI Programming Course Image]({{ ":effective-programming-with-ai.png" }})](https://www.udemy.com/course/effective-programming-with-ai/)  

👉 [Udemy Course: Effective Programming with AI](https://www.udemy.com/course/effective-programming-with-ai/)  

✨ Highly recommended for developers looking to enhance their skills with AI!  
