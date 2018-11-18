JSON
```
{
    "standardVersion": "v1",
    "name": "The name of the modpack (string, required)",
    "author": "(string, required)",
    "sourceUrl": "The homepage of the modpack (string, optional, d:null)",
    "helpUrl": "The URL for the modpack's support page (string, optional, d:null)",
    "targetGame": "The targeted game install ("skyrim"/"fallout4"/, required),
    "description": "Modpack description (string, optional, d:null)",
    "installModOrganizer": "Instructs the installer to bundle a MO instance with the Modpack install automatically (bool, optional d:true),
    "modOrganizerVersion": "Targets a specific modpack version relative to values set by installModOrganizer and targetGame (bool, optional, d:null),
    "registeredFiles": "Targets bundled configuration files by filename (string, optional, d:null),
    "registeredModDirectories": "Targets sub-directories containing mod configuration files. All directories must be registered before they can be configured. (string, required)
}
