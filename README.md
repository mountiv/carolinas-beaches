# Carolinas Beaches Store

### Paula Snyder
- Telegram: +1 252 944 9413
- Phone:  +1 252 944 9413
- Email: psnyder1982@icloud.com

### Nazar Dobroznai
- Telegram: mountivdev
- Email: mountiv.solution@outlook.com


```
theme download
```
```
theme watch --allow-live
```

- To add sub-collections, we can add metafiled into colllection.
    - setting/custom data/collection

- {% %} and {%- -%}
    >The only difference is that one strips the white space and the other doesn't.
    >So this {% %} will keep any white space around it.
    >And this {%- -%} will strip the white space. The same applies for {{ }} and {{- -}} .

- Get **Collection** Object by **handle**
    ```
    {% assign boys_collection = collections['boys'] %}

    {% if boys_collection %}
    <h2>{{ boys_collection.title }}</h2>
    <p>{{ boys_collection.description }}</p>
    {% endif %}
    ```