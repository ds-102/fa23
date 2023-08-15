---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.
course:
  edstem: 
  faq: 
currWeekNumber: 1
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

{: .highlight }
> This website is still a work in progress. All contents on this page are subject to change until this message is taken down.


<a name="schedule"></a>
## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}

