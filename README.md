# Unilever Dashboard - Canvas

A professional dashboard with unified chart system for visualizing Unilever performance metrics.

## 🚀 Features

- **Monthly Time-Based Charts**: All "Tendencial Anual" charts display monthly progression (Ene 2024, Feb 2024, etc.)
- **Unified Chart System**: Clean, maintainable code with centralized configuration
- **Professional Line Graphs**: Compliance and target lines with proper styling
- **Dynamic Scaling**: Y-axis automatically adapts to data ranges
- **Responsive Design**: Works across different screen sizes

## 📊 Charts Included

1. **Tendencial Anual Bloque** - Overall performance trends
2. **Tendencial Anual Posición de anaquel** - Shelf position performance
3. **Tendencial Anual Adyacencia** - Adjacency performance
4. **Tendencial Anual Cajillas** - Box/package performance
5. **Tendencial Anual Adyacencia bloque** - Block adjacency performance
6. **Tendencial Anual % Presencia en charolas** - Tray presence percentage

## 🔧 Technical Improvements

- **Refactored from ~800 lines to ~200 lines** of maintainable code
- **Unified configuration system** for easy data updates
- **Consistent styling** across all charts
- **Improved error handling** and debugging
- **Dynamic chart scaling** based on actual data values

## 🎨 Chart Features

- **Two-line display**: 
  - 🟠 **Compliance line** (solid orange) - actual performance
  - 🟤 **Target line** (dotted brown) - performance targets
- **Interactive legend** with proper color coding
- **Grid lines** for easy reading
- **Data point markers** with percentage labels
- **Spanish month format** (Ene, Feb, Mar, etc.)

## 🛠️ Usage

Simply open `dashboard.html` in a web browser to view the dashboard.

## 📈 Data Structure

Charts use a unified configuration system:

```javascript
const CHART_CONFIGS = {
    chartName: {
        canvasId: 'canvasElementId',
        labels: ['Ene 2024', 'Feb 2024', ...],
        compliance: [41, 41, 45, 40, 35, 34, 63],
        target: [65, 65, 65, 65, 65, 65, 65],
        dataUnit: '% Performance'
    }
}
```

## 🔄 Recent Updates

- ✅ Unified all chart functions into single, maintainable system
- ✅ Fixed chart display issues (empty/blank charts)
- ✅ Implemented consistent monthly time-based format
- ✅ Added dynamic scaling for better data visualization
- ✅ Simplified codebase for easier maintenance

---

**Repository**: https://github.com/joserafael1990/canvas
