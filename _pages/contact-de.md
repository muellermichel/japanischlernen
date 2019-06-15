---
permalink: "/contact-de/"
title:  "Kontakt"
---

## Kontakt

<form id="contactform" method="POST">
    <table>
        <tr><td>Name:</td><td><input style="width:100%;" type="text" name="name" required></td></tr>
        <tr><td>Email: </td><td><input style="width:100%;" type="email" name="_replyto" required></td></tr>
        <tr><td>Nachricht: </td><td><textarea style="width:100%;" name="message" required></textarea></td></tr>
        <tr><td colspan="2"><input style="width:100%;" type="submit" value="Senden"></td></tr>
    </table>
    <input type="text" name="_gotcha" style="display:none" />
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'mihokomueller' + '@' + 'gmail' + '.' + 'com');
</script>