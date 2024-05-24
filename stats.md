---
title: Statistics
layout: statistics
description: Statistics
bodyClass: page-statistics
lang: en
---

<div id="testSample"></div>

<script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
<script>
  let testElem = document.getElementById('testSample');

  axios.get('https://api.sampleapis.com/coffee/hot')
  .then(response => {
    testElem.innerHTML = JSON.stringify(response.data, null, 2);
  })
  .catch(error => {
    console.error(error); // This will log any errors during the request
  });

</script>