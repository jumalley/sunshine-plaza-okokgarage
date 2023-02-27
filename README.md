# sunshine-plaza-okokgarage

	{
		name = "Sunshine Plaza Legion Square", -- Garage name shown in the menu
		coords = vector3(217.35650634766, -955.12957763672, 29.459800720215), -- Marker position
		blip = { blipId = 524, blipColor = 3, blipScale = 0.9, blipText = "Garage" }, -- Blip informations
		marker = { id = 36, color = { r = 31, g = 94, b = 255, a = 90 }, size = { x = 0.7, y = 0.7, z = 0.7 }, bobUpAndDown = 0, faceCamera = 0, rotate = 1, drawOnEnts = 0 }, -- Marker informations
		radius = 1, -- Interaction radius for the marker
		storeVehicleCoords = vector3(203.4733581543, -951.27783203125, 29.378944396973),
		storeVehicleMarker = {id = 36, color = { r = 255, g = 0, b = 0, a = 90 }, size = { x = 0.7, y = 0.7, z = 0.7 }, radius = 2.5, bobUpAndDown = 0, faceCamera = 0, rotate = 1, drawOnEnts = 0}, -- Marker informations for the sell vehicle marker
		viewVehicleCoords = vector4(210.91149902344, -954.13000488281, 29.375202178955, 248.44354248047),
		vehicleSpawn = { -- Where the vehicle spawns when you take it out
			vector4(217.85470581055, -939.66668701172, 28.947975158691, 68.636215209961), -- Make it work with multiple spawn points
			vector4(208.90132141113, -963.72436523438, 28.954494476318, 69.384490966797),
			vector4(205.09373474121, -975.67919921875, 28.937871932983, 72.032279968262),
			vector4(202.26208496094, -981.15411376953, 28.936695098877, 72.066650390625),
		},
		infiniteVehicles = false, -- This will work for societies only, set the society vehicles in the Config.SocietyVehiclesList
		id = "plazalegion", -- ID of the garage, it's used to get what garage is opened | needs to be DIFFERENT for each garage
		society = "", -- Leave blank if not in use
		type = "car" -- car, air or boat
	},
