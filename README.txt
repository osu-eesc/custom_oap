Helper module for EESC maintained sites.

- Defines miscellaneous javascript functions
- Adds template overrides
- Adds Display Suite layouts
- Defines custom sort order for magazine article listings




Homepage Story Order:
------------------------------
    editor's note
    map (OAP article CCK)
    timeline (OAP article CCK)
    stories

< horizontal rule – to separate the lower items. See topics page for color. >

    profile
    updates
    depth of field (this is last because this is a different CCK. If it was between profile and update we'd have to change it's CCK to give it a lot of extra fields it doesn't need. And we don't have it under the cover img, because in mobile views this would show up after the cover.)


Notes: The order for the specified items (Editor's Note, Profile, and Update) is controlled in the custom_oap module. Everything else still defaults to the book weight, and Depth of Field remains as its own view.

These are all the possible section headers: 
	Update
	Profile
	Editor's Note
	Looking Ahead
	Depth of Field
	Those Who Feed Us
	Food for Thought Curriculum
