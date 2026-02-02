# cloudBIM API

For a cloudBIM to be interactive, an accessible API is required. The RE1 sample in the cloud can be accessed through the [ONUMA API](https://onuma.com/api.html).

## RE1 sample BIM API access

Various endpoints with specifically passed fields and filters will return simple geometry information and asset data which can be used in a third party application like the [CMMS](https://bim-genie.com/RE1.html), [PADI](https://padi.io), [Dabblefox](https://dabblefox.com/custodian), and others or directly turned into a plan and asset data App like the [RE1 API Request Visualization](https://www.onuma.com/RE1-onuma_api/floor_plan.html).

### API Endpoints:

* **Floors:**
	* https://system.onuma.com/177/api/items/building/3546?fields=floors.slabs.placement_x,floors.slabs.placement_y,floors.slabs.placement_angle,floors.slabs.profile
	* Response: [RE1-floors.json](docs/RE1-floors.json)
* **Spaces/Rooms:**
	* https://system.onuma.com/177/api/items/space?fields=id,number,name,area,profile,placement_x,placement_y,placement_angle&filter[floor.building]=3546
	* Response: [RE1-spaces.json](docs/RE1-spaces.json)
* Assets/Components:
	* **Assets Space RE-3:** https://system.onuma.com/177/api/items/space/339943?fields=id,number,name,components.component.instance_name,components.component.id,components.component.placement_x,components.component.placement_y,components.component.placement_angle,components.component.mirror_y,components.component.dimension_x,components.component.dimension_y,components.component.attributes
	* Response RE-3: [RE-3_components.json](docs/RE-3_components.json)
	* **Assets Space RE-5:** replace space id with space/339947
	* Response RE-5: [RE-5_components.json](RE-5_components.json)

## Visualization

This [Plan Visualization App](https://www.onuma.com/RE1-onuma_api/floor_plan.html) created with javascript for demonstration purposes shows how easily an App can use the response data from the cloudBIM API above.