---
title: Contact
layout: contact
description: Contact
---
I'll be pleased to answer your inquiries in regard to the services I provide

<table>
  <thead style="background-color: #333; color: #fff;">
  <tr>
   <th>Day</th>
   <th>Schedule</th>
  </tr>
  </thead>

  <!-- beging table body -->
  <tbody>
  {% for entry in site.data.schedule %}
    <tr>
     <td>{{entry.day}}</td>
     <td>{{entry.schedule}}</td>
    </tr>
  {% endfor %}
  <!-- ending table body -->
  </tbody>
</table>
