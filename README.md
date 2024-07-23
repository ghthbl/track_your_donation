### Introduction

This script is designed to manage and analyze donation allocations for various projects and operational expenses in a charity. The primary functionalities of the script are as follows:

1. **Importing Data**: The script imports CSV files containing information about donations and budgets for different projects and operational expenses. These files are read into pandas DataFrames for easy manipulation and analysis.

2. **Calculating Allocations**: The script calculates the portion of each donation that is allocated to project budgets and operational expenses based on predefined percentages.

3. **Allocating Unlabeled Donations**: Unlabeled donations, which are donations not specifically earmarked for a particular project, are allocated to various project budgets. The script ensures that these donations are distributed appropriately based on the available budget and the size of the donations.

4. **Assigning Donations to Budget Posts**: The script matches donations to specific budget posts within each project. It ensures that the donations are allocated in a way that covers the costs of the budget items.

5. **Handling Operational Expenses**: Donations are also allocated to operational expenses, which are costs that are necessary for the overall functioning of the charity but are not specific to a single project. The script ensures these expenses are appropriately covered by the donations.

6. **Managing the War Chest**: Any remaining donations that are not allocated to project budgets or operational expenses are added to a "war chest," which represents unallocated funds that can be used for future needs.

7. **Generating Reports**: For each donation, the script can generate a detailed report showing how the donation was allocated. This includes the projects, categories, and specific budget items that the donation helped to fund.
