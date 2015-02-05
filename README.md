# CF10-CertMan

An extension for ColdFusion 10 Administrator that allows adding/viewing/removing of SSL certificates in the Java certificate store from within the Administrator.

This works with ColdFusion 10. For a CF7, 8 & 9 version please check out [CF-Certman](https://github.com/coldfumonkeh/CF-Certman).


## Installation

Extract the contents of this repository into a CFIDE/administrator/certman/ directory.

Edit the CFIDE\administrator\custommenu.xml file to add the following submenu xml key:-

    <submenu label="SSL Certificates">
      <menuitem href="certman" target="content">Certificate Management</menuitem>
    </submenu>

### Notes

The CertMan project was originally developed by Paul Connell.

This is a fresh fork taken to separate the specific ColdFusion versions for easier use.
