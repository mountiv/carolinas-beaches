# Carolinas Beaches Store

`Uploaded: August 7, 2023`

![screencapture-carolinasbeaches-store-collections-boardwalk-2023-08-07-12_32_09](https://github.com/mountiv/carolinas-beaches/assets/121834775/f4327512-5027-40ff-9cf2-4e1d408f7119)

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
