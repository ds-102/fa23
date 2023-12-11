---
layout: page
title: Home
nav_order: 1
description: A week-to-week description of the content covered in the course.
course:
  edstem: 
  faq: 
currWeekNumber: week-17-finals-week
---

# Data 102: Data, Inference, and Decisions

{: .mb-2 }
UC Berkeley, Fall 2023
{: .mb-0 .fs-6 .text-grey-dk-000 }


<!-- [Ed](https://edstem.org/){:target="_blank" .btn .btn-ed .mr-1 }
[Datahub](http://data102.datahub.berkeley.edu/){:target="_blank" .btn .btn-datahub .mr-1 }
[Gradescope](https://www.gradescope.com/){:target="_blank" .btn .btn-gradescope .mr-1 }
[Extenuating Circumstances](https://forms.gle/GRREdhkik6bKm9bJA){:target="_blank .btn .btn-blue .mr-1} -->

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

<!-- {: .highlight }
> Welcome to Data 102!  -->
{% assign announcement = site.announcements | last %}
{{ announcement }}


<a name="schedule"></a>
## Schedule
[**Jump to current week**](#{{page.currWeekNumber}}){: .btn }

{% for module in site.modules %}
{{ module }}
{% endfor %}

<!-- <script src="resources/assets/darkmode.js"></script>
<script>
  const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

  jtd.addEvent(toggleDarkMode, 'click', function(){
    if (jtd.getTheme() === 'custom_dark') {
      jtd.setTheme('light');
      localStorage.setItem("darkMode", 0);
      toggleDarkMode.innerHTML = "Toggle Dark Mode";
      toggleDarkMode.classList.add('dm-btn');
        toggleDarkMode.classList.remove('dm-dark-btn');
    } else {
      jtd.setTheme('custom_dark');
      localStorage.setItem("darkMode", 1);
      toggleDarkMode.innerHTML = "Return to the Light";
      toggleDarkMode.classList.add('dm-dark-btn');
      toggleDarkMode.classList.remove('dm-btn');
    }
  });

    window.addEventListener("DOMContentLoaded", (event) => {
      onLoad();
  });
</script> -->

