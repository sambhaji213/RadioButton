# RadioButton
Radio buttons are normally used together in a RadioGroup. When several radio buttons live inside a radio group, checking one radio button unchecks all the others.  we will use “android.widget.RadioButton” class to render radio button, and those radio buttons are usually grouped by android.widget.RadioGroup. If RadioButtons are in group, when one RadioButton within a group is selected, all others are automatically deselected.

A RadioButton consists of two states : checked and unchecked. Clicking an unchecked button changes it to the checked state and unselects the previously selected RadioButton. To toggle a checked state to unchecked state, we need to chose another item. Clicking a checked state button doesn’t do any good. A RadioGroup is a set of RadioButtons. Radio Buttons that have different parent ViewGroup can’t be termed as a RadioGroup.

Some of the attributes of Radio Buttons and RadioGroups and their properties are listed below:
* android:orientation : This property on the Radio group defines the orientation to position its child view consisting of Radio Buttons. It can be either horizontal or vertical
 * check(id) : This sets the selection to the radio button whose identifier is passed in parameter. -1 is used as the selection identifier to clear the selection
* clearCheck() : It clears the selection. When the selection is cleared, no radio button in this group is selected and getCheckedRadioButtonId() returns null
* getCheckedRadioButtonId() : It returns the identifier of the selected radio button in this group. If its empty selection, the returned value is -1
* setOnCheckedChangeListener() : This registers a callback to be invoked when the checked radio button changes in this group. We must supply instance of RadioGroup.OnCheckedChangeListener to setOnCheckedChangeListener() method

<a href="url"><img src="https://github.com/sambhaji213/RadioButton/blob/master/screenshot/home.png" align="left" height="480" width="250"></a>
