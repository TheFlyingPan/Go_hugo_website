---
title: "{{ replace .Name "-" " " | title }}"
Date: {{ .Date }}
adressComp:
    adress: ""
    postalCode: "75000"
    city: "Paris"
    label: ""
when: {{ .Date }}
desciption: ""
photos: ""
draft: True
important: False
association: ""

---