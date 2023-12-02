# Udacity Data Governance Course

<img src="img/Data Governance.png" alt="Nanodegree Image" width="1000" >

# Created by Osama Alsubaie

This repository contains projects and practice set for Udacity Data Governance Course.

## Design an Enterprise Data Management System (Data Governance at SneakerPark)</a>

In the SneakerPark project, I was able to comprehensive overhaul of data management strategies, documenting existing systems, implementing a robust data catalog, refining data quality protocols, and establishing formalized data governance structures. This aimed to create a solid foundation for efficient data handling and future scalability.

## Goal of the Project

The goal is to create the foundational data management tools and artifacts that will allow SneakerPark to better manage their data now and in the future. More specifically, this entails documenting SneakerPark's data systems, setting up a data catalog, designing better data quality and master data management processes, and formalizing data governance roles.

1. <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/Starter%20Template.pdf" title="Solution Report">Solution Report</a>
2. <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/SneakerPark%20Templates.xlsx">Excel sheet template</a>

## Business Scenario

SneakerPark is an online shoe reseller that allows people to buy and sell used and new shoes. Buyers can bid for shoes or buy them outright, and sellers can set a price or sell to the highest bidder.

Each buyer and seller must have an active account in order to sell, bid, or purchase sneakers using SneakerPark’s website.

SneakerPark authenticates the shoes before shipping them to the buyer, so before listing an item, the seller must ship it to SneakerPark’s warehouse. Upon receipt, SneakerPark assigns an item number to each pair of sneakers and notifies the seller that they are now free to list their item. If the item is not listed within 45 days, SneakerPark returns the sneakers to the seller and sends an invoice to the seller for the shipping cost.

If the item is found to be inauthentic or in an unacceptable condition, it is also returned back to the seller in a similar fashion.

When the item sells, the seller's account is credited with the purchase price minus the SneakerPark service fee and shipping fees to deliver the item to the buyer.

# Solution

- Create an Enterprise Conceptual Model that provide a holistic view of data in these three systems

- Design the draft version of the Enterprise Data Catalog by documenting the metadata in an Excel spreadsheet.

- Profile the data to identify 3 data quality issues. Create a document that lists each data quality issue, its description, and a suggested remediation strategy for each.

- Design a data quality dashboard that will report on the issues you’ve identified above plus at least 1 more issue that you foresee might occur in the future.

- Sketch out a proposed MDM implementation architecture, and write a detailed explanation of why you  chose this specific approach.

- Define a set of matching rules that will be used by SneakerPark's MDM Hub to match item and customer entities between the company's different systems.

- Write a paragraph discussing what data governance roles and responsibilities will be necessary to oversee this new Data Management initiative.

## 1.Enterprise Data Model

Solution can be found on `Step 1` of <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/Starter%20Template.pdf">Solution Report</a>.

## 2.Enterprise Data Catalog

Solution can be found on `Step 2` of <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/Starter%20Template.pdf" title="Enterprise Data Catalog">Solution Report</a>.

## 3.Data Profiling/Cleansing

Solution can be found on `Data Quality Issues` of <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/SneakerPark%20Templates.xlsx" title="Excel sheet template">Excel sheet template</a>.

## 4.Monitoring/Dashboards

Solution can be found on `Step 4` of <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/Starter%20Template.pdf">Solution Report</a>.

## 5.MDM Architecture

<img src="img/MDM Arch.png" alt="MDM Architecture" width="1000" >
Also the Solution can be found on `Step 5` of <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/Starter%20Template.pdf">Solution Report</a>.

## 6.Master Record

Solution can be found on `Step 6` of <a href="https://github.com/alsubaie-os/SneakerPark-Enterprise-Data-Management-System/blob/a402dc57034cdb3a80b23cce13ab290e019befd7/Starter%20Template.pdf">Solution Report</a>.
