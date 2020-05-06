# Featured Image

## Overview of component

---

Image with corresponding text and optional button. Can be used on the homepage or a landing page.

There are slight differences when using this feature on landing page. First, the page title is an H1 -- which is necessary for SEO. Second, the body is the short description, which is used to allow the page to be shareable in other places on the site, including home and search. Third, because the page title is embedded in the feature, we want to make sure that page level fields are also capture (which is listed at the bottom.)

### Design

---

[https://codepen.io/wcmsn/full/jONQbPp](https://codepen.io/wcmsn/full/jONQbPp)

### Functionality

---

OnClick/OnTap of button, user is brought to target page.

### Specifications

---

Note that the source of content is the home page content type.

| ﻿id,Name,field type,content specs,vx specs,notes            |                                                                                                                                                      |
|------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1,feature-image,image,source                               | feature-image,,                                                                                                                                      |
| 2,feature-title,title,source                               | title,,The SAMHSA homepage is an exception to this rule.                                                                                             |
| 3,feature-body,text,homepage source                        | body,,                                                                                                                                               |
| 4,button,inverted-button-1 / url link,,,"tag for analytics |                                                                                                                                                      |
| 508                                                        | add aria-label attribute indicating what learn more about what? For instance aria-label=""Learn more about Caring for Every Child’s Mental Health""" |

[Feature Image - Landing Page](https://www.notion.so/a149a92a670a479d99fdccc3745a3ecc)
