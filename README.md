# Rent Bill Generator

A simple web app for house owners to create monthly rent bills, including electricity and water charges, and share or print them for tenants.

**Live demo:** https://priyaramajayam2007-sys.github.io/rent-bill-generator/

## Problem
Many house owners calculate rent and utility bills by hand and send them as plain messages. This is slow and easy to get wrong.

## Features
- Calculates electricity from meter readings and a per-unit rate
- Adds rent, water bill and other charges to a total
- Printable bill layout and Save as PDF
- Share the bill on WhatsApp or copy it as text
- Remembers tenants and the last meter reading on the device
- Works on phone and laptop

## Tech Stack
HTML, CSS, JavaScript (no frameworks), browser localStorage

## How to Use
1. Enter the owner and tenant details
2. Enter rent, meter readings, rate and other charges
3. Click Generate bill
4. Print, save as PDF, or share on WhatsApp

## Design Notes
- Money is calculated in paise (integers) to avoid floating-point rounding errors
- Inputs are validated, for example the current reading cannot be lower than the previous one

## Future Improvements
- Owner login and database so data syncs across devices
- Slab-based electricity pricing
- Bill history with paid/unpaid tracking
- Tamil language option
