Themes and Styles:

- Technically, they're both the same thing
- Both declared using the `<style>` tag
- The only difference between the mis how they're used:
    - Themes == Styles used in a special way

- At their simplest, themes and styles are just key-value stores

#### Attributes

- The key to the puzzle
- Attributes are just keys
- They also declare their value's format type


**Attributes format types:**

Resource Types:
- fraction
- float
- boolean
- color
- string
- dimension
- integer

Special Types:
- flag
- enum
- reference

Declare attributes in resources:

<attr name="background"
      format="reference|color" />

Attributes Namespaces

- All attributes provided by the framework are in the `android` schema

`<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:background="..."`