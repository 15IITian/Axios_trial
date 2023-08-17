# Multivaraite_Analysis
## ( Apartment -> * Some are very expensive than villa, penthouse)
## (THere is some mistake in data values)

## * with 'Price' target-> 

### price - furnish_type ->
  * Overall price order -> un < semi < furnished
  * Outliers -> un , semi
  * ### Reason -> 

### price- area ->
 *  no such relation

## price- property_type ->
 * Price order -> Studio Apartment < Villa < Independent Floor < Independent House <  Apartment < Penthouse
  ## Reasons ->
  * Penthouse -> No outliers
  * Apartments -> most outliers with largest extreme values


______________________________________________________________________________________________________________________
# With area->
  * ## Property_type
        * Villa > Penthouse > Independent Floor > Independent House > Apartment > Studio Apartment (Overall)
        * Apartment , Independent House, have many outliers -> Some are even larger than Villa & Penthouse  
        * Independent House -> moderate outliers
        *  villa > Penthouse (Penthouse on top floor)
        * Without Outliers -> Apartment ~= Independent House
  * ## Furnish_type:
               * Un < (semi~= furnish)
             * No much special in outlier
  * ## Bathroom:
        * No of bathrooms(inc) -> area(inc);
        * In other category -> some are 'North west' etc -> similar to 1 bathroom -> effect avg 
  * ## seller_type:
         * Agent > Builder >= Owner
         * Most outliers in Agent 
  * ## Bedrooms ->
       * Area inc as no of bedrroms increase(General)
  * ## Layout_type:
            * BHK >> RK
            * Some BHK ones are very large 

# Layout_type:
 *  ## Relation bw layout && property type:
      * **RK-> Only  Studio Apartment** 
      * **BHK -> All except Studio Apartment** 

# Seller_type:
  
  *   ## Which type of seller sells which type of property
          * Penthouse-> only Agents
          * Villa -> not by builders
          * In all types (area) {agent > builder> owner} for each property_type 
          * Most  massive outliers  in AGENT && APARTMENT

  * ## Which seller sells which type of layout :
            * BHK selling prefence -> Agent(95%) > Builder > Owner
            * RK -> not much intrested (Owner > Builder > Agent)
            * As  BHK > RK(price)
  * ## Which seller sells which type of furnish_type (preference):
  
          *  Builder -> Unfurnished(82%)
          *  Agent -> Semi ~= un (35-40)
          *  Owner -> Semi ~= un()
          *  Fact about furnished -> It needs to provide all facilites -> low prefer
          *  Furnish ->  agent (23)> owner> builder
          *  Builder -> constructs flats ->  un

  * ## Which seller sells which type of furnish_type (preference):
  * 

  
            


  
