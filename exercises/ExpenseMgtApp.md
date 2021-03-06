# Requirements
1. An expense report consists of multiple line items
1. For each expense report, the following need to be tracked:
    1. Date submitted
    1. Purpose of the trip
    1. Status of the report: New, Complete, Submitted, Approved, Not Approved
    1. Department of the expense report owner
1. Users should only be able to choose an expense report status of New or Complete
1. Three types of expenses must be captured:
    1. Transporatation:
        1. Type of Transportation
            1. Airline: United, Delta, British Airways, KLM
            1. Taxi: Uber, Lyft, Yellow Cab, Other
            1. Rental Car: Avis, Budget, Hertz
        1. Amount
        1. Comments
    1. Accomodation
        1. Vendor
        1. Number of Nights
        1. Nightly Rate
        1. Amount
        1. Comments
    1. Food
        1. Meal Type: Breakfast, Lunch, Dinner
        1. Amount
        1. Business Guest
        1. Comments    
1. Each expense line item should only show fields relevant to the type
1. The following calculations need to be performed:
    1. Total Transportation Expenses
    1. Total Accomodation Expenses
    1. Total Food Expenses
1. Once an expense report is complete it should be automatically submitted for approval         
