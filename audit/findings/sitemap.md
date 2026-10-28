# Sitemap notes — 2026-09-25

- robots.txt declares: `Sitemap: https://baradaranebabaei.ir/sitemap_index.xml`
- `/sitemap_index.xml` → HTML 404 (Critical)
- Working: `https://baradaranebabaei.ir/?sitemap=1` (valid sitemapindex XML)
- Children declared: post, page, product, category, product_brand (pretty URLs also 404)

Fix: Rank Math sitemap rewrites / permalinks flush, then verify pretty URL returns `text/xml`.
