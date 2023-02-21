---
layout: page
title: Unser Kalender
share-description: Ein Kalender mit allen für den Roverserver relevanten Terminen und iCalendar Unterstützung
menu:
  main:
    name: "Kalender"
    weight: 3
---

<script>
function copyiCal() {
   /* Copy the textto clipboard */
  navigator.clipboard.writeText("https://ics.teamup.com/feed/ksoxt1yh49zs6x8vqb/0.ics");

  /* Alert the copied text */
  alert("iCal Link in Zwischenablage kopiert");
}
</script>

<style>
  .button {
  background-color: #CC1F1F; /* Red */
  border: none;
  color: white;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  position: relative;
  float: right;
}
</style>

<iframe src="https://teamup.com/ksoxt1yh49zs6x8vqb?showHeader=0&showProfileAndInfo=0&showSidepanel=1&showViewSelector=1&showMenu=1&showAgendaHeader=1&showAgendaDetails=1&showYearViewHeader=1" style="width: 100%; height: 800px; border: 1px solid #cccccc" frameborder="0"></iframe>

Zum eigenen Kalender [hinzufügen](https://calendar.teamup.com/kb/subscribe-to-teamup-icalendar-feeds/) <button class="button" onclick="copyiCal()">iCal Link Kopieren</button>
