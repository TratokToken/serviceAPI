# serviceAPI
API demo for service providers to manage inventory, booking and prices.  
This documentation is mean't for those who are not integrated with a supported GDS but who wish to integrate Tratok directly into their backend systems.

Approved service providers can generate their own documentation and secret key through their property management interface. Current methods supported include:

getRoomStatus: Responds with whether the room is activated or deactivated.

getPriceOnDate: Responds with the price for a chosen room on a chosen date.

getPriceForRange: Reponds with the prices for a chosen room over a chosen period.

updatePrice: Updates the price for a chosen room on a chosen date.

updatePriceOverPeriod: Bulk updates the price for a chosen room over a chosen period.

activateRoom: Sets a particular room to active.

deactivateRoom: Sets a particular room to inactive.

getRoomInformationOnDate: Displays comprehensive room information on a chosen date.

getRoomInformationForRange: Displays comprehensive room information over a chosen period.

getBookedRoomsOnDate: Displays booked room inventory on a chosen date.

getBookedRoomsForRange: Displays booked room inventory over a chosen period.

getUnbookedRoomsOnDate: Displays unbooked room inventory on a chosen date.

getUnbookedRoomsForRange: Displays unbooked inventory over a chosen period.

getRoomInventoryOnDate: Displays room inventory on a chosen date.

getRoomInventoryForRange: Displays room inventory over a chosen period.

updateInventoryOnDate: Updates room inventory on a chosen date.

updateInventoryForRange: Updates room inventory over a chosen period.

displayHotelBookings: Displays comprehensive booking information for the entire hotel.
