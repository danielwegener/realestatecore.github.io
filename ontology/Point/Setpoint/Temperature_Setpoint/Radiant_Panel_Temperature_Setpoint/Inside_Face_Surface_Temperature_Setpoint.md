[Index](../../../../Index.md) > [Point](../../../Point.md) > [Setpoint](../../Setpoint.md) > [Temperature_Setpoint](../Temperature_Setpoint.md) > [Radiant_Panel_Temperature_Setpoint](Radiant_Panel_Temperature_Setpoint.md) > [Inside_Face_Surface_Temperature_Setpoint](#)
# Inside_Face_Surface_Temperature_Setpoint

**Display name:** Inside Face Surface Temperature Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Inside_Face_Surface_Temperature_Setpoint;1

---

## Relationships

### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Point](../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint