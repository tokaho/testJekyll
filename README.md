#Introduction

| Things we will do             |
| ------------------------------|
|1.Starting isses               |
|2.Project board                |
|3.Set up reamdme.md            |
|4.Show our team to the Internet|
|5.Keep checkinging...          |
|6.Write C code                 |
|7.Get a status badge           |
|8.Promote our repo             |

#Code

#Contributors
<ul>
{% for member in site.stu -%}
  <li>
  <p> <img src="{{member.image}}"> @ {{ member.user }}({{ member.name }})
    <li>{{member.content | markdownify}}</li>
  </p>
  </li>
{%- endfor -%}
</ul>


| Issue |People      |
|:-----:|------------|
| 1     |            |
| 2     |            |
| 3     |KUANG, Yurui|
| 4     |TO, Ka Ho   |
| 5     |            |
| 6     |            |
| 7     |            |
| 8     |            |
