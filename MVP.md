# NextStop
## Destination Determination

Every wonder where you should go next?


The web app will store a list of destinations you want to visit, and select one for you.

### Most basic MVP
Add string to array stored in memory, select random index.

### How to make it better?
- Store on local memory
- Add backend… store entries on server
- Make Destination OBJ with more data to allow more intelligent random selection
    -  Ideal time of year to visit
        - What if its good for multiple times of year… but that affects other properties?  I.E good for family in summer, but couples in winter?  Would this have to be two separate entries?
    - Minimum-Maximum duration necessary.  (Doesn’t select Tahiti for a 3 day weekend)
    - Type of vacation (maybe boolean and ability to add custom types.  One objects
        - Family
        - Romantic
        - Couples
        - Guys Trip
        - Girls Trip
        - Close Friends
            - w/ family (instead of sub category, just set family to true)
            - w/o family
        - Big Group
            - w/ family (instead of sub category, just set family to true)
            - W/o family
    - Favorite
    - Priority
    - Visited vs Unvisited
    - Priority or Ranking system
- Share destinations with other Users or    Planners.  Could find destinations that meet criteria that match multiple users best.