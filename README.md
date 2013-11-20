# Coffee Machine Project
====================

An exploration of design pattern implementations in various languages.

## Problem
You were approached by Phillip, the design coordinator from MyOwn Industries, a local manufacturer of household electronic appliances. The MyOwn product line has been available for a while, and is known for its superior quality and style. In your discussions with Phillip, he mentioned that MyOwn is partnering with an international coffee bean producer, and do not currently have an automatic beverage machine on the market. This diversification initiative will potentially allow MyOwn to cross its own boundaries into the corporate market, and the development of the MyOwn coffee machine is the first step.
Before manufacturing of the beverage machine can start, Phillip needs to propose a stable and scalable design to his executive, and he needs your help with the conceptual design of the product.
The requirements are as follows:
Water use:
The machine will have only two water inlets, located at the back of the machine that can be connected to a warm and cold water faucet. This will provide warm and cold water to the whole system when required. This is the only source of water, and when connected, cannot be used by anyone else. The flow of water should be controlled by the machine, dependent on two scenarios: When drinking water is dispensed by the machine, the flow should be high, but when water is used to maintain the level of the reservoir, the flow should be low. Drinking water will not be dispensed out of the reservoir, but with a direct flow from the cold water faucet. To allow water to be heated up quickly, the reservoir will be filled by the warm water faucet.
Products:
The machine must allow for the preconfiguring of beverages, where one button can be pressed, and the beverage is prepared based on the configuration, like a cup of coffee with two sugar and milk or a cup of coffee with sweetener and powdered milk. The machine should also allow the user to specify his or her own configuration, by pressing the control buttons on the device. 
Preconfigured beverages can be the standard base type beverages, coffee, tea, hot chocolate, etc., and exotic beverages, that are based on standard beverages, like Espresso, Frappuccino, latte, etc. A menu with beverages are provided as part of the requirement.

### Menu:
Standard Products:
Coffee (Light, Medium, Full roast, Double Roast), Sugar (sweetener, sugar, none), 20% Milk (Powdered, Low Fat, Fat Free, Full cream, none), 75% (+20% when no milk or powdered) Water (Boiled)
Tea (Rooibos, Black, Green, Chai), Sugar (sweetener, sugar, none), Milk (Powdered, Low Fat, Fat Free, Full cream, none), 75% (+20% when no milk or powdered) Water (Boiled)
Hot chocolate (Sweet, Semi-sweet, Dark, White), Sugar (sweetener, sugar, none), 75% (warm) Milk (Low Fat, Fat Free, Full cream, none), 75% Water (Boiled)
Espresso (Full roast, Double Roast, red espresso), Sugar (none), Milk (None), 25% Water (Boiled)

### Exotic products:
Frappuccino (base: Espresso (Full roast, Double Roast)), Sugar (sugar), 50% (cold) Milk (Low Fat, Fat Free, Full cream), Syrup (Almond), Syrup (Caramel, Mocha), 25% Water (Crushed ice), Whipped cream
Cappuccino (base: Espresso (Full roast, Double Roast)), Sugar (sugar), 50% (warm) Milk (Low Fat, Fat Free, Full cream), 25% Water (Boiled)
Red Cappuccino (base: Espresso (red espresso)), Sugar (honey), 50% (warm) Milk (Low Fat, Fat Free, Full cream), 25% Water (Boiled), Syrup (Almond), with a pinch of cinnamon

Cappuccino: This coffee product includes equal parts steamed and frothed milk and shot of coffee. The milk then gets poured on top of the coffee shot and dusted with nutmeg, cinnamon or chocolate powder. 

Café Mochas: The simplest way to do this is to make it with quality hot chocolate, include a shot of coffee with steamed milk poured in and top with whipped cream, then lightly dust with chocolate powder. To realize the best effect, employ a clear glass-mug with a long stemmed spoon. 

Lattes: Foam and steam milk to 75 degrees (C). The ratio is worked out as 50% coffee and 50% milk. Slowly pour the milk down the side of the coffee cup or glass so it infuses with the coffee shot. The main differentiation between a latte and a cappuccino is a latte blends the milk and coffee together, whereas the cappuccino keeps the two apart. 

Espressos: We have all had a foul espresso, right? There are lots of reasons for this. The No.1 reason being an unfavourable coffee bean being utilized. If you like espressos you are most likely a lover of all things coffee and understand what makes a good coffee bean. So with this in mind, to make a good espresso coffee you should follow these instructions: 

• Finely grind the coffee beans 
• You must pack the espresso down firmly 
• You must employ a high pressure coffee maker or stove top model 
• You must not try to make too much coffee at once 
• You need to see the crème floating on the top of the coffee shot, which is a golden-brown foam 
• You need to use an appropriate espresso cup to keep the coffee warm
