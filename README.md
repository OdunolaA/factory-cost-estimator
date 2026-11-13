# factory-cost-estimator# Kinmo Factory Cost Estimator

**Live demo:** [your GitHub Pages link]

An interactive tool that gives an indicative capital budget for a small to medium processing plant in Nigeria, from shea butter and cashew to tomato paste and rice milling.

## The problem

Importers, exporters and investors exploring manufacturing in Nigeria often ask the same first question: *"How much will a factory cost?"* Getting even a rough answer usually takes days of calls to equipment suppliers, contractors and consultants. Many promising projects stall at this stage, or start with budgets that leave out power, contingency and working capital, which are the costs that most often sink small plants.

## What it does

Users choose a product, daily capacity, and options for the building, equipment sourcing and power. The tool instantly returns:

- an estimated total investment in naira and US dollars, with a likely range
- a breakdown across equipment, installation, building, power, approvals, FX buffer, contingency and working capital
- editable planning assumptions (exchange rate, contingency, FX buffer, months of working capital)
- warnings when a configuration carries extra risk, such as large plants or locally fabricated equipment at scale

## How it works

- **Economies of scale:** equipment cost scales with capacity^0.65, so doubling capacity costs about 1.6×, not 2×.
- **FX exposure:** a separate buffer applies only to the imported share of equipment, reflecting naira volatility.
- **Nigeria-specific costs:** power is sized in kVA from capacity and product energy intensity, because most plants need their own generation.
- **Working capital:** included by default, since running out of cash during ramp-up is a common reason new factories fail.

All figures are indicative planning assumptions, not supplier quotes.

## Built with

- HTML, CSS and vanilla JavaScript, in a single file with no dependencies
- Built with AI-assisted development (Claude), with cost logic and assumptions designed from manufacturing consulting experience

## What I'd build next

1. Calibrate cost assumptions against real supplier quotes by state
2. Add revenue and payback estimates to show return on investment
3. Export a PDF summary for banks and investors
4. Lead capture, so estimates can turn into consultation bookings

## About

Built by [Your Name] · Founder, [Kinmo Solutions](https://kinmosolutions.com), building factories across Africa
