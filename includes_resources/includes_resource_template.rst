.. The contents of this file may be included in multiple topics (using the includes directive).
.. The contents of this file should be modified in a way that preserves its ability to appear in multiple topics.

Use the |resource template| resource to manage the contents of a file using an |erb| template by transferring files from a sub-directory of ``COOKBOOK_NAME/templates/`` to a specified path located on a host that is running the |chef client|. This resource includes actions and properties from the |resource file| resource. Template files managed by the |resource template| resource follow the same file specificity rules as the |resource remote_file| and |resource file| resources. 
