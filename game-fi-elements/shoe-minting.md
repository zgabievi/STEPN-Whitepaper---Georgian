# ფეხსაცმლის დამინთვა

### Shoe-Minting

Shoe-Minting Event (SME) is when users use 2 Sneakers they own as a blueprint to “breed”, producing a Shoebox in the process. For reference, the 2 Sneakers will be called Vintages (Parents). Both Vintages need to be in the user’s possession (not under lease) and have full durability to begin an SME.

Users can then select a Sneaker, by heading to the **Mint** tab, choosing the Sneaker to “breed” with, and pressing **Mint** to proceed. The user will instantly receive a Shoebox that can be opened immediately.

Users can perform a maximum of 7 SMEs per Sneaker. The higher SME count a Sneaker has, the more GST/GMT it will cost. Shoe-Minting costs for each Vintage is calculated separately and added together for the final Minting cost.

Shoe-Minting has a 48-hour cool down for both Vintages – Sneakers can still be used for movement.

### Shoe-Minting Costs

The price of GST will dictate the amount of GST and subsequently the amount of GMT needed for minting. See below:

e.g. Common M0/7 x Common M0/7. When price of price of GMT < GST:

1\.    If GST < $2, Minting cost is 200 (200 GST);

2\.    If $2 < GST < $3, Minting costs is 200 (160 GST & 40 GMT);

3\.    If $3 < GST < $4, Minting costs is 200 (120 GST & 80 GMT);

4\.    If $4 < GST < $8, Minting costs is 200 (100 GST & 100 GMT);

5\.    If $8 < GST < $10, Minting costs is 200 (80 GST & 120 GMT);

6\.    If GST > $10, Minting costs is 200 (40 GST & 160 GMT).

When price of GMT > GST, we will implement additional rule to regulate the minting cost, such as reduce the amount of GMT needed (which makes Minting cost less than 200). For different chains (BNBChain and Solana Chain) with different GST prices, the Shoe-Minting cost breakdown may differ.

**NOTE: Shoe-Minting cost will update daily on UTC 14:00.**

The first two Shoe-Minting costs the same. Shoe-Minting has a chance to drop one extra Shoebox. The higher the Mint count, the higher the chance to drop multiple Shoeboxes.

The cost of Shoe-minting will be changed from time to time to balance the supply and demand of both GST and GMT.

Shoebox Quality is determined by the Vintage Sneaker's Quality:

| **Vintage 1 Quality** | **Vintage 2 Quality** | **Common Shoebox %** | **Uncommon Shoebox %** | **Rare Shoebox %** | **Epic Shoebox %** | **Legendary Shoebox %** |
| --------------------- | --------------------- | -------------------- | ---------------------- | ------------------ | ------------------ | ----------------------- |
| Common                | Common                | 100                  | 0                      | 0                  | 0                  | 0                       |
| Common                | Uncommon              | 50                   | 49                     | 1                  | 0                  | 0                       |
| Common                | Rare                  | 50                   | 0                      | 49                 | 1                  | 0                       |
| Common                | Epic                  | 50                   | 0                      | 0                  | 49                 | 1                       |
| Common                | Legendary             | 50                   | 0                      | 0                  | 0                  | 50                      |
| Uncommon              | Uncommon              | 0                    | 98                     | 2                  | 0                  | 0                       |
| Uncommon              | Rare                  | 0                    | 49                     | 50                 | 1                  | 0                       |
| Uncommon              | Epic                  | 0                    | 49                     | 1                  | 49                 | 1                       |
| Uncommon              | Legendary             | 0                    | 49                     | 1                  | 0                  | 50                      |
| Rare                  | Rare                  | 0                    | 0                      | 98                 | 2                  | 0                       |
| Rare                  | Epic                  | 0                    | 0                      | 49                 | 50                 | 1                       |
| Rare                  | Legendary             | 0                    | 0                      | 49                 | 1                  | 50                      |
| Epic                  | Epic                  | 0                    | 0                      | 0                  | 98                 | 2                       |
| Epic                  | Legendary             | 0                    | 0                      | 0                  | 49                 | 51                      |
| Legendary             | Legendary             | 0                    | 0                      | 0                  | 0                  | 100                     |

Users will get a new Sneaker once they open the Shoebox, with the Sneaker Quality determined by the Shoebox Quality:

| **Shoebox Quality** | **Common Sneaker %** | **Uncommon Sneaker %** | **Rare Sneaker %** | **Epic Sneaker %** | **Legendary Sneaker %** |
| ------------------- | -------------------- | ---------------------- | ------------------ | ------------------ | ----------------------- |
| **Common**          | 97                   | 3                      | 0                  | 0                  | 0                       |
| **Uncommon**        | 25                   | 73                     | 2                  | 0                  | 0                       |
| **Rare**            | 0                    | 27                     | 71                 | 2                  | 0                       |
| **Epic**            | 0                    | 0                      | 30                 | 68                 | 2                       |
| **Legendary**       | 0                    | 0                      | 0                  | 35                 | 65                      |

**Note: Legendary Sneaker drop is disabled at the moment.**

The new Sneaker type is determined by the two Vintage Sneaker types:

| **Vintage 1 Type** | **Vintage 2 Type** | **Walker %** | **Jogger %** | **Runner %** | **Trainer %** |
| ------------------ | ------------------ | ------------ | ------------ | ------------ | ------------- |
| Walker             | Walker             | 85           | 6            | 6            | 3             |
| Walker             | Jogger             | 45           | 45           | 7            | 3             |
| Walker             | Runner             | 45           | 7            | 45           | 3             |
| Walker             | Trainer            | 80           | 6            | 6            | 8             |
| Jogger             | Jogger             | 6            | 85           | 6            | 3             |
| Jogger             | Runner             | 7            | 45           | 45           | 3             |
| Jogger             | Trainer            | 6            | 80           | 6            | 8             |
| Runner             | Runner             | 6            | 6            | 85           | 3             |
| Runner             | Trainer            | 6            | 6            | 80           | 8             |
| Trainer            | Trainer            | 25           | 25           | 25           | 25            |

The new Sneaker's Socket type is determined by two Vintage Sneakers' Socket types:

| **Vintage 1**     | **Vintage 2**     | **Efficiency Socket %** | **Luck Socket %** | **Comfort Socket %** | **Durability Socket %** |
| ----------------- | ----------------- | ----------------------- | ----------------- | -------------------- | ----------------------- |
| Efficiency Socket | Efficiency Socket | 85                      | 5                 | 5                    | 5                       |
| Efficiency Socket | Luck Socket       | 45                      | 45                | 5                    | 5                       |
| Efficiency Socket | Comfort Socket    | 45                      | 5                 | 45                   | 5                       |
| Efficiency Socket | Durability Socket | 45                      | 5                 | 5                    | 45                      |
| Luck Socket       | Luck Socket       | 5                       | 85                | 5                    | 5                       |
| Luck Socket       | Comfort Socket    | 5                       | 45                | 45                   | 5                       |
| Luck Socket       | Durability Socket | 5                       | 45                | 5                    | 45                      |
| Comfort Socket    | Comfort Socket    | 5                       | 5                 | 85                   | 5                       |
| Comfort Socket    | Durability Socket | 5                       | 5                 | 45                   | 45                      |
| Durability Socket | Durability Socket | 5                       | 5                 | 5                    | 85                      |

### Shoe-Minting Variation

Sneaker Attributes are randomized according to their quality, regardless of their Vintage’s Attributes.



### Minting Scroll (coming soon)

Minting requires 2 Minting Scrolls and 2 parent Sneakers. The Minting Scrolls need to match the parents' Sneaker quality. Minting Scrolls are permanently burned after minting
