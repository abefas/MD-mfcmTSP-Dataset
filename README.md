i01-i11 are modified (coordinates x50) MDVRP instances p01-p11 to make them realistic for our problem's scenario.

i12-i16 are new randomly generated instances for 500 and 1000 customers.



.MDmfcmTSP file format:

num_customers num_depots num_vehicle_types

cap_Truck cap_Motorbike cap_Drone

/* Customer nodes */
node_ID coord_x coord_y customer_demand customer_accessibility (1=Truck 2=Motorbike 3=Drone)

/* Depot nodes */
node_ID coord_x coord_y num_Trucks num_Motorbikes num_Drones