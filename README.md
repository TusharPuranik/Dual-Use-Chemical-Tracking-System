# Dual-Use-Chemical-Tracking-

Absract
Development of an app/software for tracking dual use chemicals (chemicals that have legit uses and when diverted become precursors to major drugs) from their manufacture to end use. Need to have proper app and software to collate and maintain this data with proper data mining facilities. We should also have uilities in generating crucial report.

Objective
This Dual use drug tracking software is specifically designed for the NCB to track the supply chain of chemicals that can be illicitly used from the manufacturer to the end user. Both Application for phones and Software is developed for the project where data is continuously updated.

The concepts of Ethereum Blockchain are used to build the software’s. An application for the users of the supply chain use this model for the delivery of the package (drugs). The website is connected to a local blockchain created using Ganache in which the data is stored of every transaction.

The user will first have to register himself into the supply chain and select which type of user they are. The users can operate through different features type wise.

For a manufacturer, the user can add a new product. In this process a feature of QR generation is added. This QR needs to be put by the manufacturer on the package.

Other users can scan this QR to update the status of the drug package which will then be visible to all users.

Another software is created which will specifically be accessed by the NCB. This application is constructed using the DASH Framework. Package tracking is done by geotagging the package at every shipment facility.

Advanced Statistically graphs are derived from PLOTLY to have uniqueness in visual representation of this data.

This software is indirectly connected to the blockchain and is updated at runtime. The NCB will have options to search through the data on the basis of precursors or manufacturers. Automated generation of reports is done to have a better information storing regarding the dual use drug data.

An Android application is also built which the workers in the facilities can use to scan the QR on the drug packages through which the data related to that package will be updated.

Technology Stack
Solidity
Ganache v2.5.4
Truffle v5.4.29
Dash Framework
Plotly
