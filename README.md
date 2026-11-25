# ki-projects.github.io

<script>
fetch('https://github.com')
  .then(response => response.json())
  .then(data => {
    data.forEach(item => console.log(item.name));
  });
</script>
