user stories (`As a user ...`)
(CRUD ACTIONS BELOW)
-view all parks
    -return all parks upon page load
    -commit when this works
-view single park 
    -query for a single park -by ID? (can i use use park name)
    -return the correct park we query for
    -commit when this works
-view all my parks
    -query all parks in collection ()find
    -return all parks
    -commit when this works
-view one of my parks
    -query for a single park -by ID? (can i use use park name)
    -return the correct park we query for
    -commit when this works
-create a park
    -new schema
    -create model to use 
    -return newly created park
    -commit when this works
-update single park inside of my parks
    -query for a single park -by ID?
    -update that single park 
    -return updated park
    -commit when this works
-delete single park
    -query for a single park -by ID?
    -delete or remove a park only from myparks 
    -return proof of success of somehow 
    -commit when this works
-be able to add times visited to a park 
    -default value of some kind (start a zero... like zero likes )
    -query for a single park -by ID?
    -update liked field 
    -return that updated document 
    -commit when this works
-be able to add comments to single parks
    -search for single park 

    Schema: (model)
        -park
            -city - string
            -state - string
            -postal code - number
            -entrance fee - boolean
            -description - string

        -comment
            note:
                type: string
                required: true
            autor:
                type
                ref



