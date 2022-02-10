<style>
  .inner {
    max-width: 1024px !important;
  }
</style>

<script>
  function logEvent(event) {
    console.log("logging an event");
    console.log(JSON.stringify(event));
  }
</script>

[link to a test page](test/index.md)

[link to second test](test2.md)

<script src="https://dev.valassis.eu/scripts/core/util/init.js"></script>
<div 
  id="ValassisGallery" 
  style="width: 100%" 
  data-lang="en"
  data-logEvent="logEvent"
  data-dpl="https://dev.valassis.eu/instances/Wobrock-Thulium/?token=Thulium%7CExample-216047%7C%7C%7C%7CRhlatJpNL4o%253D%7C1644510785825%7Cucc%3D0000000000000644510783001&digest=sTPBMVHsXg5n2QSATRnfySbtWyo%3D">
</div>
