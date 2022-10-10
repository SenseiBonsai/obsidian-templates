# Monthly-Report <% tp.date.now("MMMM YYYY-MM", 0, tp.file.title, "YYYY-MM") %>

# Work
- [ ] add hours and confirm time report 📅 <% tp.date.now("YYYY-MM-DD", "P1M", tp.file.title, "YYYY-MM" + "-01") %>
- [ ] add receipts and confirm expenses 📅 <% tp.date.now("YYYY-MM-DD", "P1M", tp.file.title, "YYYY-MM" + "-01") %>

# Report
```tasks
heading includes work
done after <% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM") %>
done before <% tp.date.now("YYYY-MM-DD", "P1M", tp.file.title, "YYYY-MM" + "-01") %>

group by filename
sort by description

short mode
hide backlink 
```

# Tags
#work/monthly-report 