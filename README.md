# tag-manager

A Polymer Element that manages tags saved using ajax requests.

### Example
```html
<tag-manager
  auth-username="myUser"
  auth-password="myPassword"
  entity-endpoint="http://localhost:1234/projects/PROJECT/entities/ENTITY_TYPE/ids/ENTITY_ID/tags/TAG"
  extraction-endpoint="http://localhost:1234/projects/PROJECT/entities/ENTITY_TYPE/ids/ENTITY_ID/extractions/EXTRACTION_FIELD/keys/EXTRACTION_KEY"
  list-endpoint="http://localhost:1234/projects/PROJECT/tags"
  project="myProject"
  tag="{{tag}}"
  tag-list="{{tagList}}"
  tag-manager="{{tagManager}}">
</tag-manager>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

