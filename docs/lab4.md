# Bob's Pool and Spa

> Bob's Pool and Spa is a regional pool and spa dealer offering sales, installation, parts and services.  In these labs you will using AI to help streamline the business.

## Real-time assist

> !!! code "Create a new Knowledge base named waterLab_yourName using this information"
    ```
        problem: colored water
        Solution:
        Colored Water (clear green/brown/yellow tint with no algae) has generally two causes – dissolved metals or a high organic content in the water. Follow these steps for sparkling clear water:
            Step 1. Sample of the water to your authorized Poolife™ dealer for a full analysis.
            Step 2. If metals are detected, add Poolife™ Intensive Stain Prevention™ product per label directions.
            Step 3. If a high organic content is suspected, shock the pool with Poolife™ TurboShock™ shock treatment or Poolife™ Rapid Shock™ shock treatment per label directions. Remember to wait until the free chlorine level has dropped to between 1-4 ppm before reentering the pool.


        problem: algae
        Solution:
        The addition of shock and algaecide on a regular basis will be more effective at preventing algae growth than treating algae once it is visible in a pool. However, if algae does appear, follow the steps below for treatment:
            Step 1. Adjust the pH to 7.2 – 7.4.
            Step 2. Brush the pool sides vigorously.
            Step 3. Shock the pool with Poolife™ TurboShock™ shock treatment or Poolife™ Rapid Shock™ shock treatment.
            Step 4. Add Poolife™ AlgaeBomb™ 30, Poolife™ Super AlgaeBomb™ 60, or Poolife™ Algaecide 90 according to label directions. Your authorized Poolife™ dealer can recommend which product is best for your pool.
            Step 5. Run the filter 24-48 hours, brushing and vacuuming frequently.
            Step 6. If algae remains a problem, contact your authorized Poolife™ dealer for further directions.
            NOTE: If you continue to experience algae, despite a high chlorine reading, the pool water may contain too much stabilizer (cyanuric acid) which interferes with the efficiency of the chlorine. Ensure you are following responsible pool care by shock-treating with a Poolife™ calcium hypochlorite-based shock product and contact your authorized Poolife™ dealer for further directions.


        problem: cloudy water
        Solution:
        There are many causes of cloudy water, the most common being incorrect pH, incorrect TA and improper filtration. Always check and adjust the pH and TA levels before adjusting your filtration system. Thereafter follow these steps to investigate your filtration system:
            Step 1. Make sure that the filtration system is running smoothly and that it is running at least 8-12 continuous hours daily.
            Step 2. Does the filter need to be backwashed?
            Step 3. If the filter pressure does not return to normal starting pressure after backwashing, the filter needs to be chemically cleaned.
            Step 4. Have the pump strainer baskets and the skimmer baskets been emptied?
            Step 5. Also test your water to make sure that the pH and total alkalinity are within the ideal range.
            Step 6. Shock the pool with Poolife™ TurboShock™ shock treatment or Poolife™ Rapid Shock™ shock treatment. Remember to wait until the chlorine level drops to between 1-4 ppm before re-entering the pool.
            NOTE: Poolife™ TurboBlu Clarifier™, Poolife™ Flocculant and Poolife™ Gold Medal Clarifier can also be used to clear cloudy water. Your authorized Poolife™ dealer can recommend which products are best for use in your pool.


        problem: eye and skin irritation
        Solution
        Often high levels of chlorine are blamed for eye and skin irritation or a strong chlorine odor. In fact the reason could be too little free available chlorine and an incorrect pH. Follow the recommendations below:
            Check pH and alkalinity levels and adjust as necessary.
            Shock the pool with Poolife™ TurboShock™ shock treatment or Poolife™ Rapid Shock™ shock treatment. Once you have done this, remember to recheck the pH and total alkalinity levels and readjust if necessary. Remember to always keep the chlorine levels between 1-4 ppm.
            Contact your authorized Poolife™ dealer for further directions.


        problem: scale deposits
        Solution:
        Scale deposits (usually in the form of white, gray or brownish chalky deposits on pool walls and fixtures) are the precipitate that forms as a result of unbalanced water. This could be a high pH, high TA, high calcium hardness and/or a combination thereof.
        Take a sample of your pool water to your authorized Poolife™ dealer for a full analysis. Balance your water according to your dealer’s recommendations. To avoid further scaling take a sample of the pool water to your Poolife™ dealer each month for a detailed analysis.
    ```
    
> Create an AI Assistant skill to help troubleshoot water issues.
>    
> Use the preview function to test the functionality
>>
> > Try phrases like: My pool is cloudy, My pool is making my skin itch, and/or  I have algae in my pool
>
> Adjust your goal and ant instructions until you are content with the results, then click publish
>
> (We will be incorporating this into flow later)
> 
> ---

## Autonomous AI Agent Knowledge
> Create A New Knowledge Base Named Bob's Pool and Spa_yourName
>
> !!! code "Add a new document named Hours of operation"
    ```
    Showroom:
    Monday: 9:00 AM - 9:00 PM
    Tuesday: 9:00 AM - 9:00 PM
    Wednesday: 9:00 AM - 5:00 PM
    Thursday: 9:00 AM - 9:00 PM
    Friday: 9:00 AM - 9:00 PM
    Saturday: 9:00 AM - 12:00 PM
    Sunday: closed

    Parts and Lab Services:
    Monday: 10:00 AM - 7:00 PM
    Tuesday: 10:00 AM - 7:00 PM
    Wednesday: 10:00 AM - 7:00 PM
    Thursday: 10:00 AM - 7:00 PM
    Friday: 10:00 AM - 7:00 PM
    Saturday: 12:00 PM - 5:00 PM
    Sunday: closed

    Installation and on-site:
    By appointment only
    ```
> !!! code "Add a new document named Promotions"
    ```
    February:

    - Free Spa cover with purchase

    - 25% off last years models 

    March:
    - 12 month same as cash financing available.
    - Free Site Inspections.
    ```
> !!! code "Add a new document named Filters"
    ```
    Pool & Spa Filter Cartridge 4-pk Replaces Pentair CCP320, PLFPCC80, Ultral-A5, Unicel C-7470, R173573, Filbur FC-1976, 178580, Clean and Clear Plus 320, 80 sq ft Pleated Fabric Filter Media 

    Price: 115.99

    Universal Compatibility: The CCP320 pool filtration system works seamlessly with major brand equivalents including PCC80, Uni cel C-7470, Pentair CCP320, Baleen AK-60433, Dar lly 70804, Excel Filters XLS-720, and certification codes SD-00162/SD-00065.

    Advanced Filtration Technology: Featuring proprietary tri-lobe fiber technology, our engineered filtration media expands the active surface area by 22%, stabilizing system pressure balance for sustained crystal-clear water output

    Cost-Effective Quad Pack: Package includes 4× CCP320 premium cartridges with exact specifications: Dimensions: 20.06" (509.5mm) length × 7" (177.8mm) OD Ports: 3" (76.2mm) universal inlet/outlet Capacity: 80 sq. ft per unit (320 sq. ft total) Media: Multi-layered tri-lobe fiber matrix with anti-clogging gradient design

    Low-Maintenance Operation: For optimal performance, execute biweekly maintenance cycles using pH-neutral cleaners. Critical protocol: Remove cartridges prior to chemical sanitization to prevent polymer degradation from concentrated disinfectants.

    Easy to Install & Maintain: Fits and performs just as well as the original equipment manufacturer product. It is recommended that you change your pool or spa filter when the pressure gauge on the filter tank reaches 8 psi above the pressure recorded when first installed.



    Baleen Filters Premium 27 Sq. Ft. Pool & Spa Filter | Replaces Unicel C-5627, Pleatco Ppm30, Filbur Fc-3070 | Efficient, Durable & USA-Made 

    Price 37.99

    SKU: NCC-173

        Precise Fit: Compatible with a 1 1/16" open hole top and 1 5/8" open hole bottom, ensuring compatibility with Marquis Spas and more.

        Superior Filtration: 27 sq. ft. media area made with premium USA-Made fabric for exceptional water clarity.

        Effortless Installation: Designed for an easy fit and compatible with Unicel C-5627, Pleatco PPM30, or Filbur FC-3070.

        Durable & Reusable: Washable filter media extends its lifespan, offering savings and reduced environmental impact.

        Optimized Engineering: Handles high pressures and temperatures, making it suitable for residential, commercial or industrial use, Exceeds OEM specifications, ensuring reliable and consistent performance.


    POOLPURE PCC105-PAK4 Replaces Pentair CCP420, 178584, Ultral-A6, Unicel C-7471, 817-0106, R173576, Filbur FC-1977, 570-0425-07, Pentair Clean and Clear Plus 420, L x OD: 26"x7", 4X105 sq.ft. Cartridge

    Price: 179.99

        Specifications: Length: 26"; Outside Diameter: 7"; Top Opening: 3"; Bottom Opening: 3"; Material Area: 105 Sq.ft; Filter Material: Trilobal Filtration Fabric.

        Compatible Models: PLF105A Pool Filter compatible Pentair CCP420, 160301, Waterway Crystal Water 425, 570-0425, SD-00163, AK-60431, Aladdin 20503, Filbur FC-6470. ★NOTE: This is a compatible spare part and the manufacturers' names and part numbers have been used for reference purposes only. POOLPURE is an independent brand.

        NSF/ANSI 50 Certified Safety: PoolPure pool and spa filter is tested and certified by IAPMO against NSF/ANSI 50 standards for material safety. All components are proven safe for long-term water exposure, ensuring no harmful substances are released. Protect your family’s health and enjoy cleaner, safer pool and spa water.

        Trilobal Filtration Fabric Design: The innovative trilobal fiber structure provides three times the adsorption surface area compared to conventional filter fabrics. It captures more dirt and sediment while maintaining consistent water clarity, even under frequent use—so you can enjoy crystal-clear water all day long.

        Patented Dirt-Locking Technology: Our exclusive dirt-locking structure efficiently captures debris and makes cleaning effortless. During rinsing, trapped dirt is released easily and thoroughly. The filter is simple to rinse, reusable, and significantly reduces both maintenance time and costs.

        50-Micron Fine Filtration: Upgraded with a 50-micron high-efficiency filtration layer, it effectively removes up to 99% of fine particles such as hair, leaves, dust, and sand. It keeps pool water sparkling clear for longer, reducing the need for frequent water changes and chemical use—saving you both time and money.

        Durable Heavy-Duty Construction: Made with 4 oz. thickened polyester filter fabric, reinforced ABS end caps, and a strengthened integrated core, this filter lasts over 30% longer than standard cartridges. It reduces replacement frequency and long-term maintenance costs, delivering greater value over time.

        Not for Backwashing – This filter cartridge is not designed for backwashing. Backwashing may cause cracks or permanent damage.


    Spa-Daddy SD-01433 Filter - Replacement for Marlin Spa, Romanesque, Waterworks | 27 Sq. Ft. Replaces Pleatco PPM30 | Filbur FC-3070 | Unicel C-5627

    Price: 42.00

    SKU: NCC-330

        Length: 14 3/4" | Diameter: 5 3/16" | Top: Open 1 1/16" | Bottom: Open 1 5/8"

        Spa-Daddy filters are Guaranteed against defects for One Full Year and feature our free flow core which allows a) greater water flow through the filter for better filtration; b) stronger water pressure at your jets; and c) reduced stress on your pump.

        Replaces Pleatco PPM30 | Filbur FC-3070 | Unicel C-5627

        Replaces 678285150316 |12701 |AK-4030 |50271


    Filbur FC-2375 Antimicrobial Replacement Filter Cartridge for Rainbow/Pentair Dynamic 25 Pool and Spa Filter

    Price: 33.21

        Brand: Filbur

        Material: Polyester, Pvc

        Product Dimensions: 13.31"L x 4.94"W x 11"Th

        Compatible Devices:    Pool and Spa Filters (Apollo Spas, Aqua Mystic, Arctic Spas, etc.)

        Item Weight: 3 Ounces

    Global Trade Identification Number: 00645544023759
    ```
>
> ---

## Create A New Autonomous AI Agent 
> Create A New Autonomous AI Agent Named Bob's Pool and Spa_yourName
>
> Set the Welcome message to: <copy>Thank you for contacting Bob's Pool and Spa, how can I help you?</copy>
>
> Set the Agent goal similar to: <copy>You are a polite and helpful agent that will help customers lookup and order pool and spa supplies.</copy>
>
> Save your changes
>
> Add the Knowledge you created in the previous step.
>
> ---

### Testing
> Using the Preview option
>
> - Can you come look at Spas in the showroom today?  
> - Are there any promotions going on this month?
> - How late can you pick up parts?
> - Find a replacement filter for your Unicel C-5627
>
> ---

## Actions

