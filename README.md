# Motor-Part-Shop-Software

## Description
The small automobile spare parts shop sells the spare parts for a vehicles of several makes and models. Also, each spare part is typically manufactured by several small industries. To stream line the sales and supply ordering, the shop owner has asked us to develop the following motor part shop software. The motor parts shop deals with large number of motor parts of various
manufacturers and various vehicle types. Some of the motor parts are very small and some are of reasonably large size. The shop ownermaintains different parts in wall mounted and numbered racks.
The shop owner maintains as few inventory for each item as reasonable,
to reduce inventory overheads after being inspired by the just-in-time
(JIT) philosophy.

## Modules 
MotorPartShopSoftware - Parent class which is executed to start the application
LoginPage - Provides an username textfield and a password textfield. Shows an error notiff on wrong credentials.
WelcomePage - The page where the allowalble functions are present for different userClasses
AddDetails - User can add a new motorPart into the inventory through this function, needs to enter relevant details of the part.
Billing - Handles the billing process when a part is sold from the shop.
CheckStock - Gives a list of MotorParts present in the shop with quantity and ID of each.
RequiredStock - Gives a list of MotorParts that need to be restocked after comparing current stock and average sales from previous week.
SalesStatistics - Gives the total revenue of the day and the list of MotorParts sold in the current day.
UpdateStock - Allows to restock an existing MotorPart into the inventory by taking in the ID and the quantity added.
