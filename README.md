# hashbrowns

A Python module for locality senstive hashing based on <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=0ahUKEwjKx4W6spjVAhVLxVQKHZgmCqIQFggvMAI&url=http%3A%2F%2Feduardovalle.com%2Fwordpress%2Fwp-content%2Fuploads%2F2014%2F10%2Fsilva14sisapLargeScaleMetricLSH.pdf&usg=AFQjCNEzBzXg_F6lu0VWZ2sQI3x9lltrQQ">Silva et al (2014)</a>, and also <a href="https://graphics.stanford.edu/courses/cs468-06-fall/Papers/12%20lsh04.pdf">Datar et al (2004)</a>.

Still very much a work-in-progress. 

TODO:
<ul>
  <li>Add hdf5 storage via h5py</li>
  <li>Add sql storage via sqlite3</li>
  <li>Add support for data supplied as bytes (memory/mmap), ie sequence data</li>
  <li>Switch to using `randomkit` from `numpy` instead of `rand` from `stdlib`
  <li>Write all the tests. Test all the things.</li>
  <li>Demos
    <ul>
      <li>lsh for denstity-based clustering (as a fast approximation for kNN problem in OPTICS algorithm)</li>
      <li>lsh accelerated multiple alignment</li>
      <li>lsh for classification</li>
      <li>lsh for estimating mutual information</li>
      <li>pretty much scaling any kNN based algorithm to large data space</li>
     </ul>
   </li>
