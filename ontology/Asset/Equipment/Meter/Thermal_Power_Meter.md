[Index](../../../Index.md) > [Asset](../../Asset.md) > [Equipment](../Equipment.md) > [Meter](Meter.md) > [Thermal_Power_Meter](#)
# Thermal_Power_Meter

**Display name:** Thermal Power Meter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Thermal_Power_Meter;1

---

## Relationships

### Inherited Relationships
* **[Meter](Meter.md):** hasSubMeter, isSubMeterOf
* **[Equipment](../Equipment.md):** feeds, isFedBy
* **[Asset](../../Asset.md):** commissionedBy, documentation, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Meter](Meter.md):** isMeteredBy, isVirtualMeter, meters
* **[Equipment](../Equipment.md):** operationalStageCount
* **[Asset](../../Asset.md):** assetTag, commissioningDate, customTags, externalIds, geometry, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### Inherited
* [Asset](../../Asset.md).hasPart
* [Asset](../../Asset.md).isPartOf
* [EquipmentCollection](../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).includes
* [Meter](Meter.md).hasSubMeter
* [Meter](Meter.md).isSubMeterOf