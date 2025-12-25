# authority-pillar-nervous-system
Tgis is an authority pillar for the neural safety switch digital product. This page helps create trust for Google. 

#top of page -->
# <?php include "partials/nav.html"; ?>

#bottom -->
# <?php include "partials/footer.html"; ?>

add this to pages 
<div id="header"></div>
...
<div id="footer"></div>

add this to pages 
<script>
function loadPartial(id, file) {
  fetch(file).then(r => r.text()).then(html => {
    document.getElementById(id).innerHTML = html;
  });
}
loadPartial('header', '/partials/header.html');
loadPartial('footer', '/partials/footer.html');
</script>
