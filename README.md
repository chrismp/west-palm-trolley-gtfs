# west-palm-trolley-gtfs
Attempting to make GTFS for Downtown West Palm Beach trolley routes

# Sources
- [Downtown WPB trolley route maps and schedules: Green, Yellow and Blue lines](http://www.downtownwpb.com/trolley/)
- [Holiday schedule for Green, Yellow and Blue lines](http://www.downtownwpb.com/trolley-holiday-schedule/)
- [Orange line route and schedule](http://www.downtownwpb.com/blog/the-orange-line-trolley-your-free-ride-to-arts-culture-in-wpb/)

# Issues
- Not sure on what holidays the trolleys operate on holiday schedule.
- In `stops` file, these columns need review: `stop_name`, `stop_lat` and `stop_lon`.
- Not sure if Yellow and Green line info need to be added to `stop_times` file since I added info for those lines to `frequencies` file.
- Not sure what Orange line's holiday schedule is.
- Not sure what are the the best color codes to use for columns `route_color` and `route_text_color` in file `routes`.
- Review all files, but especially check these:
-- Need to review `calendar_dates`.
-- Need to review `calendar`.
