<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>

<body>

  <h1>Sales Force Form</h1>

  <form action="https://webto.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method="POST">

    <input type=hidden name="oid" value="00D6g000003rjfO">
    <input type=hidden name="retURL" value="https://zaurinvictus.github.io/salesforce/thankyou">
   
    <!--  ----------------------------------------------------------------------  -->
    <!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
    <!--  these lines if you wish to test in debug mode.                          -->
    <!--  <input type="hidden" name="debugEmail" value="maxmehm2020@gmail.com">   -->
    <!--  ----------------------------------------------------------------------  -->

    <label for="first_name">First Name</label>
    <input id="first_name" maxlength="40" name="first_name" size="20"
      type="text" /><br>
    <label for="last_name">Last Name</label>
    <input id="last_name" maxlength="80" name="last_name" size="20"
      type="text" /><br>
    <label for="email">Email</label>
    <input id="email" maxlength="80" name="email" size="20" type="text" /><br>

    Garage usage (check all that apply):
    <select id="00N6g00000Ffch2" multiple="multiple" name="00N6g00000Ffch2" title="Garage usage (check all that apply)">
      <option value="Standard - Vehicles regularly parked in garage">Standard - Vehicles regularly parked in garage
      </option>
      <option value="Mechanical Workshop (oil changes)">Mechanical Workshop (oil changes)</option>
      <option value="Woodworking Workshop">Woodworking Workshop</option>
      <option value="Other (please explain below)">Other (please explain below)</option>
    </select>
    <br>

    Check all that describe your garage:
    <select id="00N6g00000FfchM" multiple="multiple" name="00N6g00000FfchM"
      title="Check all that describe your garage">
      <option value="Dry">Dry</option>
      <option value="Humid">Humid</option>
      <option value="Constant Water Flow">Constant Water Flow</option>
      <option value="Snow">Snow</option>
      <option value="Muddy">Muddy</option>
      <option value="Other ( please explain below)">Other ( please explain below)</option>
    </select>
    <br>
    Comments and Questions:
    <textarea id="00N6g00000FfchW" name="00N6g00000FfchW" type="text" wrap="soft"></textarea><br>

    Would you like us to send you a sample?:
    <input id="00N6g00000Ffchq" name="00N6g00000Ffchq" type="checkbox"
      value="1" />
    <br>

    <input type="submit" name="submit">
  </form>


</body>

</html>