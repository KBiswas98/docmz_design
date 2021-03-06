# Documentation

---

## Organism

1. **FancyHeader**
    - ProfileMode (Boolean)
        - Whether header contains a Profile picture or not **[default false]**
    - LeftComp (Node)
        - Custom left component for header navigation bar
    - RightComp (Node)
        - Custom right component for header navigation bar
    - headerText (String)
        - Header text for the header navigation bar
    - showOverlayComponent (Boolean)
        - Whether to show overlay component in the component or not
    - overlayComponents (Node)
        - Custom overlay component(s) to show in the component
    - navigation (Object)
        - navigation object to be passed in **REQUIRED**
    - leftButtonClick (function)
        - function callback when left component is pressed
    - rightButtonClick (Function)
        - function callback when right component is pressed
    - style (Object)
        - Custom style object for the component
            - Container : styles for container of component
            - ChildContainer: styles for container of children in the component
    - children (Node)
        - children(s) passed to render inside component
1. **Container**
    - children (Node)
        - children(s) to render in component
    - style (Object)
        - Custom style object for component
            - Container: styles for container of component

---

## Molecules

1. **AvailDoctorContainer**
    - onPress (function)
        - function callback to get called when component is pressed
    - name (String)
        - name of the doctor
    - schedule (Array)
        - schedule data of doctor
    - navigation (Object)
        - navigation object for navigation screen **REQUIRED**
    - id (String)
        - id of current doctor
    - data (Object)
        - data about doctor
1. **Section**
    - HeaderText (String)
        - Header text for the section
    - children
        - children(s) to be render inside component
    - style
        - Custom style for the component
            - Container: styles for container of component
1. **DmzSearchbar**
    - placeholder (String)
        - placeholder text for the search bar input
    - onEndEditing (function)
        - function to be called when user submits the input
    - onChangeText (function)
        - funtion to be called when user types in the input box
1. **ToggleButton**
    - text0 (String)
        - first text to show in toggle switch
    - text1 (String)
        - second text to show in toggle switch
    - onToggle (function)
        - function to be called when user toggles switch
    - toggle (boolean)
        - value to tell the state of toggle switch
    - style (Object)
        - Custom style for the component

---

## Atoms

1. **DmzText**
    - text (String)
        - Text to show
    - type (Number)
        - different sizes for text
            - Available options **[0,1,2,3,4,5,6]**
                - Equivalent size **[8,10,12,15,20,30,40]**
    - center (Boolean)
        - Whether to align text horizontally center or not
    - gap_small (Boolean)
        - introduces **0.5 letterSpacing** in text
    - gap_medium (boolean)
        - introduces **0.75 letterSpacing** in text
    - gap_big (boolean)
        - introduces **1 letterSpacing** in text
    - lite (boolean)
        - makes fontWeight **300**
    - normal (boolean)
        - makes fontWeight **500**
    - semi_bold (boolean)
        - makes fontWeight **700**
    - bold (boolean)
        - makes fontWeight **800**
    - extera_bold (boolean)
        - makes fontWeight **900**
    - children (Node)
        - children(s) to render along with **text** prop's value
    - style (Object)
        - Custom styles for the component's text
