<script src="https://unpkg.com/launchdarkly-js-client-sdk@2.18.1/dist/ldclient.min.js"></script>

<h1>Greate Linkedin Learning Courses</h1>
<div style="position:relative;height:0;padding-bottom:56.25%"><iframe width="640" height="360" src="https://www.linkedin.com/learning/embed/git-for-teams/git-flow?autoplay=false&claim=AQHZr9Da3JIh0wAAAZItsaO8qrJum9ojCQ4u4xFxL3l01-myBQoQItqBifamwcHKbJ-PruN-NuaDGbIBJ0iAFf0Tya-vjJr4uyBdSV2rqxClbCq7BdROtQejZkCliGhYXTgltEFLgfpbYlWAmW1xzf3eLRSBY1smXXy23B-bbG_GbahDjonS_MNT0XEIFunP6OPZS6qbMmEK370Hllkb8TjTsfk7fVHTGeb2aeSzRg6Ys11uixNuEBolV5PzvMcvDHaQiI3oLrfgNMU219Fyh78XAGjIBVKMfOefYxkHJkJv9--kJS-Z0QqpgXtU43yizvxQXstsWoBv4f0w-kYTFcI2MV3efqpnEjtA2FJL1pX3zNgmVwqFPWn_FdOSynfwDhTH15q8FAuGFwxoJBY6FK3h3eK8vifCsKWXfQyWTUFNmsCDtI1RJLQkyUag9TMgyjtMG5M6SVuASg8it3yN0wnBKAqN6YztD_ePkBrSUdnWRl_ZRrYkH-G-JJIxP3BOq1bUj4VTBZeRu6gdMxqaznEOtIImTsn3y36_VtJJRDlNdh-feAVhjYdz6h9bggSwgJRHb4_OrjQfPfQ_CeJU3uv2MEz_eeTnYB4iNYp-LMQxN6ZO8vMdiYe3LiEvj-DhdO3SfGqdt6TZzw4wmU6uYYbWo41sSE-vEjboX24aoyzPa_6JMA9hzcOrP0YdIu21ggvPK9RX89gSfXXxSAwKpKzZkRCJeW8oxCyRpljDPPaRxhzGqiR1x1Q4DuVzvRDuy-soPwDqSbptDxxL-ki_lyxj8R8OLkvVDHF-irrxXA4Y61g-ZUKvcCpcOgfoaPgwh0oXuzuHtauMd6k7DqmgxQ1wfqL5ALgFimhf-r_4747PIKxF5SzQAkf0mi7Cj1W4BnoJD6CR0DcbjaC4GOWrDBnGSm2LF0zpuqBdXfSqupQbSJ2rlmDthmnIHYttBU2Qbewaz3WMM_tSHnGshUctLuysJdFkzzYJULA52PXjxxjlhuRQmAfb_ADpM-LNGEMS36xub7tt8i0bCFKFMQNZ87820YksRz71ACsKlwCHFVdZhMU82eBxsifFZFL7kDZYzZfovaR4jBWo0mL8ZfxBaTbA6R0jpVYzqT6Zmp2pZ0WivpBDvb621AEjyzZCrtWye1rRFnPk91z3I6nQo7bpHVq71Kev0eLDV9rn3HP7lW8hskuwOmJkh_rbVb8HYxmN1A" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true" frameborder="0" style="position:absolute;width:100%;height:100%;left:0"></iframe></div><p><strong><a href="https://www.linkedin.com/learning/git-for-teams/git-flow?trk=embed_lil">Git flow</a></strong> from <strong><a href="https://www.linkedin.com/learning/git-for-teams?trk=embed_lil">Git for Teams</a></strong> by <strong><a href="https://www.linkedin.com/learning/instructors/kevin-bowersox?trk=embed_lil">Kevin Bowersox</a></strong></p>

<h1>Great Udemy Courses</h1>
<div style="padding: 20px; border: 1px solid #ccc; background-color: #f9f9f9;">
    <p><strong>Course:</strong> <a href="https://www.udemy.com/share/102lEQ3@0M7rfOmvPMPdqk8_TwIAiSGQTJpgaMHypcQCc55CL6PQXQPEksWZVfIbX2ibI5FxCw==/">Learn Android Development</a></p>
    <p>Click the link to explore the course and start learning.</p>
</div>

<div id="preview" style="display:none">
    <h1>Great Udemy Courses with MERN</h1>
    <div style="padding: 20px; border: 1px solid #ccc; background-color: #f9f9f9;">
        <p><strong>Course:</strong> <a href="https://www.udemy.com/share/102g8S3@j-6YVMHdAGjn4H0tnyBi8kREuGTHQD4jol4Y1UhTi6FOfIVpE-S_4dPwuXDykD3qRw==/
        ">React, NodeJS, Express & MongoDB - The MERN Fullstack Guide</a></p>
        <p>Build fullstack React.js applications with Node.js, Express.js & MongoDB (MERN) with this project-focused course.</p>
    </div>
</div>

<script>
  var clientId = "66f55dc801838b0863d50572";
  var flagName = "course-preview";
  var user = { anonymous: true };

  var ldclient = window.LDClient.initialize(clientId, user);

  ldclient.on("ready", function() {
    document.getElementById("preview").style.display = ldclient.variation(flagName, false) ? "block" : "none";
  });

  ldclient.on("change:" + flagName, function(newVal, prevVal) {
    document.getElementById("preview").style.display = newVal ? "block" : "none";
  });
</script>
