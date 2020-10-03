# flexbox
💪 🗳️

just some notes on flexbox by moi:

 first things first: *display: flex* set ALL children as FLEX items.
    - FLEX-CONTAINER: takes width of entire view window
    - INLINE FLEX: only tkaes necessary space to contain all children elements
    
 WORKING WITH FLEX-DIRECTION:
     
     - the default flex-direction is ROW
     - with a ROW, the contents (children flex items) will STACK horizontally, and SPAN vertically
     - with a COLUMN, rather than child flex-items stacking side-by-side, the column will stack them on top of one another
     
     KEY TERMS: 
        -- MAIN AXIS: Axis used going left to right (when flex-direction is ROW)
            -- if flex-direction is set to COLUMN, the main axis will run top to bottom
            
        -- CROSS AXIS: Axis used going top to bottom (when flex-direction is ROW)
            -- if flex-direction is set to COLUMN, the cross axis will run left to right
            
     -!!! CSS rules like ROW-REVERSE and COLUMN-REVERSE will command the main axis to run in the opposite direction
            -- row-reverse will set the main-axis to run from right to left
            -- column-reverse will set the main-axis to run from bottom to top

WORKING WITH FLEX-WRAP:
    
    - NOTE: nowrap; is the default setting for flex-items
    - NOTE: by default, flex-items will also try to strecht to the entire height of their container
    -- the nature of flexbox is to be flexible, setting an explicit width on a group of flex-items will still allow the flex property to justify          the size of each item
    -- {flex-wrap: wrap} will wrap the child elements into a grid-like manner.
    -- each flex-item will stretch across its container
       -- wrap-reverse will change the cross-axis from bottom to top. 
       
