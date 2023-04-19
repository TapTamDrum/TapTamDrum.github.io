---
layout: page
title: Audio Player 
description: 
img: assets/img/12.jpg
importance: 1
category: Audios
---
   
   
   ----

   # Audio Player 

   ----

<style>
table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  border: 1px solid black;
  padding: 4px;
  text-align: center;
  width: 10%;
}

th {
  background-color: lightgray;
}
</style>

<table>
  <thead>
    <tr>
      <th>INDEX</th>
      <th>GT</th>
      <th>IH</th>
      <th>IHS</th>
      <th>IH (Mix)</th>
      <th>IHS (Mix)</th>
    </tr>
  </thead>
  <tbody>
    {% for x in (0..2) %}
{% assign path = site.baseurl | append: "/explore/assets/A1/000_drummer1-eval-session-4_soul-groove4_80_beat_4-4_best_2bar_segment_6/Participant_1_repetition_0.wav" %}
<p>Path for index {{ x }}: {{ path }}</p>
<tr>
  <td>{{ x }}</td>
  <td><audio controls><source src="/explore/assets/A1/000_drummer1-eval-session-4_soul-groove4_80_beat_4-4_best_2bar_segment_6/Participant_1_repetition_0.wav"></audio></td>
  <td><audio controls><source src="/explore/assets/A1/000_drummer1-eval-session-4_soul-groove4_80_beat_4-4_best_2bar_segment_6/Participant_1_repetition_0.wav"></audio></td>
  <td><audio controls><source src="/explore/assets/A1/000_drummer1-eval-session-4_soul-groove4_80_beat_4-4_best_2bar_segment_6/Participant_1_repetition_0.wav"></audio></td>
  <td><audio controls><source src="/explore/assets/A1/000_drummer1-eval-session-4_soul-groove4_80_beat_4-4_best_2bar_segment_6/Participant_1_repetition_0.wav"></audio></td>
  <td><audio controls><source src="/explore/assets/A1/000_drummer1-eval-session-4_soul-groove4_80_beat_4-4_best_2bar_segment_6/Participant_1_repetition_0.wav"></audio></td>
</tr>
{% endfor %}
  </tbody>
</table>
