<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-4R0F3F4K3P"></script>
<script>
  window.dataLayer = window.dataLayer || [];

  function gtag() {
    dataLayer.push(arguments);
  }
  gtag('js', new Date());

  gtag('config', 'G-4R0F3F4K3P');

</script>
<h1>Bocheng Cui</h1>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script>
  $(function () {
    $('#aboutme').load('aboutme/aboutme.html');
    $('#news').load('news/news.html');
    $('#talks').load('talks/talks.html');
    $('#projects').load('projects/projects.html');
    $('#experience').load('experience/experience.html');
    $('#education').load('education/education.html');
    $('#publications').load('publications/publications.html');
  })

</script>


<div class="profile-sections">
  <section id="aboutme"></section>
  <section id="publications"></section>
  <section id="projects"></section>
  <section id="talks"></section>
  <section id="experience"></section>
  <section id="education"></section>
</div>
<style>
  .profile-sections > section + section { margin-top: 2.5rem; }
</style>
