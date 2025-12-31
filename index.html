<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virtual Trading Simulation</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0f172a;
            color: #e2e8f0;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #334155;
        }
        
        h1 {
            color: #60a5fa;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            color: #94a3b8;
            font-size: 1.1rem;
        }
        
        .dashboard {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 25px;
            margin-bottom: 30px;
        }
        
        @media (max-width: 768px) {
            .dashboard {
                grid-template-columns: 1fr;
            }
        }
        
        .card {
            background-color: #1e293b;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            border: 1px solid #334155;
        }
        
        .card-title {
            font-size: 1.4rem;
            color: #60a5fa;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .portfolio-value {
            font-size: 2.8rem;
            font-weight: bold;
            color: #34d399;
            text-align: center;
            margin: 15px 0;
        }
        
        .portfolio-details {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid #334155;
        }
        
        .detail-item {
            text-align: center;
        }
        
        .detail-label {
            color: #94a3b8;
            font-size: 0.9rem;
            margin-bottom: 5px;
        }
        
        .detail-value {
            font-size: 1.3rem;
            font-weight: 600;
        }
        
        .profit {
            color: #34d399;
        }
        
        .loss {
            color: #f87171;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
        }
        
        th {
            text-align: left;
            padding: 12px 10px;
            background-color: #334155;
            color: #cbd5e1;
            font-weight: 600;
        }
        
        td {
            padding: 12px 10px;
            border-bottom: 1px solid #334155;
        }
        
        tr:hover {
            background-color: #2d3748;
        }
        
        .trade-form {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-top: 20px;
        }
        
        .form-group {
            display: flex;
            flex-direction: column;
        }
        
        .form-group.full-width {
            grid-column: 1 / span 2;
        }
        
        label {
            margin-bottom: 8px;
            color: #cbd5e1;
            font-weight: 500;
        }
        
        input, select {
            padding: 12px 15px;
            background-color: #0f172a;
            border: 1px solid #475569;
            border-radius: 6px;
            color: #e2e8f0;
            font-size: 1rem;
        }
        
        input:focus, select:focus {
            outline: none;
            border-color: #60a5fa;
        }
        
        .btn {
            padding: 12px 20px;
            background-color: #3b82f6;
            color: white;
            border: none;
            border-radius: 6px;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s;
            font-size: 1rem;
        }
        
        .btn:hover {
            background-color: #2563eb;
        }
        
        .btn-buy {
            background-color: #10b981;
        }
        
        .btn-buy:hover {
            background-color: #059669;
        }
        
        .btn-sell {
            background-color: #ef4444;
        }
        
        .btn-sell:hover {
            background-color: #dc2626;
        }
        
        .btn-reset {
            background-color: #8b5cf6;
        }
        
        .btn-reset:hover {
            background-color: #7c3aed;
        }
        
        .button-group {
            display: flex;
            gap: 10px;
            margin-top: 15px;
        }
        
        .summary {
            margin-top: 40px;
        }
        
        .summary-content {
            line-height: 1.8;
            margin-top: 15px;
        }
        
        .instructions {
            background-color: rgba(96, 165, 250, 0.1);
            border-left: 4px solid #60a5fa;
            padding: 15px;
            margin-top: 25px;
            border-radius: 0 8px 8px 0;
        }
        
        .instructions h3 {
            color: #60a5fa;
            margin-bottom: 10px;
        }
        
        .instructions ol {
            margin-left: 20px;
        }
        
        .instructions li {
            margin-bottom: 8px;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #334155;
            color: #94a3b8;
            font-size: 0.9rem;
        }
        
        .success-message {
            background-color: rgba(52, 211, 153, 0.2);
            border: 1px solid #10b981;
            color: #a7f3d0;
            padding: 12px;
            border-radius: 6px;
            margin-top: 15px;
            display: none;
        }
        
        .export-section {
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid #334155;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-chart-line"></i> Virtual Trading Simulation</h1>
            <p class="subtitle">Track your mock portfolio and simulate trades with ₹1,00,000 virtual capital</p>
        </header>
        
        <div class="dashboard">
            <div class="card">
                <h2 class="card-title"><i class="fas fa-wallet"></i> Portfolio Overview</h2>
                <div class="portfolio-value" id="portfolioValue">₹1,00,000.00</div>
                <div class="portfolio-details">
                    <div class="detail-item">
                        <div class="detail-label">Cash Balance</div>
                        <div class="detail-value" id="cashBalance">₹1,00,000.00</div>
                    </div>
                    <div class="detail-item">
                        <div class="detail-label">Invested Value</div>
                        <div class="detail-value" id="investedValue">₹0.00</div>
                    </div>
                    <div class="detail-item">
                        <div class="detail-label">Total P&L</div>
                        <div class="detail-value" id="totalPnL">₹0.00</div>
                    </div>
                </div>
            </div>
            
            <div class="card">
                <h2 class="card-title"><i class="fas fa-exchange-alt"></i> Execute Trade</h2>
                <form id="tradeForm">
                    <div class="trade-form">
                        <div class="form-group">
                            <label for="stockSelect">Stock</label>
                            <select id="stockSelect" required>
                                <option value="">Select a stock</option>
                                <option value="RELIANCE">Reliance Industries (RELIANCE)</option>
                                <option value="TCS">Tata Consultancy Services (TCS)</option>
                                <option value="HDFCBANK">HDFC Bank (HDFCBANK)</option>
                                <option value="INFY">Infosys (INFY)</option>
                                <option value="ICICIBANK">ICICI Bank (ICICIBANK)</option>
                                <option value="BHARTIARTL">Bharti Airtel (BHARTIARTL)</option>
                                <option value="ITC">ITC Limited (ITC)</option>
                                <option value="SBIN">State Bank of India (SBIN)</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="tradeType">Action</label>
                            <select id="tradeType" required>
                                <option value="BUY">Buy</option>
                                <option value="SELL">Sell</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="quantity">Quantity</label>
                            <input type="number" id="quantity" min="1" value="10" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="price">Price (₹)</label>
                            <input type="number" id="price" min="1" step="0.01" required>
                        </div>
                    </div>
                    
                    <div class="button-group">
                        <button type="submit" class="btn btn-buy" id="submitBtn">Execute Buy Order</button>
                        <button type="button" class="btn btn-reset" id="resetBtn">Reset Portfolio</button>
                    </div>
                    
                    <div class="success-message" id="successMessage">
                        Trade executed successfully!
                    </div>
                </form>
            </div>
        </div>
        
        <div class="card">
            <h2 class="card-title"><i class="fas fa-list-alt"></i> Trade History</h2>
            <div class="table-container">
                <table id="tradeHistory">
                    <thead>
                        <tr>
                            <th>Date & Time</th>
                            <th>Stock</th>
                            <th>Action</th>
                            <th>Quantity</th>
                            <th>Buy Price (₹)</th>
                            <th>Sell Price (₹)</th>
                            <th>Profit/Loss (₹)</th>
                        </tr>
                    </thead>
                    <tbody id="tradeHistoryBody">
                        <!-- Trade rows will be added here dynamically -->
                    </tbody>
                </table>
            </div>
            
            <div class="export-section">
                <h3 class="card-title"><i class="fas fa-download"></i> Export Data</h3>
                <p>Download your trade history for your assignment submission:</p>
                <div class="button-group">
                    <button class="btn" id="exportCSV"><i class="fas fa-file-csv"></i> Export to CSV</button>
                    <button class="btn" id="exportSummary"><i class="fas fa-file-alt"></i> Generate Summary</button>
                </div>
            </div>
        </div>
        
        <div class="card summary">
            <h2 class="card-title"><i class="fas fa-chart-pie"></i> Simulation Summary</h2>
            <div class="summary-content" id="summaryContent">
                <p>This virtual trading simulation started with a portfolio value of <strong>₹1,00,000</strong>.</p>
                <p>Execute at least 5 trades to complete the assignment. Track your profit/loss for each trade in the table above.</p>
                <p>After completing your trades, export the data using the buttons above for your assignment submission.</p>
            </div>
            
            <div class="instructions">
                <h3>Assignment Instructions:</h3>
                <ol>
                    <li>Perform at least 5 virtual trades using this simulator</li>
                    <li>Record each trade with stock name, buy price, sell price, and profit/loss</li>
                    <li>Export your trade history to a spreadsheet</li>
                    <li>Write a summary report based on your trading activity</li>
                    <li>Submit both the spreadsheet and summary report</li>
                </ol>
            </div>
        </div>
        
        <footer>
            <p>Virtual Trading Simulation for Educational Purposes | This is not real financial advice</p>
            <p>Task 3: Trading Simulation (Virtual) - Created with HTML, CSS & JavaScript</p>
        </footer>
    </div>

    <script>
        // Initial portfolio state
        let portfolio = {
            cash: 100000,
            investedValue: 0,
            totalValue: 100000,
            trades: []
        };

        // Stock data with current prices (mock data)
        const stockData = {
            "RELIANCE": { name: "Reliance Industries", price: 2450.75 },
            "TCS": { name: "Tata Consultancy Services", price: 3420.50 },
            "HDFCBANK": { name: "HDFC Bank", price: 1650.25 },
            "INFY": { name: "Infosys", price: 1425.80 },
            "ICICIBANK": { name: "ICICI Bank", price: 920.40 },
            "BHARTIARTL": { name: "Bharti Airtel", price: 815.60 },
            "ITC": { name: "ITC Limited", price: 425.30 },
            "SBIN": { name: "State Bank of India", price: 550.75 }
        };

        // DOM elements
        const portfolioValueEl = document.getElementById('portfolioValue');
        const cashBalanceEl = document.getElementById('cashBalance');
        const investedValueEl = document.getElementById('investedValue');
        const totalPnLEl = document.getElementById('totalPnL');
        const tradeForm = document.getElementById('tradeForm');
        const stockSelect = document.getElementById('stockSelect');
        const tradeType = document.getElementById('tradeType');
        const priceInput = document.getElementById('price');
        const quantityInput = document.getElementById('quantity');
        const submitBtn = document.getElementById('submitBtn');
        const resetBtn = document.getElementById('resetBtn');
        const tradeHistoryBody = document.getElementById('tradeHistoryBody');
        const successMessage = document.getElementById('successMessage');
        const exportCSVBtn = document.getElementById('exportCSV');
        const exportSummaryBtn = document.getElementById('exportSummary');
        const summaryContent = document.getElementById('summaryContent');

        // Initialize the application
        function init() {
            // Load saved portfolio from localStorage if available
            const savedPortfolio = localStorage.getItem('tradingPortfolio');
            if (savedPortfolio) {
                portfolio = JSON.parse(savedPortfolio);
            }
            
            updatePortfolioDisplay();
            updateTradeHistory();
            updateSummary();
            
            // Add event listeners
            tradeForm.addEventListener('submit', executeTrade);
            resetBtn.addEventListener('click', resetPortfolio);
            stockSelect.addEventListener('change', updateStockPrice);
            tradeType.addEventListener('change', updateSubmitButton);
            exportCSVBtn.addEventListener('click', exportToCSV);
            exportSummaryBtn.addEventListener('click', generateSummary);
            
            // Set initial button text
            updateSubmitButton();
            
            // Add some sample trades if no trades exist
            if (portfolio.trades.length === 0) {
                addSampleTrades();
            }
        }

        // Update stock price when stock is selected
        function updateStockPrice() {
            const selectedStock = stockSelect.value;
            if (selectedStock && stockData[selectedStock]) {
                priceInput.value = stockData[selectedStock].price.toFixed(2);
            } else {
                priceInput.value = "";
            }
        }

        // Update submit button text based on trade type
        function updateSubmitButton() {
            if (tradeType.value === 'BUY') {
                submitBtn.textContent = 'Execute Buy Order';
                submitBtn.className = 'btn btn-buy';
            } else {
                submitBtn.textContent = 'Execute Sell Order';
                submitBtn.className = 'btn btn-sell';
            }
        }

        // Execute a trade
        function executeTrade(e) {
            e.preventDefault();
            
            const stockSymbol = stockSelect.value;
            const action = tradeType.value;
            const quantity = parseInt(quantityInput.value);
            const price = parseFloat(priceInput.value);
            
            if (!stockSymbol) {
                alert("Please select a stock");
                return;
            }
            
            const stock = stockData[stockSymbol];
            const totalCost = quantity * price;
            
            if (action === 'BUY') {
                if (totalCost > portfolio.cash) {
                    alert("Insufficient cash to execute this trade");
                    return;
                }
                
                portfolio.cash -= totalCost;
                portfolio.investedValue += totalCost;
                
                // Add trade to history
                const trade = {
                    id: Date.now(),
                    date: new Date().toLocaleString(),
                    stockSymbol: stockSymbol,
                    stockName: stock.name,
                    action: action,
                    quantity: quantity,
                    buyPrice: price,
                    sellPrice: null,
                    profitLoss: null
                };
                
                portfolio.trades.push(trade);
                
            } else { // SELL action
                // Check if we have enough shares to sell
                const buyTrades = portfolio.trades.filter(t => 
                    t.stockSymbol === stockSymbol && t.action === 'BUY' && t.sellPrice === null
                );
                
                const totalOwned = buyTrades.reduce((sum, trade) => sum + trade.quantity, 0);
                
                if (quantity > totalOwned) {
                    alert(`You only own ${totalOwned} shares of ${stockSymbol}, cannot sell ${quantity}`);
                    return;
                }
                
                // Find the oldest buy trades to match with this sell
                let remainingToSell = quantity;
                let totalProfitLoss = 0;
                
                for (let trade of buyTrades) {
                    if (remainingToSell <= 0) break;
                    
                    const sellFromThisTrade = Math.min(trade.quantity, remainingToSell);
                    const profitLoss = (price - trade.buyPrice) * sellFromThisTrade;
                    
                    // Update the original buy trade
                    if (sellFromThisTrade === trade.quantity) {
                        // Sold all shares from this trade
                        trade.sellPrice = price;
                        trade.profitLoss = profitLoss;
                    } else {
                        // Sold partial shares - we need to split the trade
                        const newTrade = {
                            ...trade,
                            id: Date.now() + Math.random(),
                            quantity: sellFromThisTrade,
                            sellPrice: price,
                            profitLoss: profitLoss
                        };
                        
                        // Update original trade with remaining quantity
                        trade.quantity -= sellFromThisTrade;
                        
                        // Add the partial sell trade
                        portfolio.trades.push(newTrade);
                    }
                    
                    totalProfitLoss += profitLoss;
                    remainingToSell -= sellFromThisTrade;
                }
                
                portfolio.cash += quantity * price;
                portfolio.investedValue -= (quantity * price) - totalProfitLoss;
            }
            
            portfolio.totalValue = portfolio.cash + portfolio.investedValue;
            
            // Save to localStorage
            localStorage.setItem('tradingPortfolio', JSON.stringify(portfolio));
            
            // Update UI
            updatePortfolioDisplay();
            updateTradeHistory();
            updateSummary();
            
            // Show success message
            successMessage.style.display = 'block';
            successMessage.textContent = `${action} order for ${quantity} shares of ${stock.name} executed successfully!`;
            
            // Hide success message after 3 seconds
            setTimeout(() => {
                successMessage.style.display = 'none';
            }, 3000);
            
            // Reset form
            tradeForm.reset();
            updateSubmitButton();
        }

        // Update portfolio display
        function updatePortfolioDisplay() {
            portfolioValueEl.textContent = `₹${portfolio.totalValue.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}`;
            cashBalanceEl.textContent = `₹${portfolio.cash.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}`;
            investedValueEl.textContent = `₹${portfolio.investedValue.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}`;
            
            // Calculate total P&L
            let totalPnL = 0;
            portfolio.trades.forEach(trade => {
                if (trade.profitLoss !== null) {
                    totalPnL += trade.profitLoss;
                }
            });
            
            totalPnLEl.textContent = `₹${totalPnL.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}`;
            
            if (totalPnL >= 0) {
                totalPnLEl.className = 'detail-value profit';
            } else {
                totalPnLEl.className = 'detail-value loss';
            }
        }

        // Update trade history table
        function updateTradeHistory() {
            tradeHistoryBody.innerHTML = '';
            
            if (portfolio.trades.length === 0) {
                const row = document.createElement('tr');
                row.innerHTML = `<td colspan="7" style="text-align: center; padding: 30px;">No trades executed yet. Execute your first trade above.</td>`;
                tradeHistoryBody.appendChild(row);
                return;
            }
            
            // Sort trades by date (newest first)
            const sortedTrades = [...portfolio.trades].sort((a, b) => b.id - a.id);
            
            sortedTrades.forEach(trade => {
                const row = document.createElement('tr');
                
                let profitLossCell = '<td>-</td>';
                if (trade.profitLoss !== null) {
                    const pnlClass = trade.profitLoss >= 0 ? 'profit' : 'loss';
                    profitLossCell = `<td class="${pnlClass}">₹${trade.profitLoss.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}</td>`;
                }
                
                row.innerHTML = `
                    <td>${trade.date}</td>
                    <td>${trade.stockName} (${trade.stockSymbol})</td>
                    <td>${trade.action}</td>
                    <td>${trade.quantity}</td>
                    <td>${trade.buyPrice ? `₹${trade.buyPrice.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}` : '-'}</td>
                    <td>${trade.sellPrice ? `₹${trade.sellPrice.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}` : '-'}</td>
                    ${profitLossCell}
                `;
                
                tradeHistoryBody.appendChild(row);
            });
        }

        // Update summary content
        function updateSummary() {
            const totalTrades = portfolio.trades.length;
            const completedTrades = portfolio.trades.filter(t => t.sellPrice !== null).length;
            const openTrades = totalTrades - completedTrades;
            
            let totalProfitLoss = 0;
            let totalInvestment = 0;
            
            portfolio.trades.forEach(trade => {
                if (trade.profitLoss !== null) {
                    totalProfitLoss += trade.profitLoss;
                }
                if (trade.action === 'BUY' && trade.sellPrice === null) {
                    totalInvestment += trade.quantity * trade.buyPrice;
                }
            });
            
            summaryContent.innerHTML = `
                <p>This virtual trading simulation started with a portfolio value of <strong>₹1,00,000</strong>.</p>
                <p><strong>Current Portfolio Value:</strong> ₹${portfolio.totalValue.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}</p>
                <p><strong>Trade Statistics:</strong> ${totalTrades} total trades (${completedTrades} completed, ${openTrades} open positions)</p>
                <p><strong>Total Profit/Loss:</strong> <span class="${totalProfitLoss >= 0 ? 'profit' : 'loss'}">₹${totalProfitLoss.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}</span></p>
                <p><strong>Current Cash Balance:</strong> ₹${portfolio.cash.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}</p>
                <p><strong>Current Invested Value:</strong> ₹${totalInvestment.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}</p>
                <p>${totalTrades >= 5 ? '✅ You have completed the requirement of at least 5 trades.' : `⚠️ You need to execute ${5 - totalTrades} more trades to complete the assignment.`}</p>
            `;
        }

        // Reset portfolio to initial state
        function resetPortfolio() {
            if (confirm("Are you sure you want to reset your portfolio? All trade history will be lost.")) {
                portfolio = {
                    cash: 100000,
                    investedValue: 0,
                    totalValue: 100000,
                    trades: []
                };
                
                localStorage.removeItem('tradingPortfolio');
                
                updatePortfolioDisplay();
                updateTradeHistory();
                updateSummary();
                
                // Add sample trades after reset
                addSampleTrades();
            }
        }

        // Add some sample trades for demonstration
        function addSampleTrades() {
            // Add 2 sample trades to demonstrate the functionality
            const sampleTrades = [
                {
                    id: Date.now() - 86400000, // 1 day ago
                    date: new Date(Date.now() - 86400000).toLocaleString(),
                    stockSymbol: "RELIANCE",
                    stockName: "Reliance Industries",
                    action: "BUY",
                    quantity: 10,
                    buyPrice: 2400.50,
                    sellPrice: 2450.75,
                    profitLoss: (2450.75 - 2400.50) * 10
                },
                {
                    id: Date.now() - 43200000, // 12 hours ago
                    date: new Date(Date.now() - 43200000).toLocaleString(),
                    stockSymbol: "INFY",
                    stockName: "Infosys",
                    action: "BUY",
                    quantity: 20,
                    buyPrice: 1410.25,
                    sellPrice: null,
                    profitLoss: null
                }
            ];
            
            // Update portfolio with sample trades
            sampleTrades.forEach(trade => {
                portfolio.trades.push(trade);
                
                if (trade.action === 'BUY') {
                    const cost = trade.quantity * trade.buyPrice;
                    portfolio.cash -= cost;
                    portfolio.investedValue += cost;
                    
                    if (trade.sellPrice) {
                        portfolio.cash += trade.quantity * trade.sellPrice;
                        portfolio.investedValue -= cost;
                    }
                }
            });
            
            portfolio.totalValue = portfolio.cash + portfolio.investedValue;
            localStorage.setItem('tradingPortfolio', JSON.stringify(portfolio));
            
            updatePortfolioDisplay();
            updateTradeHistory();
            updateSummary();
        }

        // Export trade history to CSV
        function exportToCSV() {
            if (portfolio.trades.length === 0) {
                alert("No trade history to export");
                return;
            }
            
            // Create CSV content
            let csvContent = "Date,Stock Symbol,Stock Name,Action,Quantity,Buy Price (₹),Sell Price (₹),Profit/Loss (₹)\n";
            
            portfolio.trades.forEach(trade => {
                const row = [
                    trade.date,
                    trade.stockSymbol,
                    trade.stockName,
                    trade.action,
                    trade.quantity,
                    trade.buyPrice || "",
                    trade.sellPrice || "",
                    trade.profitLoss || ""
                ];
                
                csvContent += row.join(",") + "\n";
            });
            
            // Create download link
            const blob = new Blob([csvContent], { type: 'text/csv' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'virtual-trading-history.csv';
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
        }

        // Generate and display a summary report
        function generateSummary() {
            const totalTrades = portfolio.trades.length;
            const completedTrades = portfolio.trades.filter(t => t.sellPrice !== null).length;
            const openTrades = totalTrades - completedTrades;
            
            let totalProfitLoss = 0;
            let winningTrades = 0;
            let losingTrades = 0;
            
            portfolio.trades.forEach(trade => {
                if (trade.profitLoss !== null) {
                    totalProfitLoss += trade.profitLoss;
                    if (trade.profitLoss >= 0) {
                        winningTrades++;
                    } else {
                        losingTrades++;
                    }
                }
            });
            
            const winRate = completedTrades > 0 ? (winningTrades / completedTrades * 100).toFixed(2) : 0;
            
            const summaryReport = `
VIRTUAL TRADING SIMULATION SUMMARY REPORT
===========================================

Initial Capital: ₹1,00,000.00
Current Portfolio Value: ₹${portfolio.totalValue.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}
Cash Balance: ₹${portfolio.cash.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}

TRADE STATISTICS
----------------
Total Trades Executed: ${totalTrades}
Completed Trades: ${completedTrades}
Open Positions: ${openTrades}
Winning Trades: ${winningTrades}
Losing Trades: ${losingTrades}
Win Rate: ${winRate}%

PROFIT/LOSS ANALYSIS
--------------------
Total Profit/Loss: ₹${totalProfitLoss.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}
Return on Initial Capital: ${((portfolio.totalValue - 100000) / 100000 * 100).toFixed(2)}%

TRADE HISTORY
-------------
${portfolio.trades.map(trade => 
`${trade.date} | ${trade.stockName} (${trade.stockSymbol}) | ${trade.action} | Qty: ${trade.quantity} | Buy: ${trade.buyPrice ? '₹' + trade.buyPrice : 'N/A'} | Sell: ${trade.sellPrice ? '₹' + trade.sellPrice : 'N/A'} | P&L: ${trade.profitLoss !== null ? '₹' + trade.profitLoss.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2}) : 'Open'}`
).join('\n')}

CONCLUSION
----------
${totalTrades >= 5 ? 'The requirement of executing at least 5 trades has been met.' : `The requirement of executing at least 5 trades has not been met. ${5 - totalTrades} more trades are needed.`}

This simulation demonstrates the basics of trading without risking real capital.
            `;
            
            // Create download link for summary
            const blob = new Blob([summaryReport], { type: 'text/plain' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'virtual-trading-summary.txt';
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
            
            // Also show the summary in an alert
            alert("Summary report has been generated and downloaded. Here's a preview:\n\n" + 
                  `Total Trades: ${totalTrades}\n` +
                  `Completed Trades: ${completedTrades}\n` +
                  `Total P&L: ₹${totalProfitLoss.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}\n` +
                  `Portfolio Value: ₹${portfolio.totalValue.toLocaleString('en-IN', {minimumFractionDigits: 2, maximumFractionDigits: 2})}`);
        }

        // Initialize the app when the page loads
        document.addEventListener('DOMContentLoaded', init);
    </script>
</body>
</html>