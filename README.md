<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />  
    <title>My View App</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
    <link rel="stylesheet" type="text/css" href="./style.css" />
  </head>
  <body>
    Preeti 2
{{{data.req_card_number}}}
 
  {{#each data}}
    Key: {{@key}} Value = {{this}}
{{/each}}
  </body>
</html>
