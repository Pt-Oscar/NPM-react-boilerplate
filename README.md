# Example

This is a example

## Dependencies

IMPORTANT: install react-draggable component for this npm package

## Installation



```bash
npm install example
```

## Usage

```javascript
import Example from 'example';
          <Example
            id="examle-id"
            moveTo="left"
            backgroundColor="white"
            onStartPopoverMovement={()=>{}}
            onStopoPopoverMovement={()=>{}}
            content={<div> </div>}
            isVisible={true}
          />
```

## Props 


**id** type string --id of the popover


**moveTo** type string (left, right, top, down) --animation movement on popover appear


**backgroundColor** type string .-- color of the background on popover


**onStartPopoverMovement** type function -- function on start popover movement


**onStopPopoverMovement** type function -- function on stop popover movement


**content** type html -- html of the content of the div


**isVisible** type bool -- is visible popover

**zIndex** type string -- zindex for popover if needed default (1030)




## License
[MIT](https://choosealicense.com/licenses/mit/)