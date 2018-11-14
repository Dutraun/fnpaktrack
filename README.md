### tracking fortnite pak changes

.uexp files are concatenated to .uasset (or .umap) files and are then serialized
currently stored is:
* name table
* import table
* serialized information for exports with some other information

these property tag types are explicitly supported:
* SoftObjectProperty
* some ObjectProperty's
* TextProperty (only HistoryType 0 is shown properly)
* BoolProperty
* FloatProperty
* EnumProperty
* NameProperty
* StrProperty
* some ByteProperty's
* ArrayProperty's of type NameProperty, or FloatProperty with support for _some_ StructProperty's (listed below)
* some StructProperty's (also listed below)
* IntProperty  

supported StructProperty types:
* FFortMcpQuestObjectiveInfo (arrays too)
* FortItemQuantityPair (arrays too)
* Vector
* Vector2D
* Rotator
* Guid
* GameplayTagContainer  
  
non-uasset/uexp/ubulk/umap files are stored raw (excluding ushaderbytecode)
