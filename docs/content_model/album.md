## Album

Description:

* An album is a collection of photos

Attributes:

* Title
  * Total: 1
  * Required: true
  * Type: text input
  * Character limit: 127
  * Description: The title for this album
* Media
  * Total: multiple
  * Required: false
  * Type: reference (photo)
  * Description: The media that is part of this album
* Tags
  * Total: multiple
  * Required: false
  * Type: reference (term)
  * Description: Tags allow albums to be related to other albums and/or photos on a meta level

Relationships:

* Photo
* Term