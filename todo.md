# PoultryPro - Farm Management System TODO

## Phase 1: Schema & Design Foundation
- [x] Design tokens: elegant color palette, typography, global CSS variables
- [x] Database schema: users (with farm_owner/manager roles), flocks, daily_records, feed_purchases, expenses, egg_sales, bird_sales
- [x] Run database migrations

## Phase 2: Backend API (tRPC Routers)
- [x] Flock router: create, list, get, update status
- [x] Daily records router: create/update daily mortality + production data
- [x] Feed router: record purchases, calculate FCR and cost per bird
- [x] Expense router: create, list, categorize (feed, medication, labor, utilities, miscellaneous)
- [x] Sales router: egg sales (layers), bird sales (broilers)
- [x] Reports router: mortality rate, total expenses, feed usage per flock, profit/loss summary
- [x] Dashboard router: summary KPIs

## Phase 3: Frontend - Layout, Dashboard, Flocks
- [x] DashboardLayout with sidebar navigation and user role display (Farm Owner / Manager)
- [x] Global index.css design tokens (premium green/earth palette, Plus Jakarta Sans + Inter fonts)
- [x] Dashboard home: active flocks, today's mortality, feed used, revenue KPI cards + charts
- [x] Flock management page: add flock form, active flocks list, flock detail view
- [x] Daily record entry: mortality + production data entry per flock (layer/broiler)

## Phase 4: Frontend - Feed, Production, Expenses
- [x] Feed management page: record purchases, FCR calculator, cost per bird display
- [x] Production tracking page: layers (daily egg count, broken eggs charts) and broilers (weight trend)
- [x] Expense tracking page: categorized expense entries with pie chart and progress bars
- [x] Sales page: egg sales and bird sales tabs with revenue summary

## Phase 5: Reports Dashboard
- [x] Reports page: mortality rate per flock, feed usage per flock chart with FCR
- [x] Profit/Loss summary with revenue vs expenses monthly bar chart
- [x] Expense breakdown pie chart
- [x] 30-day mortality trend area chart

## Phase 6: Tests & Delivery
- [x] Vitest tests: auth, flock CRUD, daily records, feed FCR, expenses, sales revenue, dashboard, reports, RBAC
- [x] 27/27 tests passing
- [x] Final UI polish and responsive design
- [x] Save checkpoint and deliver
