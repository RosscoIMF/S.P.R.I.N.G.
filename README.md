# S.P.R.I.N.G.
Spring Profile Reverse-Engineering Integrated Numerical Generator v1.00

S.P.R.I.N.G was designed to help you analyze and reverse-engineer springs, calculate their potential energy, and compare this energy with the muzzle energy of an air rifle. By doing this, you can measure the efficiency of the air rifle.

The app allows you to input details about the spring and its configuration, and it will calculate important values like:

    The spring's potential energy at a given displacement.
    The spring's force and displacement.
    The spring constant (a measure of the spring's stiffness).
    The spring's solid length (the shortest length the spring can compress to).
    And much more!

Purpose

The main goal of this app is to reverse-engineer a spring by determining its potential energy at different displacements. You can then compare that energy to the muzzle energy to see how efficient the rifle is at turning the spring's stored energy into kinetic energy. The app calculates several important parameters that can help you understand how a spring performs in an air rifle.
How to Use the App: Step-by-Step Instructions

    Choose the Right Tab
    The app has four tabs at the top:
        Spring Calculator: Used to calculate properties of the spring (spring constant, potential energy, etc.).
        Mean Diameter Calculator: Used to calculate the spring's mean diameter from the inner and outer diameters.
        PE/KE Calculator: Used to compare the potential energy of the spring and the muzzle energy of the air rifle.
        About: Displays information about the app and how it works.

    Spring Calculator
    In this tab, you’ll enter the details of the spring:
        Wire Diameter: Enter the diameter of the wire used in the spring (in millimeters).
        Mean Diameter: The average diameter of the spring (calculated from the inner and outer diameters).
        Number of Coils: The number of coils in the spring.
        Shear Modulus: The stiffness of the material the spring is made from (this is set to 80 GPa by default, but you can adjust it if needed).
        Displacement: How much the spring compresses (in millimeters).
        Free Length: The length of the spring when not compressed.
        Closed and Ground Ends: Whether the ends of the spring are closed and ground (this affects the spring's behavior when compressed).

    Once you've entered this information, click the Calculate button. The app will compute:
        Spring Constant (k): A measure of how stiff the spring is.
        Potential Energy (PE): The energy stored in the spring when compressed (in Joules and ft-lb).
        Spring Force: The force the spring applies at the given displacement.
        Solid Length: The length of the spring when fully compressed.

    These values will be shown on the screen, giving you a full understanding of the spring's properties.

    Mean Diameter Calculator
    If you don’t know the mean diameter of the spring but you have the Inner Diameter (ID) and Outer Diameter (OD), you can enter them here, and the app will calculate the mean diameter for you.

    PE/KE Calculator
    In this tab, you’ll compare the potential energy of the spring (calculated in the Spring Calculator) with the muzzle energy of the air rifle.
    To do this, enter:
        Potential Energy (Joules): The energy stored in the spring.
        Mass of Pellet: The mass of the pellet used in the rifle (in grains or grams).
        Velocity of Pellet: The speed at which the pellet leaves the barrel of the rifle (in m/s or ft/s).

    The app will calculate:
        Muzzle Energy: The energy of the pellet when fired (in Joules and ft-lb).
        Efficiency: A measure of how well the rifle converts the spring's stored energy into the pellet's kinetic energy.
        Momentum: The momentum of the pellet after being fired.
        Time of Flight: How long it takes the pellet to travel a set distance (like 25 meters).
        Velocity Deviation: How much the pellet's velocity varies from the average.

    The app will display these results to help you evaluate the air rifle's performance.

