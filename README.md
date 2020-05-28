# Dataset Background

### What exactly are these knives?
#### These knives are cosmetic items players can get in the game Counter Strike: Global Offensive (CS:GO) by unboxing crates which are won when players win matches (and open them with keys for a price). They are purely cosmetic in nature and offer no in-game benefit, yet some have unique designs and are mostly used as items to show off to other players. Some knives go for over $1000. 

### How is this data extracted?

#### The dataset is extracted through a Python web scraper; the web scraper goes to the Steam Marketplace (where these knives are sold) and extracts information about each knife, including:

#### 1.   Knife Type (i.e. Karambit, Bayonet)
#### 2.   Knife Skin (i.e. Tiger Tooth, Case Hardened)
#### 3.   Knife Skin Quality (i.e. Battle-Scarred, Factory New)
#### 4.   StatTrak (the ability for the knife to track kills)
#### 5.   Price (USD) (technically, the *minimum* price to buy the knife on the Marketplace)
#### 6.   Quantity (the number of knives of a given type on the Marketplace)

#### The dataset is not complete, however, as some skins are only available on certain knives and some players just aren't selling certain types of knives on the Marketplace at the time the dataset was compiled.

### How do I get this set up?
#### Run the file (Runtime -> Restart and run all) and, under "Getting Set Up", click "Choose Files" and upload the database. It should be in .db format as output from the web scraper file. Once that is uploaded, check the plots below! If you are interested in how data was manipulated/accessed, check the hidden cells for the Python code written.
