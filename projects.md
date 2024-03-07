---
layout: default
title: Projects
permalink: /projects/
---
# [Home](/) | [Projects](/projects/) | [Classes](/classes/) | [Contact](/contact/)
# Projects
## Onyx Aircraft Design

<img src="/assets/OnyxIso.webp" alt="OnyxIso" style="border-radius: 10px;">

<div class="gallery">
  <img src="/assets/OnyxIso.webp" alt="Image 1" onclick="openModal('/assets/OnyxIso.webp')">
  <img src="/assets/OnyxElectrical.webp" alt="Image 2" onclick="openModal('/assets/OnyxElectrical.webp')">
  <!-- Add more image tags as needed -->
</div>

<div id="myModal" class="modal">
  <span class="close-btn" onclick="closeModal()">&times;</span>
  <img id="modalImage" src="" alt="Zoomed Image">
</div>

<script>
  function openModal(imageSrc) {
    document.getElementById('modalImage').src = imageSrc;
    document.getElementById('myModal').style.display = 'flex';
  }

  function closeModal() {
    document.getElementById('myModal').style.display = 'none';
  }
</script>

