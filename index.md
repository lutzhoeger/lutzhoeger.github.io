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
  data-dpol="https://dev.valassis.eu/instances/Wobrock-Thulium/?token=Thulium%7C%7C%7C%7C%7CRhlatJpNL4o%253D%7C1644250130761%7Cucc%3D0000000000000644250127001&digest=5Otrrx%2F1vSl0PfECwx5Qm4bg%2B8Q%3D">
</div>
