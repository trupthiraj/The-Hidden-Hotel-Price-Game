# The Hidden Hotel Price Game
### Why does the same room cost 3× more on Saturday — and can you actually beat the algorithm?

The trip finally made it out of the group chat. Flights booked, hotel sorted, 
everyone committed. Then someone checked the price the next morning and it had 
gone up £40. That's not bad luck. That's yield management — and hotels have 
been running it for decades while the rest of us just assumed prices were random.

This project uses 119,390 real hotel bookings to figure out what's actually 
going on. Not "here are some charts about hotels." What drives the price up. 
When the system can be beaten. And why almost everything you've read about 
booking early is wrong.

---

## What the Data Actually Says

**Book in winter.** That's it. That's the most valuable finding in this entire 
project. Season moves the nightly rate by nearly £30 in either direction — more 
than any other variable, more than hotel type, more than how far in advance you 
book. Everything else is marginal.

**37% of bookings were cancelled.** More than one in three. Hotels know this and 
price accordingly — which is partly why last-minute rooms exist at all. The 
algorithm isn't just responding to demand. It's hedging against people like us.

**Booking 90 days early saves £1.19.** The early bird discount is a myth, at 
least in peak season. Hotels have no reason to reward patience when rooms are 
filling anyway.

**Corporate guests pay the most. Online TA books the most.** Two completely 
different guests, two completely different relationships with price. A hotel 
that treats them the same is leaving money on the table.

**Portugal generates the volume. Luxembourg pays the rates.** Distance 
correlates with spend — guests flying further arrive with different expectations 
and book less on price alone.

---

## What's in This Project

Six interactive charts built in Plotly and Folium — not because more charts 
means better analysis, but because each one answers a different question:

- **Folium world map** — where the bookings come from and what each market pays
- **Violin plot** — how city and resort pricing distributions actually differ
- **Calendar heatmap** — when to book and when to avoid
- **Animated scatter** — whether lead time actually predicts price
- **Treemap** — which markets generate volume vs revenue
- **Waterfall chart** — the exact £ impact of every pricing factor, ranked

Plus a Tableau dashboard that lets you interact with all of it.

---

## Project Structure

```
hotel-price-analysis/
│
├── 01_hotel_analysis.ipynb
├── TheHiddenHotelPriceGame.html
├── chart1_global_adr_map.html
├── chart2_adr_violin.html
├── chart3_calendar_heatmap.html
├── chart4_animated_scatter.html
├── chart5_treemap_revenue.html
├── chart6_waterfall_adr.html
└── README.md
```

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python + pandas | Analysis and cleaning |
| Plotly | Interactive charts |
| Folium | Interactive world map |
| Tableau Public | Dashboard |

## Data Source

Hotel Booking Demand — Antonio, Almeida & Nunes (2019)  
[Kaggle dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

## Live Dashboard

🔗 [The Hidden Hotel Price Game — Tableau Public](https://public.tableau.com/app/profile/trupthi.raj/viz/The_Hidden_Hotel_Price_Game/Dashboard)

---
Checkout more projects at:
*[github.com/trupthiraj](https://github.com/trupthiraj)*
