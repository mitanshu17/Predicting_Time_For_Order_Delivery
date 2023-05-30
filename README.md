# Predicting the Time Taken for a Delivery
## Given a Training Dataset that contains the detials of the order and time taken to complete the delivery.
### PERFORMANCE OF MODELS:

![image](https://github.com/mitanshu17/Predicting-the-time-taken-to-complete-a-delivery/assets/118126264/c43b49db-845e-4cfd-bc90-6cf92bf85d01)
![image](https://github.com/mitanshu17/Predicting-the-time-taken-to-complete-a-delivery/assets/118126264/79076cba-9514-47d7-9d90-051811f4f6d4)

### COLUMN DESCRIPTION: (23 Features and 1 Label Column)

* `UID` : Unique IDentifier used to identify each unique sample in the dataset
* `trip_creation_time` : Timestamp of trip creation
* `route_schedule_uuid` : Unique Id for a particular route schedule
* `route_type` – Transportation type <br>
 * `FTL – Full Truck Load` : FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way <br>
 * `Carting`: Handling system consisting of small vehicles (carts) <br>
* `trip_uuid` : Unique ID given to a particular trip (A trip may include different source and destination centers)
* `source_center` : Source ID of trip origin
* `source_name` : Source Name of trip origin
* `destination_cente` : Destination ID
* `destination_name` : Destination Name
* `od_start_time`: Trip start time
* `od_end_time` : Trip end time
* `start_scan_to_end_scan` : Time taken to deliver from source to destination
* `is_cutoff` : Unknown field
* `cutoff_factor` : Unknown field
* `cutoff_timestamp` : Unknown field
* `actual_distance_to_destination` : Distance in Kms between source and destination warehouse
* `osrm_time` : An open-source routing engine time calculator which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) and gives the time (Cumulative)
* `osrm_distance` : An open-source routing engine which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) (Cumulative)
* `factor` : Unknown field
* `segment_actual_time` : This is a segment time. Time taken by the subset of the package delivery
* `segment_osrm_time` : This is the OSRM segment time. Time taken by the subset of the package delivery
* `segment_osrm_distance` : This is the OSRM distance. Distance covered by subset of the package delivery
* `segment_factor` : Unknown field
* `actual_time` : Actual time taken to complete the delivery (Cumulative)
