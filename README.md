# Health-Insurance-Cross-Sell-Prediction
_ _ _
## **Project Summary :**
---

### An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee. For example, One may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if that person falls ill and needs to be hospitalised in that year, the insurance provider company will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalised that year and not everyone. This way everyone shares the risk of everyone else.
### Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.
### Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue. Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

## **Data Description :**
---

### **TRAIN-HEALTH INSURANCE CROSS SELL PREDICTION.csv ⇒** Contains the Historical data of the the Insurance company.

**1. id ⇒** Unique id of the customer.

**2. Gender ⇒** Gender of the customer.(male / female)

**3. Age ⇒** Age of the customer

**4. Driving License ⇒** Customer has the DL or not.

**5. Region_Code ⇒** Unique code for the region of the customer.

**6. Previously_insured ⇒** Customer already has vehicle insurance or not.

**7. Vehicle_Age ⇒** Age of the vehicle.

**8. Vehicle_damage ⇒** Past damages of the vehicle still present or not.

**9. Annual_premium ⇒** The amount of money the customer needs to pay as premium.

**10. PolicySalesChannel ⇒** Anonymized code for the channel of outreaching to the customer ie. Different Agents, Over mail, over phone, in person, etc.

**11. Vintage ⇒** Number of Days, Customer has been associated with the company.

**12. Response ⇒** Customer is interested in the Insurance or not.

