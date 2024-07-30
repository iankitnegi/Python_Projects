# Portfolio Projects

### 1. AtliQ Hotels Data Analysis  
Datasets: 1. dim_date.csv, 2. dim_hotels.csv, 3. dim_rooms.csv, 4. fact_aggregated_bookings & 5. fact_bookings.csv
-  Data Import & Data Exploration:
    - Read bookings data in a dataframe
    - Explore bookings data
    - Read rest of the files
      - _Exercise-1. Find out unique property ids in aggregate bookings dataset_
      - _Exercise-2. Find out total bookings per property_id_
      - _Exercise-3. Find out days on which bookings are greater than capacity_
      - _Exercise-4. Find out properties that have highest capacity_
-  Data Cleaning:
    - Clean invalid guests
    - Outlier removal in revenue generated
      - _Exercise-1. In aggregate bookings find columns that have null values. Fill these null values with whatever you think is the appropriate subtitute (possible ways is to use mean or median)_
      - _Exercise-2. In aggregate bookings find out records that have successful_bookings value greater than capacity. Filter those records_
-  Data Transformation:
    - Create occupancy percentage column
    - Convert it to a percentage value
    - There are various types of data transformations that you may have to perform based on the need. Few examples of data transformations are Creating new columns, Normalization, Merging data & Aggregation
-  Insights Generation:
   - What is an average occupancy rate in each of the room categories?
   - Print average occupancy rate per city
   - When was the occupancy better? Weekday or Weekend?
   - In the month of June, what is the occupancy for different cities
   - We got new data for the month of august. Append that to existing data
   - Print revenue realized per city
   - Print month by month revenue
     - _Exercise-1. Print revenue realized per hotel type_
     - _Exercise-2 Print average rating per city_
     - _Exercise-3 Print a pie chart of revenue realized per booking platform_
