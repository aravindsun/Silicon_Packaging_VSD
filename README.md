# Silicon_Packaging_VSD
This repository contains detailed documentation about the semiconductor packaging workflow and various other aspects involved in packaging like thermal analysis, CAD modelling etc.

# Introduction to Semiconductor Packaging
Semiconductor Packaging is a process involved in the chip manufacturing workflow and serves two important purposes :-

      1) To protect the bare die from corrosion, moisture and physical damages that can happen in real world
      2) To enable the dies to connect with other dies or components
      
<img width="1045" height="505" alt="image" src="https://github.com/user-attachments/assets/657b2e90-1ed7-4a39-845f-7241d3d15d1e" />

# Example of a chip package
The picture below illustrates the various components involved in a particular type of package called Ball Grid Array(BGA) package. The bare die is attached to a substrate(green) using a material called die attach. The connections from the die is taken out through the substarte via wires(wire bonding). Inorder to protect the die from external damages the entire die is covered with a molding component which is generally the ones which we see in real chips.

<img width="510" height="212" alt="image" src="https://github.com/user-attachments/assets/3a7971ea-5214-4b68-9711-bb06f283bd99" />

# Selecting the right package
There are various kinds of packages available for a chip. The application and other requirements will decide the right packaging style. Some of the important considerations for selecting a package are:

      1) Pincount (Packages like BGA, PBGA have more pin count and high package efficiency)
      2) Thermal Dissipation
      3) Form Factor (Package like Chip Scale Package(CSP) will have tiny form factor)
      4) Application
      5) Reliability & Durability
      6) Cost (Crucial Parameter!!)

# Different Package Styles
The below picture illustrates some of the common package styles used.

<img width="1230" height="324" alt="image" src="https://github.com/user-attachments/assets/7f60af1a-ee94-4788-a81b-ab5b373f7b30" />

# Typical Package Structures
Generally there are two interconnections which are important to be considered in packaging a chip and enable it to communicate with other chips. First is the interconnection between the die and the substrate and the other one is the interconnection between the substrate and the pcb (or to other dies outside the package). The die is interfaced with the substrate with the help of wires and the process is called wire bonding. Similar to wire bonding, which connects to the die from the top, another way to make the connection is flip chip connection. Here the chip is flipped down and the connection to the substarte is made via solder balls embedded in underfill.

<img width="758" height="277" alt="image" src="https://github.com/user-attachments/assets/298d7bce-1f01-44d1-a2f8-30a9485bf22e" />




