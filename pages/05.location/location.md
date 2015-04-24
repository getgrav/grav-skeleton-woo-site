---
title: Location
title2: Contact
menu: location
onpage_menu: true
map: <iframe src="http://maps.google.com/maps?f=q&amp;source=s_q&amp;hl=en&amp;geocode=&amp;q=Brooklyn,+New+York,+NY,+United+States&amp;aq=0&amp;sll=37.0625,-95.677068&amp;sspn=61.282355,146.513672&amp;ie=UTF8&amp;hq=&amp;hnear=Brooklyn,+Kings,+New+York&amp;ll=40.649974,-73.950005&amp;spn=0.01628,0.025663&amp;z=14&amp;iwloc=A&amp;output=embed"></iframe>

simple_form:
  token: "token-by-simpleform"
  template_file: "contact"

  fields:
      name:
        type: "text"
        title: "Name"
        default: ""
        placeholder: "Name"
        class: ""
        required: true
      email:
        type: "email"
        title: "Email"
        default: ""
        placeholder: "E-mail"
        class: ""
        required: true
      phone:
        type: "text"
        title: "Phone"
        default: ""
        placeholder: "Phone"
        class: ""
        required: false
      message:
        type: "textarea"
        title: "Message"
        default: ""
        placeholder: "Message"
        class: ""
        required: true
      submit:
        type: "submit"
        title: "submit"
        default: ""
        class: "btn-link btn-link2"
  messages:
      success: "Your message has been sent."

---

##Postal Address
<address markdown="1">
**8901 Marmora Road, Glasgow, D04 89GR.**

Telephone: +1 959 603 6035

FAX:  +1 504 889 9898

E-mail: mail@demolink.org
</address>

<address markdown="1">
**9867 Mill Road, Cambridge, MG09 99HT**

Telephone: +1 959 603 6035

FAX: +1 504 889 9898

E-mail: mail@demolink.org
</address>



