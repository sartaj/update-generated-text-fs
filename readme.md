# Update Generated Text

Update or append a block of generated text from a file. Uses `update-generated-text`.

## Example

```javascript
import updateGeneratedFile from 'update-generated-text-fs'

const startString = '# _Start_Generated_Text'
const endString = '# _End_Generated_Text'

const newContents = '
coverage
.tmp
'

const file = __dirname + '.gitignore'

const newText = updateGeneratedText(
  startString,
  endString,
  newContents,
  file
)
```
