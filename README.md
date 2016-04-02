# Resume

Simple, responsive and printable resume in HTML and CSS made dynamic using Jekyll.

http://aviaryan.github.io/resume

All resume content is stored in yaml files (skills.yml, projects.yml ..) in the `_data` directory. 

For local development, create an empty file named `local` in project root. This will ensure that local resources are loaded by Jekyll instead of CDN's.

Changing order of categories in resume is easy. :wink: Just change the include orders in `index.html`

```html
{% include education.html %}
{% include skills.html %}
{% include projects.html %}
{% include awards.html %}
{% include social.html %}
{% include contact.html %}
{% include references.html %}
```