# Investment ROI & NPV Analysis Framework

A professional-grade financial analysis tool for evaluating investment projects through comprehensive metrics including ROI, NPV, payback period, and strategic scoring. Built for finance professionals, CFOs, and investment managers who need rigorous quantitative analysis combined with qualitative strategic insights.

## Overview

This framework provides enterprise-level investment analysis capabilities through an intuitive web interface. It combines traditional financial metrics with sector-specific evaluation criteria and risk assessment methodologies to deliver actionable investment recommendations.

## Key Features

### Financial Analysis
- **Return on Investment (ROI)**: Three calculation models supporting CAPEX-only, OPEX-only, and hybrid investment structures
- **Net Present Value (NPV)**: Time-value adjusted cash flow analysis with configurable discount rates
- **Payback Period**: Break-even timeline calculation with growth rate adjustments
- **Strategic Scoring**: Proprietary 100-point scoring system incorporating financial performance, risk factors, and sector-specific considerations

### Advanced Analytics
- **Sensitivity Analysis**: Four-parameter sensitivity testing showing impact of revenue, CAPEX, risk, and discount rate variations across ±20% ranges
- **Cash Flow Projection**: Year-by-year breakdown of capital expenditure, operating expenses, revenue, and cumulative positions
- **Break-even Analysis**: Annual break-even revenue requirements with cumulative investment tracking
- **Scenario Modeling**: Best case, base case, and worst case projections for risk evaluation

### Sector-Specific Intelligence
Pre-configured evaluation criteria for five major sectors:
- Banking & Regulation (IFRS9/Basel compliance considerations)
- Retail & E-Commerce (volume-driven models)
- Software & SaaS (technical debt and scalability factors)
- Insurance & Fintech (actuarial accuracy and regtech requirements)
- Manufacturing & Logistics (fixed cost burden and capacity utilization)

### Data Management
- **Auto-Save**: Automatic state preservation during active sessions
- **Analysis History**: Stores last 10 analyses with complete parameter sets
- **Excel Export**: Five-sheet workbook with summary, cash flows, sensitivity data, break-even calculations, and visualization-ready datasets
- **PDF Export**: Professional formatted reports with all metrics and recommendations
- **Import Capability**: Load parameters from existing Excel files for template-based analysis

### Multi-Language Support
Complete Turkish and English localization across all interface elements, data tables, and analytical outputs.

## Use Cases

### Investment Committee Review
Present standardized investment proposals with consistent metrics across projects. Strategic scoring provides at-a-glance comparison while detailed cash flow projections support deep-dive discussions.

### Portfolio Optimization
Compare multiple investment opportunities using identical evaluation frameworks. Sensitivity analysis reveals which parameters most significantly impact returns.

### Risk Assessment
Risk-adjusted scoring combines quantitative metrics with qualitative factors. Sector-specific adjustments ensure appropriate benchmarking against industry standards.

### Budget Planning
Break-even analysis informs realistic revenue targets. Cash flow projections identify funding requirements across project timelines.

### Due Diligence
Comprehensive parameter documentation creates audit trail. Excel exports integrate seamlessly with existing financial models and reporting systems.

## Technical Specifications

### Architecture
Single-page application requiring no backend infrastructure. All calculations execute client-side for maximum privacy and performance.

### Browser Compatibility
Modern browsers with ES6 support. Tested on Chrome, Firefox, Safari, and Edge.

### Dependencies
- Chart.js for visualization
- SheetJS (xlsx) for Excel operations  
- jsPDF for PDF generation
- No framework dependencies

### Data Privacy
All data remains local to user browser. No information transmitted to external servers. LocalStorage used exclusively for state persistence.

## Getting Started

### Basic Workflow

1. **Select Sector**: Choose the industry category that best matches your investment project
2. **Enter Parameters**: Input capital expenditure, operating expenses, expected revenue, and projection timeline
3. **Configure Risk**: Adjust risk factor slider and set growth rate assumptions
4. **Review Analysis**: Examine calculated metrics, strengths, risks, and strategic recommendation
5. **Explore Scenarios**: Review data sheets for sensitivity analysis and cash flow projections
6. **Export Results**: Generate Excel workbook or PDF report for distribution

### Parameter Guidelines

**Capital Expenditure (CAPEX)**: One-time upfront investment costs including equipment, facilities, systems, and initial setup expenses.

**Operating Expenses (OPEX)**: Annual recurring costs including salaries, rent, utilities, maintenance, and ongoing operational requirements.

**Expected Revenue**: Projected annual revenue from the investment. Use conservative estimates for initial years.

**Projection Period**: Analysis timeframe typically ranging from 3-7 years depending on project nature and payback expectations.

**Risk Factor**: Subjective assessment from 0-100 reflecting execution risk, market uncertainty, regulatory concerns, and other project-specific hazards.

**Growth Rate**: Annual compound growth rate for both revenues and expenses. Use sector benchmarks as reference.

**Discount Rate**: Cost of capital or hurdle rate. Typically company WACC plus risk premium.

## Interpretation Guide

### ROI Thresholds
- Above 150%: Exceptional returns, high priority
- 100-150%: Strong performance, recommended  
- 50-100%: Acceptable returns, evaluate alternatives
- Below 50%: Marginal performance, careful review required

### NPV Decision Rules
- Positive NPV: Project creates value, proceed
- Zero NPV: Project breaks even, consider strategic value
- Negative NPV: Project destroys value, reject unless compelling strategic rationale

### Payback Period Benchmarks
- Under 18 months: Fast recovery, low risk
- 18-30 months: Standard timeframe, acceptable
- 30-48 months: Longer commitment, higher risk
- Over 48 months: Extended exposure, requires strong strategic justification

### Strategic Score Ranges
- 75-100: Highly recommended, all metrics positive
- 60-74: Recommended with conditions, monitor risks
- 40-59: Careful evaluation required, mixed signals
- Below 40: Not recommended, fundamental concerns

## Advanced Features

### Sensitivity Analysis Interpretation
Tornado chart data reveals which parameters have greatest influence on outcomes. Focus risk mitigation efforts on high-impact variables. Revenue sensitivity typically shows highest leverage in most projects.

### Cash Flow Management
Cumulative cash flow projection identifies funding requirements. Negative positions indicate capital needs. Plan financing to cover gaps until positive territory reached.

### Break-even Planning
Year-by-year break-even revenue shows realistic targets. Compare against market size and competitive positioning to validate achievability.

### Scenario Planning
Best case, base case, and worst case projections bracket likely outcomes. Use range to assess risk-reward profile and set expectations appropriately.

## Best Practices

### Conservative Assumptions
Use pessimistic revenue projections and realistic cost estimates. Better to exceed low expectations than miss aggressive targets.

### Regular Updates
Revisit analysis quarterly as projects progress. Update parameters with actual results to refine projections.

### Comparative Analysis
Evaluate multiple alternatives using consistent parameters. Relative rankings often more informative than absolute scores.

### Stakeholder Communication
Export professional reports for investment committees. Transparent methodology builds confidence in recommendations.

### Documentation
Maintain parameter rationale. Document why specific assumptions chosen. Creates accountability and learning for future analyses.

## Limitations and Considerations

This framework provides quantitative analysis but cannot replace qualitative judgment. Consider factors beyond numerical metrics including strategic fit, organizational capability, competitive dynamics, and market timing.

Garbage in, garbage out applies. Analysis quality depends entirely on input parameter accuracy. Invest time in developing realistic assumptions.

Past performance does not guarantee future results. Historical benchmarks provide guidance but each project has unique characteristics.

Sensitivity analysis explores parameter variations but cannot capture all possible scenarios. Black swan events and discontinuous changes require separate consideration.

## Support and Feedback

This tool continues to evolve based on user feedback and changing analytical requirements. Suggestions for enhancements, additional metrics, or sector-specific modifications are welcome.

## License

Copyright 2026 Metin Demirtel. All rights reserved.

## Version History

**Version 1.0 (January 2026)**
- Initial release with core ROI, NPV, payback, and scoring capabilities
- Five-sector evaluation framework
- Turkish and English localization
- Excel and PDF export functionality
- Sensitivity analysis and cash flow projections
- Analysis history and auto-save features

---

Developed by Metin Demirtel, 2026
