This zip archive contains data of your contacts derived from Yahoo Mail.

Inside the zip archive, you can find the following files:
    - ContactsData.json which lists all the derived contact details, including but
      not limited to name, email addresses, phone numbers, etc.
    - Images if you have uploaded any pictures for your contacts. The image
      files are names as {contactId}-{contactName}.png

For example if you have two contacts in ContactData.json file like:

[
     {
         "data": [
            "Name: Lisa",
            "smtp:email_address@domain.com; (source:yahoo)",
            "tel:+11234567890; (type: mobile); (source: iphone)"
            "profile_image_url: /photos/relative/url; (source: user)"
         ]
     },
     {
         "data": [
            "Name: Ben",
            "smtp:eail_addr@domain.com; (source: mail)",
            "tel:+11231231234; (type: work); (source: iphone)"
            "profile_image_url: /photos/relative/url; (source: user)"
         ]
     }
]

Then you will have two image files in the zip archive named as 1a2b.3c4d-Lisa.png
and 1234.abcd-Ben.png along with the ContactData.json file.
