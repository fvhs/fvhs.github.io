<h1 align="center">
  FVHS.GitHub.io Respository
</h1>

Welcome to the FVHS.GitHub.io repositiory!

This is where FVHS Network data is congregated and hosted. Data is open source and accessible by requesting fvhs.github.io/data/[Insert filename].


<h2>Examples</h2>

<b>Axios</b>
```
import axios from "axios"
axios.get('fvhs.github.io/data/[Insert filename]')
  .then(function (response) {
    // handle success
    console.log(response);
  })
  .catch(function (error) {
    // handle error
    console.log(error);
  })
  .then(function () {
    // always executed
  });
```
