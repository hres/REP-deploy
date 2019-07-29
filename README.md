# REP-deploy
Regulatory Enrolment Program (REP) production deployment environment

Use the prod branch to deploy the to the production web site. All other branches ignores.
Should mark the branch with releases, and description of why the release is happening

Construction page

replace the following html fragement with the index page or certain form main html page, such as product.html for PI form.

<!DOCTYPE html>
<html>
<head>
    <!-- HTML meta refresh URL redirection -->
    <meta http-equiv="refresh"
          content="0; url=https://construction.hres.ca/">
</head>
<body>
<p>The page has moved to:
    <a href="https://construction.hres.ca/">this page</a></p>
</body>
</html>