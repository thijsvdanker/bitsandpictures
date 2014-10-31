## Photo

Description:
* A photo with all it's meta data (exif)

Attributes:

* Title
  * Total: 1
  * Required: true
  * Type: text input
  * Character limit: 127
  * Description: The title for this photo
* File
  * Total: 1
  * Required: true
  * Type: reference (file)
  * Description: The actual file for this photo
* Exif
  * Dimensions
  	* Width
  	* Height
  * ISO
  * GPS
    * GPSLatitude
    * GPSLatitudeRef
    * GPSLongitude
    * GPSLongitudeRef
* Tags
  * Total: multiple
  * Required: false
  * Type: reference (term)
  * Description: Tags allows photos to be related to each other in a meta sense
* Persons
  * Total: multiple
  * Required: false
  * Type: reference (person)
  * Description: The persons that are tagged to be on this photo
* Description
  * Total: 1
  * Required: false
  * Type: text input
  * Character limit: false
  * Description: The story of whats going on in the photo

Relationships:

* File
* Taxonomy
* Person

  