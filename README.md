# Adebayo Oluwasegun Emmanuel Portfolio

Hello, I'm Emmanuel.

I am a student and aspiring writer interested in:

- Financial literacy
- Wealth mindset
- Fintech ideas
- Strategic thinking

---

## Projects

### Wealth Mindset Ebook
An ebook focused on helping students build the right mindset for wealth and financial independence.

### Financial Literacy Content
Educational content explaining money, investments, and wealth thinking.

---

## Writing Samples

Coming soon.

---

## Contact

Email: maxemmanuel138@gmail.com
LinkedIn: https://www.linkedin.com/in/maxadebayo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin Operations Dashboard</title>
    <style>
        /* General Styling */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f4f7f9; color: #333; padding: 40px; }
        .container { max-width: 1000px; margin: auto; background: white; padding: 20px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); }
        
        /* Stats Bar */
        .stats-bar { display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin-bottom: 30px; }
        .stat-card { background: #fff; border: 1px solid #e1e8ed; padding: 15px; border-radius: 8px; text-align: center; }
        .stat-card h3 { margin: 0; font-size: 24px; color: #2c3e50; }
        .stat-card p { margin: 5px 0 0; color: #7f8c8d; font-size: 14px; text-transform: uppercase; }

        /* Table Styling */
        table { width: 100%; border-collapse: collapse; margin-top: 10px; }
        th { text-align: left; background-color: #f8fafd; padding: 15px; border-bottom: 2px solid #e1e8ed; color: #5d6d7e; font-size: 13px; }
        td { padding: 15px; border-bottom: 1px solid #e1e8ed; font-size: 14px; }
        tr:hover { background-color: #f9fbff; }

        /* Color Coded Tags */
        .tag { padding: 4px 10px; border-radius: 20px; font-size: 11px; font-weight: bold; text-transform: uppercase; }
        .high { background: #ffdada; color: #cf2a2a; } /* Red for High Priority */
        .medium { background: #fff4d1; color: #b7791f; } /* Yellow for Medium */
        .low { background: #d1fadf; color: #14532d; } /* Green for Low */
        
        .status { font-weight: 500; display: flex; align-items: center; }
        .status-dot { height: 8px; width: 8px; border-radius: 50%; display: inline-block; margin-right: 8px; }
        .dot-progress { background-color: #3498db; }
        .dot-resolved { background-color: #2ecc71; }
        .dot-pending { background-color: #f39c12; }
    </style>
</head>
<body>

<div class="container">
    <h2>Operations & Task Tracker</h2>
    
    <div class="stats-bar">
        <div class="stat-card"><h3>24</h3><p>Total Tasks</p></div>
        <div class="stat-card"><h3>08</h3><p>In Progress</p></div>
        <div class="stat-card"><h3>92%</h3><p>Success Rate</p></div>
        <div class="stat-card"><h3>3.5h</h3><p>Avg. Response</p></div>
    </div>

    <table>
        <thead>
            <tr>
                <th>REF ID</th>
                <th>TASK / ISSUE</th>
                <th>PRIORITY</th>
                <th>STATUS</th>
                <th>DUE DATE</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>#OPS-401</td>
                <td><strong>Quarterly Board Meeting</strong><br><small>Venue booking & itinerary</small></td>
                <td><span class="tag high">High</span></td>
                <td class="status"><span class="status-dot dot-progress"></span>In Progress</td>
                <td>Mar 15, 2026</td>
            </tr>
            <tr>
                <td>#OPS-398</td>
                <td><strong>Tenant Maintenance</strong><br><small>Unit 4B Leak - Contractor Assigned</small></td>
                <td><span class="tag high">High</span></td>
                <td class="status"><span class="status-dot dot-pending"></span>Pending Vendor</td>
                <td>Mar 14, 2026</td>
            </tr>
            <tr>
                <td>#OPS-392</td>
                <td><strong>Email Triage</strong><br><small>Cleared inbox to Zero</small></td>
                <td><span class="tag low">Low</span></td>
                <td class="status"><span class="status-dot dot-resolved"></span>Resolved</td>
                <td>Completed</td>
            </tr>
            <tr>
                <td>#OPS-385</td>
                <td><strong>Travel Research</strong><br><small>London flight options (4 delegates)</small></td>
                <td><span class="tag medium">Medium</span></td>
                <td class="status"><span class="status-dot dot-progress"></span>In Progress</td>
                <td>Mar 18, 2026</td>
            </tr>
        </tbody>
    </table>
</div>

</body>
</html>
