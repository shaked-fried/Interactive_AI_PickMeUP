# Coordination system for carpooling
You will need to install osmnx and radar api extensions to run the code
important notes:
    1. The radar geofence object should be created each time with a new id, the relevant line is marked in the code
    2. The radar conversion of address to ccordinated and vice versa sometimes gets innacurate results/ wrong results perhaps due to the fact that the data it has about Haifa isn't accurate enough.

If you want another example for th algorithm you should try:

driver - Hankin Rd
passenger - Sderot David Rose, Haifa
destination - Natanzon, Haifa

driver - Pinsker st, Haifa
passenger - Sderot David Rose, Haifa
destination - Natanzon, Haifa
