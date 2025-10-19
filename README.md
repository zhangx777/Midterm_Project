# Midterm Project: Tori's Places to Visit

This SwiftUI application serves as a travel wish-list and destination guide focused on "Tori's places to visit." 

## Project Structure:
* Custom Data Model (Subject.swift): Defines the structure for each travel destination, including name, image asset name, and description.
* JSON Data Loading: Utilizes the Helper.swift utility to load and parse destination data from Data.json.
* Main List View (ContentView.swift): Displays a list of destinations, each featuring a circular thumbnail and the place's name.
* Navigation: Uses NavigationStack to allow users to tap a list item and transition to a detail view.
* Detail View (DetailView.swift): Presents a larger, rectangular image of the selected place, the name, and a detailed description, including the best season to visit and scenic spots.

## How to Run:

* Open the project in Xcode.
* Ensure all Swift files (Subject.swift, Helper.swift, ContentView.swift, DetailView.swift) and Data.json are included in the target.
* Ensure the required image assets are added to Assets.xcassets.
* Select an iPhone Simulator.
* Build and Run (Cmd + R).
