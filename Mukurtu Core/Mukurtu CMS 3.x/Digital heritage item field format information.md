guid
- GUIDs are 'Globally Unique Identifiers' and are used to uniquely identify content.
This is a single value, plain text field. The GUID is created by you and is useful for
situations where you do not know the internal ID of a piece of content. This field can
be nearly anything as long as it is unique to the content across the entire system.

nid
- NID stands for ‘Node ID’ and uniquely identifies a Node (e.g., Digital Heritage,
Dictionary Word) on a specific site . This field must only contain a single integer
value. Node IDs are not consistent between sites.

Title 
- A single value plain text field.

Book Pages
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid. Values must reference one of the following types: digital_heritage.

Book Parent
- A single value field. Values must be a valid GUID or node ID (nid). Values will be
used as GUIDs first. If no content is found with that GUID, the value will be used as
a nid. Values must reference one of the following types: digital_heritage.

Collections
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid. Values must reference one of the following types: collection.

Community Records
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid. Values must reference one of the following types: digital_heritage.

Community Record Parent
- A single value field. Values must be a valid GUID or node ID (nid). Values will be
used as GUIDs first. If no content is found with that GUID, the value will be used as
a nid. Values must reference one of the following types: digital_heritage.

Community
- A multi-value field (unlimited). Values must be either GUIDs or node IDs (nid).
Referenced nodes must be of type community.

Type
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Type' taxonomy. Values not found in that taxonomy will be auto-created.

Related Digital Heritage Items
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid.
- Note, this field should not be used in version 2.1.3 and above. Use Related Content
instead.

Summary
- A single value field. Values will be used as plain text of no more than 255 characters
each.

Transcription A single value field. Values will be used as plain text, and can be of any length.

Cultural Narrative
- A single value field. Values will be used as filtered text (e.g., Filtered HTML, Full
HTML, depending on importer), and can be of any length.

Category
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Category' taxonomy. Values not found in that taxonomy will be auto-created.

Contributor
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Contributor' taxonomy. Values not found in that taxonomy will be auto-created.

Location 
- A single value field. Values must be of type geofield.

Location Description
- A single value field. Values will be used as filtered text (e.g., Filtered HTML, Full
HTML, depending on importer), and can be of any length.

Creator
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Creator' taxonomy. Values not found in that taxonomy will be auto-created.

Original Date Description
- A single value field. Values will be used as plain text of no more than 255 characters
each.

Description
- A single value field. Values will be used as filtered text (e.g., Filtered HTML, Full
HTML, depending on importer), and can be of any length.

Format
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Format' taxonomy. Values not found in that taxonomy will be auto-created.

Identifier
- A single value field. Values will be used as plain text of no more than 255 characters
each.

Item Sharing Settings
- A single value field. Values must be one of:
 - any
 - all

Language
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Language' taxonomy. Values not found in that taxonomy will be auto-created.

Licensing Options
- A single value field. Values must be one of:
 - http://creativecommons.org/licenses/by/4.0
 - http://creativecommons.org/licenses/by-nc/4.0
 - http://creativecommons.org/licenses/by-sa/4.0
 - http://creativecommons.org/licenses/by-nc-sa/4.0
 - http://creativecommons.org/licenses/by-nd/4.0
 - http://creativecommons.org/licenses/by-nc-nd/4.0

Traditional Knowledge Labels
- A multi-value field (up to 4 values). Values must be one of:
 - http://localcontexts.org/tk/a/1.0
 - http://localcontexts.org/tk/s/1.0
 - http://localcontexts.org/tk/f/1.0
 - http://localcontexts.org/tk/o/1.0
 - http://localcontexts.org/tk/c/1.0
 - http://localcontexts.org/tk/nc/1.0
 - http://localcontexts.org/tk/mr/1.0
 - http://localcontexts.org/tk/mg/1.0
 - http://localcontexts.org/tk/mc/1.0
 - http://localcontexts.org/tk/wr/1.0
 - http://localcontexts.org/tk/wg/1.0
 - http://localcontexts.org/tk/ss/1.0
 - http://localcontexts.org/tk/co/1.0
 - http://localcontexts.org/tk/cv/1.0
 - http://localcontexts.org/tk/cs/1.0
 - http://localcontexts.org/tk/v/1.0
 - http://localcontexts.org/tk/nv/1.0

Media Assets
- A multi-value field (unlimited). Values must be either GUIDs or scald atom IDs (sid).

Publisher
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Publisher' taxonomy. Values not found in that taxonomy will be auto-created.

Rights 
- A single value field. Values will be used as plain text, and can be of any length.

Source
- A single value field. Values will be used as plain text of no more than 255 characters
each.

Subject
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Subject' taxonomy. Values not found in that taxonomy will be auto-created.

Keywords
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'Tags' taxonomy. Values not found in that taxonomy will be auto-created.

Traditional Knowledge
- A single value field. Values will be used as filtered text (e.g., Filtered HTML, Full
HTML, depending on importer), and can be of any length.

Protocol
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid.

People
- A multi-value field (unlimited). Values must be plain text taxonomy term names from
the 'People' taxonomy. Values not found in that taxonomy will be auto-created.

Related Dictionary Words
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid. Values must reference one of the following types: dictionary_word.
- Note, this field should not be used in version 2.1.3 and above. Use Related Content
instead.

Personal Collections
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid. Values must reference one of the following types: personal_collection.

Original Date 
- A single value field. Values must be dates formatted as YYYY-mm-dd.

External Links
- A multi-value field (unlimited). Values must be formatted as URL||Title||Attributes.

Related Content
- A multi-value field (unlimited). Values must be a valid GUID or node ID (nid). Values
will be used as GUIDs first. If no content is found with that GUID, the value will be
used as a nid. Values must reference one of the following types:
collection,dictionary_word,digital_heritage,person,word_list.

Username
- The single, plain text username of the user that should be the author of the imported
item.
