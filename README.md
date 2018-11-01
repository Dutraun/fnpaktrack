### tracking fortnite pak changes

.uexp files are concatenated to .uasset files and are then serialized
currently stored is:
* name table
* import table
* export table
* serialized property tags for exports

these property tags are serialized to the proper type:
* SoftObjectProperty
* TextProperty (only HistoryType 0 is shown properly)
* BoolProperty
* FloatProperty
* IntProperty  
other's are stored with an [xxHash](https://cyan4973.github.io/xxHash/)  
  
non-uasset/uexp/ubulk files are stored raw