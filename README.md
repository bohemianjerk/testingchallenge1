# testingchallenge1
http://testingchallenges.thetestingmap.org/index.php with answers


<ins> put info in the text field where possible </ins>

* You made the user admin
  f12 -> Elements -> <input type="hidden" name="user_right_as_admin" value="0"> -> change to 1 -> Submit
* Missing css
    f12 -> console -> detailsoverviewnow.css -> put in field -> submit
* You looked at the page source
  f12 -> elements -> to the end -> dfjwGGe82H43g3uRiy53h -> submit
* You looked at the cookie
  f12 -> network -> index.php -> headers -> cookie -> TestingChallenge=You_have_checked_the_cookie_content._Add_oi32jnxd42390slk345_in_the_First_Name_field_to_mark_this_case
* Non ASCII
  "ыыыыыы"
* Space
  " "
* Minimum value
  "s"
* Space values at the beginning
  "    s"
* Maximum values
  AmberAmberAmberAmberAmber
* Basic XSS
  <img src=x onerror=alert(1)>
* You used html tags
  <strong>Gheorghe_
* More than maximum values
  AmberAmberAmberAmberAmberAmberAmber
* Basic Sql injection
  ' OR 1=1
* Space in the middle
  "beep   boop"
* Average value
  "idk"
* Other chars then alphabetic
  "1232123"
* Space values at the end
  "d       "
* Empty value
    
