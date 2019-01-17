### medium-editor
---
https://github.com/yabwe/medium-editor

```js
var elements = document.querySelectorAll('.editable'),
  editor = new MediumEditor(elements);
  
var editor = new MediumEditor('.editor', {
});

var editor = new MediumEditor('.editable',{
  toolbar: {
    allowMultiParagraphSelection: true,
    buttons: ['bold', 'italic', 'underline', 'anchor', 'h2', 'h3', 'quote'],
    diffLeft: 0,
    diffTop: -10,
    firstButtonClass: 'medium-editor-button-frist',
    lastButtonClass: 'medium-editor-button-last',
    relativeContainer: null,
    standardizeSelectionStart: false,
    static: false,
    align: 'center',
    sticky: false,
    updateOnEmptySelection: false
  }
});

var editor = new MediumEditor('.editable', {
  placeholder: {
    text: 'Type your text',
    hideOnClick: true
  }
});

var editor = new MeduimEditor('.editable', {
  placeholder: false
});

var editor = new MediumEditor('.editable', {
  toolbar: {
    buttons: ['bold', 'italic', 'underline', 'anchor']
  },
  anchor: {
    customClassOption: null,
    customClassOptionText: 'Button',
    linkValidation: false,
    placeholderText: 'Paste or type a link',
    targetCheckbox: false,
    targetCheckboxText: 'Open in new window'
  }
});

editor.removeElements(document.querySelector('#myElement'));
var removeElements = [];
editor.elemenets.forEach(function(element){
  if(!$(element).parents('body').length){
    removeElements.push(element);
  }
});
editor.removeElements(removedElements);
```

```
```

```
```


